### What are Smart Actions?
Smart Actions are reusable JavaScript modules designed to perform discrete tasks within the Smart Environment. They serve as behavioral primitives that can be combined into sequences using Smart Collections or Action Groups, enabling complex operations through simple, modular components.

## Developing Custom Actions

### Smart Action Properties
- **env:** An instance of `SmartEnv` providing access to environment-specific functionalities like embeddings and chat models.
- **fs:** An instance of `SmartFs` for file system operations, ensuring consistency across environments.


### Browser Methods
`params.browser` is an object that provides methods for interacting with the browser (all methods return promises).

- `open(url, opts={})` - Open a browser window to the given URL
  - `opts.url` (string): The URL to open (required)
  - `opts.script` (string): The script to execute after the page has loaded
  - `opts.ensure_url_loaded` (boolean): If true, will ensure page is on the given URL before executing the script
- `run_script(script)` - Run a script in the currently open browser window
- `get_page_url()` - Get the URL of the currently open browser window
  - Returns false if no page is open

#### Authentication
Browser actions are run in a Chromium instance that is accessible by the user. Authentication is handled simply by instructing the user to login when prompted. Authentication data is handled securely in same way it would be in a regular browser.

### Built-in Test Suite

Each Smart Action should include a `test` constant that defines the test suite. This test suite is used to test the action in the Smart Connect app for full integration testing.

**Structure:**
- **setup(env, test_group):** Initializes the test environment, such as creating necessary files.
- **cases:** An array of test cases, each with a `name`, `params`, and `assert` function.
  - `name`: The name of the test case
  - `params`: The parameters to pass to the action
  - `assert`: A function that asserts the expected outcome of the action using the `assert` object provided by node.js

**Example:**
```javascript
export const test = {
  setup: (env, test_group) => {
    // setup test environment
  },
  cases: [
    {
      name: 'Append Text to File',
      params: { note_path: 'test.md', text: 'Appended text.' },
      assert: (assert, result, env) => {
        const content = env.fs.readFile('test.md');
        assert.strictEqual(content, '# Test File\nAppended text.');
      },
    },
  ],
};
