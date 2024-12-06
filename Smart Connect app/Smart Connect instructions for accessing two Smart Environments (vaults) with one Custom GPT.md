1) *Add a second vault:* you need to create a new "Smart Environment" in the Smart Connect app, similar to how you created the first, with the subsequent vault specified in the "Folder" setting.

2) *Create a second Custom GPT* where the second Smart Environment is configured using the Smart Environment dropdown in the Custom GPT settings.

3) *Create a new Custom GPT in the ChatGPT builder.*

4) _This part can be tricky: **you need to merge the "paths" sections** of the file at the "openapi.json" link (URL is provided in the Setup GPT section)._

5) *Copy & Paste the merged OpenAPIs into the "Schema" section* in the GPT builder in ChatGPT.

6) *Reference which vault belongs to with Custom GPT in the "Instructions" section of the ChatGPT GPT Builder:* The paths from the two OpenAPI schemas will start with the corresponding name of the "Custom GPT" as shown in the Smart Connect app (ex. `custom-1` and `custom-2`). Use the "Instructions" section like: "`custom-1` refers to my personal notes and `custom-2` refers to my business notes." 