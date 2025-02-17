---
title: "Smart Connect Update: Let's Dive into Community Actions and Custom GPTs"
ogImage: assets/sc-app-update-2024-10-31.jpg
---
![](https://www.youtube.com/watch?v=GCn3u2F2tZM)

Hey there, it’s Brian. Today, I want to walk you through a feature update I just shipped in Smart Connect, something I’m pretty excited to share—Community Actions. This new update, inspired by the community plugins in Obsidian, opens up a way for you to customize Smart Connect with your own actions, adding some serious flexibility if you've been looking to get creative with automations and integrations.

We’ll start from scratch, download the update, and go over setting things up. For anyone already familiar with Smart Connect, this should feel pretty intuitive, but there are some new things to note if you want to get the most out of it.

### First Up: Downloading the Update
So, if you’re logging into Smart Connect for the first time since this update, you’ll see version 1.3.11 is ready to download. Once it’s installed, open it up, and you’ll notice some changes. I’ve added a section for Smart Actions where Community Actions will live, as well as a more refined system for managing Custom and Official GPTs.

### What Are Community Actions?
Basically, Community Actions are like custom plugins that allow you to add new functions not initially built into Smart Connect. They’re perfect for anyone who wants to expand beyond the default set of features and get creative with their Smart Environment.

I’ll show you a few examples of how you can use these Community Actions, but the main idea here is that you can install actions contributed by other users or even create your own. These actions live in a public repository, so you can inspect, tweak, or be inspired by other actions, which opens up tons of possibilities.

### Getting Set Up
When setting up Smart Connect, one thing I recommend is naming your Smart Environment the same as your Obsidian vault, if you’re using it in tandem. This makes sure everything runs smoothly, especially if you’re using note-specific actions that require compatibility between Smart Connect and Obsidian.

Now, once you go to Smart Actions, you’ll see two new sections—Official GPTs and Custom GPTs. Official GPTs will include pre-built actions that come with Smart Connect and will always be maintained to ensure stability. Custom GPTs, on the other hand, allow you to pick and choose specific actions you want to use, and even customize the system prompt.

### Installing Your First Community Action
For this walkthrough, let’s install a “List Tweets” action as an example. Go to the Community Actions section, hit “Install” on List Tweets, and you’ll be prompted to restart. After that, you can see List Tweets in your Custom Actions list.

With this action, I can go to my Twitter feed or a specific Twitter list and pull up tweets, like, or bookmark them directly from within Smart Connect. To add more actions like “Bookmark Tweet,” it’s the same steps—just install, restart, and it’s ready to go.

### Creating a Custom GPT
The flexibility here is that Custom GPTs can be configured to use only the actions you need, which means you don’t have to worry about extra functionality cluttering up your workflow. Just add the actions you want to use, save it, and start giving it commands.

A quick pro-tip: When setting up the custom GPT, you’ll paste the OpenAPI URL in the import section. This URL is basically what tells ChatGPT which actions are available and how to use them, which I’ll be expanding over time to make adding new actions even easier.

### Real-Time Action with Twitter
Now, let’s see it in action. Let’s say I want a quick report on the top Obsidian-related tweets in my Twitter feed. I can ask ChatGPT to search my feed and even bookmark specific tweets, like those showing cool Obsidian workflows or personal knowledge management tips. Just type in your request, and it’ll pop up a Twitter window to do exactly that.

A heads-up, you’ll want to be logged into Twitter first to make this work seamlessly. If not, you’ll get a prompt reminding you, so no worries if you forget.

### Customization and Future Ideas
The cool thing about Community Actions is how customizable they are. Since they’re built on JavaScript, you can create actions for whatever platform or workflow you’re using—Twitter, LinkedIn, your inbox, you name it. I’ve designed these actions to open a Chromium browser on your desktop, which helps interact with websites as if you were doing it manually, making it easy to get around API restrictions on platforms like Twitter.

I’ll keep updating the public repository with more action examples and documentation on creating your own actions. But if you’re already familiar with JavaScript, I think you’ll find it easy to start adding in custom actions.

### Wrapping Up

So, that’s a quick look at Community Actions in Smart Connect. I hope you find them as useful as I do! Whether you’re looking to automate your note-taking process, curate tweets, or manage multiple workflows all in one place, Community Actions is here to give you that extra flexibility. And as always, I’d love to hear how you’re using it. Drop a comment, reach out, or contribute your own actions to the public repository—I'm all ears! Thanks for checking it out.