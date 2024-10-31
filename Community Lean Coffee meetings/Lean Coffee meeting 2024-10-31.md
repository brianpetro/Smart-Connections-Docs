
## 🌴 Brian's notes
### Search in Smart Chat and Roadmap
I've been working on enhancing the Smart Chat functionality within Obsidian. Currently, the existing version of Smart Chat is limited to single-step interactions, and it's somewhat outdated. I'm in the process of rewriting it to allow for multi-step processes. This means that in the future, the AI will be capable of performing more complex tasks, like exploring through folders, analyzing multiple files, and providing more comprehensive insights.

One of the exciting features I'm planning to integrate is web search capabilities within Smart Chat. By developing Smart Actions that utilize the browser, the AI could perform searches on platforms like Google or Bing and scrape the results—all locally on your machine. This would enhance the AI's ability to retrieve and present information without relying on third-party integrations that might compromise privacy or add dependencies.

### Smart Connections Making Third-Party Content More Useful in Obsidian
Initially, I was quite strict about only including my own words in my Obsidian vault. The idea was to prevent clutter and keep the focus on my original thoughts, especially since Smart Connections was designed to help me keep track of them. However, as Smart Connections has improved, I've started to see the value in incorporating third-party content.

With the advancements in Smart Connections, third-party content can now be made available at the right times, enhancing the usefulness of my vault. This means that when I'm working on a topic, relevant external information can be surfaced intelligently, providing a richer context and deeper insights. It's a shift from solely personal notes to a more integrated knowledge system that combines my thoughts with valuable external content.

### Smart Templates: "Progression Mode" vs. Progression Dimension (Data)
I've been developing something I call Smart Templates. The idea is to have templates that contain prompts, which the AI can then complete to generate the desired output. Instead of the AI filling out the entire template in one go, I'm designing a "progressive template" system. This approach allows the template to be filled out step by step.

Here's how it works: The AI starts with the first prompt in the template, perhaps triggering a retrieval of relevant information, and fills out that section. The output from this step is then used as context for the next prompt. This iterative process continues through all sections of the template. The advantage is that it can produce better, more coherent results because each step builds upon the previous one, and the AI isn't overwhelmed trying to process all the context at once.

As for the "progression mode" versus the "progression dimension," they aim for the same outcome—improved outputs—but they function differently. The progression dimension refers to giving the AI access to the sequential history of a note—how it has evolved over time. This historical context can enhance the AI's understanding and improve its responses.

In contrast, the progression mode in Smart Templates refers to the step-by-step generation of content during the template filling process. It's about the AI's output progression in the moment, rather than accessing past data. Both concepts can work together: the Smart Template can use the progression dimension data to inform its progressive output, leading to more refined and accurate results.

### Other Related Information
My overarching goal with the Smart Ecosystem is to minimize dependencies and maintain as much control over the codebase as possible, especially in the open-source components. This ensures better privacy, reduces reliance on external libraries, and allows for more seamless integration of new features.

I'm also exploring ways to improve retrieval processes, both from a coding and prompting perspective. Effective prompting is crucial for guiding the AI to produce the desired outcomes, so any ideas or suggestions on how to better instruct the AI are always welcome.

Lastly, integrating features like root cause analysis into Smart Templates could be highly beneficial. By allowing the AI to iteratively question and refine the data inputted by the user, we can create more robust problem-solving tools within the Obsidian environment.

## transcript
##### 🌴 Brian
Hey there.

##### Gregorio Muraca
Thank you for the app.

##### 🌴 Brian
You're welcome. Thanks for joining us. Yes.

##### Matthew Oatts
Yeah, I will take zero credit for anything Smart Connections app related. I'm only here because the best way I can contribute is to facilitate discussions so called Brian and others.

##### 🌴 Brian
Well, it's a. It's an important contribution.

##### Gregorio Muraca
Yeah.

##### Matthew Oatts
All right. I'm getting stuff set up here on my side. I realized I should be logging in this, but I'll go ahead and post the link while we let others join. If anyone's going to join. It all depends upon, I don't know. Gregorio, have you watched any of the recordings before? Are you familiar with sort of how we structure some of these meetings or anything like that?

##### Gregorio Muraca
No. No. So it's new. I'm new to this.

##### Matthew Oatts
All right, sounds good. Well, here's the Miro link that we hop into and I'll share my screen. Are you familiar with the concept? I always do this sort of briefing just to make sure. Are you familiar with the concept of a lean coffee? Have you ever heard of that before? No. So it's a meeting structure style and you can actually, I think very early on, one of the very first ones, it's meeting structure style that's intentionally designed to be emergent. I don't know where somewhere in the link I'll find it. But the idea of lean coffees is we'll have a virtual whiteboard essentially of stickies and whoever's on the call, essentially, if you show up, then you're going to be a driver of what we would talk about. The idea is we have all the topics that we potentially would want to talk about. We stack, rank them and vote them and then the people on the call essentially will sort of use like a Kanban style. All right, let's talk about this topic for 10 minutes. If we want to keep talking about it, then let's keep talking about it. Otherwise let's move it off the board and do the other topic. So it's a way for us to have some degree of structure to what's very much supposed to be an emergent engaging conversation. It's sort of a lean coffee style. So with that I can actually go ahead and why don't we go ahead and hop into adding more topics and I think. Brian, did you predo some of these things. Here were these ones that you added earlier in the week.

##### 🌴 Brian
I was curious if you added this.

##### Matthew Oatts
I didn't add them. I don't know. Somebody added somebody. That's very cool. A little bit of. Proactivity here.

##### 🌴 Brian
Info.

##### Matthew Oatts
Yeah. Oh, fraun Additive. Cool. So given. I don't know if he's gonna join. So if he. If he doesn't, then we'll try to infer what is meant by those. But what I'm gonna do is start the timer here. Yeah. If you. If you right click and you go to info, you'll see who created it if they happen to be logged in. So looks like Fran Abenza added those.

##### 🌴 Brian
He's got some good ideas.

##### Matthew Oatts
Yeah. Cool. What I'll do is I'll start the timer here and then whoever is on the board, we can add sticky notes and then just essentially add them and then drag them to this topics panel here and then we'll vote on which ones we want to discuss and like in what order and that type of thing. And if you don't have anything, that's great. If you do have something you go ahead and add. I do have one that reaction to the new Obsidian web clipper, which obviously you saw I was very excited about. So anyway, I see got some other folks joining here. It looks like Boris has joined. Hi Boris, welcome to the meeting.

##### 🌴 Brian
Hey Boris, thanks for joining.

##### Matthew Oatts
I am not sure Boris is familiar with the lean coffee style meeting, but the gist of a lean coffee is we group get a list of topics that we might want to talk about and then we'll prioritize what we want to talk about and then just talk about it. So it's way to add a little bit of structure to what otherwise is an emergent meeting. So we're spending time about five minutes doing that. That also buys me time to log into Miro on my iPad so I can draw if we need to.

##### 🌴 Brian
And you can find the link in the chat, in the video or in the video call.

##### Boris Smus
I need to sign up, I guess.

##### Matthew Oatts
Oh no, I don't should. Yeah, I think I have a structured where it's free also just so that everybody's aware, we use an agent to record the meeting. That lets me take off the administrative effort of having like clipped parts of the meeting. So that's what you see is the sixth participant on the call lets me in 30 seconds be able to actually capture like previous meetings with, you know, clips and tags and stuff, not have to worry about it.

##### 🌴 Brian
Sweet. I actually was able to come up with a blog post based on one of our last meetings using the transcripts that you provide. Yeah, and I would like to do more with the videos, you know, so if afterward, if you have any links that I can get access to, like download the videos, so then maybe I can upload them to YouTube or something.

##### 🌴 Brian
I was looking around and I don't know if I have access. I might just need a link or something.

##### Matthew Oatts
Let me look real fast. Like, it's. There's one video that we definitely do not have the recording for. Yeah. And just disclaimer for Gregorio and for us, there was some nefarious bots that joined this call one time and started to screen share some less than desirable audio and video that we tried to quickly kick out from the thing. So needless to say, we don't have the recording for that meeting. So if you see people join, help me be aware of that. They made their presence known pretty quickly, but that's okay.

##### Boris Smus
I would love to have seen

##### Matthew Oatts
that recording and I think I do. I do have some of the recordings here. But yeah, Brian, I can give you. I might be able to give you guest access to green. So let's see. Cool. I got. I don't know if my eyes. 20%. Oh, and while we're. While we're sitting here adding things, Brian, I have. I've enlisted an intern who is essentially a local person. He's in community college, going to a local. He's about to go to a local university who I've known for a while, but he just wanted to get more involved in, you know, stuff that I'm doing. And I was like, I, you know, I. I can. I can't pay you, but I can legally engage you in something that's of benefit to you and not of benefit to me, like as a sort of an educational kind of thing. And so I started talking about what we're doing. He's going to get involved in this. But long and the short of it is I was like, one of the things that might be interesting is you getting involved in using this tool called Obsidian and this Smart Connections thing. And the gist of it was he was already using Obsidian. Like, I'd never talked to him about any of this. He was already using Obsidian and was already aware of Smart Connections. Oh, wow. So I was like, that's pretty crazy. Anyway, I think his name is. So his name is Zia Nori. He might be joining some of our meetings coming up, but. He's hopefully going to get involved too, in the community.

##### 🌴 Brian
Fantastic. Yeah. Just let me know if there's any way that I could help facilitate anything.

##### Matthew Oatts
Yeah, sure thing. Okay, cool. So here's the topics and again, Boris Gregorio, what we're going to do now is I'm going to select these topics and if you're in the Miro board, you will be eligible. Let me just do just sticky notes that you'll be eligible to essentially vote for which topics would be the things that you would want us to talk about. So I'm going to do three votes. We'll do it just a minute here. And you should see now something like this on your screen where you would join voting and enjoying joining voting. You can click on what topics you'd like to talk about and then we'll stack, rank that and use that as essentially our backlog of topics.

##### Gregorio Muraca
So we. One vote for each.

##### Matthew Oatts
You get a three total of three votes. So pick the top three things you might want to talk about and then it'll aggregate it.

##### Boris Smus
So there's a new web clipper. That's cool.

##### Matthew Oatts
Very excited about this. I encountered this, so I'm obviously gonna go for that one, but we'll talk about that. So be sure to vote and then the results will be tabulated.

##### Boris Smus
I don't know what half these are. What's an augmented conversation?

##### Matthew Oatts
What's funny is someone added that who wasn't able to join the meeting. So I don't think any of us actually know what that means.

##### 🌴 Brian
You know, I actually think I might have an idea where he's going with that because I've had some conversations with other people where it's like, imagine having AI, so it's like a third participant. So it's like me and you having a conversation, but then you have AI to kind of interject. I think that might be what it means, but it seems like we've already got our top three.

##### Matthew Oatts
Cool. We got these. That sounded interesting. So I'm just going to put that as sort of four here and then we'll go from that since it's all tied at three. You know, I'm just. If anyone objects to these being the three order, I think we should have plenty of time to get through all three of these topics in the next 45 minutes. So. Yeah. Okay, if we hop into this one at the top. Reaction to the new Obsidian webcover.

##### 🌴 Brian
Yeah. So did you want to lead on that one?

##### Matthew Oatts
And then.

##### 🌴 Brian
Yeah, let me know when like. Or how I should chime in. I mean, it's.

##### Matthew Oatts
Sure, I'll do that. I'll give a little bit of a demo of what I was actually tied to the thing I was talking about with new intern. So I. In a previous. So everybody knows, like, the context of why I found this incredibly interesting. In a previous Lean Coffee I had talked about, and I think it's up here, one a scenario where I essentially would leverage the Smart Connections conversations when I would encounter something interesting on the Internet. To have Smart Connections be the tool that dumps an article into my Obsidian vault if I just give it a link. So there's a previous video around that. But this idea of if people are familiar with like Pocket or any like URL, like archival type tool. I was talking with my intern about that and he was going to go build something that was going to essentially be a Python script that was going to scrape a website and then put it into an Obsidian article. And what we ended up realizing was, let's see, Chrome. I'm actually going to go to chat. Where is this? Except the link chat connection is at. Yeah, What I realized is recently, I believe, and Brian, you know these folks better than I do, but is Dynalist, like the Official company behind Obsidian md, Like, if you go to like Obsidian.

##### 🌴 Brian
So that sounds familiar. So it's probably right. But I think to your point, the person that developed this web Clipper, I believe, is also the CEO of Obsidian.

##### Matthew Oatts
Okay, cool. So anyway, and I'll put this link into the chat here. But I was like, this is blowing my mind, the fact that from an Official party there is essentially a tool. And I'll do this here. So let me go to like Gresky business Architecture so I can find like an article from a colleague here. Yeah, okay, cool. So here's a blog post, like an article. Every project need this. So what this tool does. And I'll see if I can safely bring up my Obsidian vault without disclosing private information here, I'll just go to this. This is good enough. Here's my Obsidian vault, like my personal vault here. What this tool does is it essentially adds an extension to Chrome where you can press this, it has formatting things that it can do and then it adds to Obsidian and it actually creates in the right folder structure, the article in an Obsidian note like boom. It just doesn't. And what this essentially is doing for me is obviously replacing Pocket, but as a practice, one of the ways that I use Obsidian. Is to try to begin to quite literally create an archive of things that are interesting to me that I encounter trying to get them into a format where my system of record, if you will, is a bunch of markdown tiles in Obsidian. So essentially the longer, the short of that is there is an Official extension now that allows that to happen. And I just found out from another colleague that there is a mobile version of this too. And I don't know that I have that up, but you can also get this for. Let me see if I can find it.

##### 🌴 Brian
Good to know.

##### Matthew Oatts
Yeah. So it is pretty slick. It works. Yeah. Here we go. Here's this copy link. I think the big thing that impressed me. Yeah, so there's this link too. And then I'll leave it at this. The big thing that impressed me that we can obviously have a conversation around it is it just works. It works really, really well. Like it scrape, you know when you get like reader view on a website article, it does it to that level of fidelity. It keeps images. If you look at actually some of the settings here, you can go to options and you get all of the options around shortcuts, properties that you can have different templates. Like I was messing around with templates, you can have all sorts of stuff. So all the things that you would expect from like a really well designed Obsidian plugin are built directly into this tool. And I can, you know, I can only imagine the use cases that people are going to be encountering around either doing this manually, like when you encounter something. But I mean you can get some agents going here and deploying these kind of things and having like a really clean. You could build that into your own personal like agent, like agent, like workflow where you can just start to scrape some other things around around that. So anyway, thoughts, comments, reactions to that.

##### Boris Smus
Yeah, I've been using a lot of Readwise and kind of have a pretty good flow. So like I have this script that just runs nicely and it takes highlights from Readwise and pulls them into my vault in Obsidian. So I feel like I got that dialed in and like the reading experience matters. I don't really want to be reading in the Obsidian vault necessarily. So I feel like I'm not entirely sold on this, but it seems useful, especially on mobile. That would be nice.

##### Matthew Oatts
Yeah, I used to use so that's that they have like that read wise Official plugin and I used to use that a good bit because I did like Boris to your point. And if people aren't familiar with that, if I recall correctly, what it does is essentially extract and put into Obsidian your highlights on articles, not just not the full article.

##### Boris Smus
That's right.

##### Matthew Oatts
Yeah.

##### Boris Smus
Yeah. Although actually I had my own flow that did a similar thing before. I think the, I think the Official integration does. This does pretty much what I have handwritten like a couple years ago. But that's the other thing. I'm not sure I want the full content of an article in my vault. It's like highly. Not like this is not what I, what I wrote, you know.

##### Matthew Oatts
Oh yeah, yeah, yeah, yeah.

##### 🌴 Brian
To your point, I like I had a pretty strict rule where I would only put my own words in my Obsidian vault. Yeah. And that's because, you know, when I first made Smart Connections, it's because I was losing track of my own words, you know, so I thought it would just be insane for me to be copy and pasting any third party content. But then, you know, with Smart Connections getting better and you know, imagining future improvements which will make the content be available at the right times, you know, like I'm starting to open up more, you know, towards having third party words in my vault.

##### Boris Smus
Interesting. Yeah, I have some third party words. Like, I have like a, like this random thing that does like collisions. It like tries to take two random nodes and like find the synthesis between them on a nightly basis using like GPT stuff. And. But the output of that goes in a special place. It's like nightly AI bullshit rather than polluting my corpus. So that's my sort of, that's how I'm trying to square that circle, I guess.

##### 🌴 Brian
Oh, interesting.

##### Boris Smus
So like the stuff that's not made by me goes in the special sequestered plays.

##### Matthew Oatts
Yeah, that's. I to your point. I think that's, that's naturally, I think what I'm starting to do with those things too. Like that that was going into a specific folder and Brian, this goes back to some of the conversations we've had that I've sort of struggled with in terms of using Smart Connections, being able to wisely direct Smart Connection, you know, interaction to just the things that I. That is original thought as opposed to the other articles and or incorporate other thought when I'm wanting that to happen. Like, you know, let's say I, I want to have something that's going to synthesize me preparing for one of my consultant meetings that needs to be exclusively only original thought and then bump that up against. All right, given this like my vocation and what I do is a lot of executive coaching and strategy and things like that. And one of the things that would be useful for me is when I have monthly one on ones with a C suite of a client. I don't have a lot of time to talk to them about things, but I would like to drop like, hey, here's some things over the last. 30 days that I've encountered that are sort of relevant to what we've been talking about. Being able to not just randomly go across the Internet, but instead go from my vault of articles that I've encountered that I didn't necessarily have the time to read all the way through, but might be relevant to this and give me three that are relevant to drop in somebody's inbox. Like that idea of a Smart Environment, being able to delineate those types of things is. Is neat. So by the way, just so that from a recording and perspective. And I don't know if this is exactly Boris, how yours got structured, but this was like an old thing that I used to use from Readwise. And what Read Wise is, was that integration was able to do is essentially pull some information and then as you highlight different parts of books. Like this was like when I was reading Leadership as Language, it would essentially continue to add highlights as you added them to like Amazon. And so and the link you would get, you can actually, I think kind of see here it would go to like a lead, a Read Wise link that linked to like this was like a Kindle source.

##### Matthew Oatts
So Morris was mentioning that that was a really nice workflow too to have that kind of stuff.

##### Boris Smus
Yep, yep. Very similar to my flow as well. And I assume it captures your notes and highlights there.

##### Matthew Oatts
Yeah, yeah, yeah. Gregorio, any thoughts on sort of this topic?

##### Gregorio Muraca
Yeah, I was searching that like because I don't have the account. So I just realized I need to do. To open the account and then do the donation and get access to the. To do. To this extension because otherwise it doesn't work.

##### Matthew Oatts
And then Smart Connect. No, this one goes to Smart Connections. You mean Miro?

##### Gregorio Muraca
No, the web Clipper.

##### Matthew Oatts
Oh, I didn't have to do a donation.

##### Gregorio Muraca
Well, I don't have the. What's called. It says here that I need to go early access. I need to start install the early access version. So I need the Catalyst license.

##### Matthew Oatts
I see, I see what you're saying

##### 🌴 Brian
is that for the mobile app specifically.

##### Gregorio Muraca
No, for my. I have a MacBook, so.

##### 🌴 Brian
So maybe the Mac version, Windows doesn't have this problem.

##### Matthew Oatts
I mean, I'm on a Mac right now.

##### Boris Smus
I'm on a Mac as well. There's. I didn't see any of that.

##### Gregorio Muraca
And it works for you.

##### Matthew Oatts
Yeah, yeah. And by the way, this is a perfect example of something that we can spend some time to work through because if you're encountering that, then other people are going to encounter it.

##### Gregorio Muraca
Or maybe I can enable Legacy mode in web clippers. Let me see.

##### Boris Smus
Are you in Chrome?

##### Matthew Oatts
Are you in Chrome? Yes. Interesting. That's crazy. I did not encounter that. I essentially went to. Maybe Did I go to the Obsidian? Maybe I gave a bad link.

##### Boris Smus
By the way, does Smart Chat conversation view, should that be working?

##### 🌴 Brian
Yeah. So are you having issues with the chat?

##### Boris Smus
Yeah, I haven't gotten it to work yet.

##### 🌴 Brian
What error are you seeing?

##### Boris Smus
Nothing, it just doesn't. I try to chat it and it doesn't do anything.

##### 🌴 Brian
Huh.

##### Boris Smus
Maybe I need some. Is this supposed to be like local chat or do I need an API key for something?

##### 🌴 Brian
So in the top right corner there's a little gear icon and you can add API keys or you can configure a local model but there's no built in local chat model.

##### Boris Smus
Okay, maybe that's it. But can I call like Olama?

##### 🌴 Brian
Yeah. So to do that you have to set the model platform to custom local. Okay. And then it gives you some options to configure Olama. If you search on the GitHub, there's like a few different issues and discussions of people showing their configuration that they've used to make Olama work. Got it. OK. Try to search Olama on the. On the GitHub.

##### Boris Smus
OK.

##### Matthew Oatts
Yeah, I'm glad Gregoro, you did you figure out sort of what the issue was? Which link were you using first of all? Was it the Chrome web Store one?

##### Gregorio Muraca
Yeah.

##### Matthew Oatts
Yeah.

##### Gregorio Muraca
So I think now should work. Let's see.

##### Matthew Oatts
Ok. Yeah. And again, for the benefit of IT folks recording, I have not encountered any reason why it would need to be paid for. So if you're encountering that, use caution and try to figure out how to not get. Go down a path to get it paid for. Yeah, let me see. I'm not looking like. Yeah, I'm not seeing anything there. So. Cool. All right, well let us know if we encounter any other issues with that.

##### Gregorio Muraca
Yeah, fine.

##### Matthew Oatts
Sweet. Yeah, and I. That's just going to personally help, I think a ton with that. Again, the big thing for me is it's, it's an obvious, you know, Pocket replacer. Again, if anyone watches this recording and is from Pocket, I'm not trying to like rain on your parade, but in the spirit of sort of why we all get together for both Smart Connections and then by sort of necessity Smart Connections is, you know, tied to Obsidian. One of the big drivers of people that reasons people use Obsidian is the idea of. Your information is retained by you. So like you, you're creating a bunch of markdown files and a bunch of collateral that you own locally. And that is going to be incredibly powerful now, but then going forward. And one of the reasons I just bring up this comparison to Pocket is two things. One, you know, if I look at saves that I've had with within Pocket as a tool, it's saving all of these things, but I don't actually have the source of all of this information. Right. I don't actually own the piece of data that's capturing the fact that at one point in time I saved this article from Ethan Molik. I don't have that data is stored within Pocket, so that can be frustrating. The other thing is I can't really do much with that. And so I'm sort of beholden to Pocket as its interface. Like, I can't tell you how much. It drives me crazy that when I go to Pocket it only shows if you look at the actual screen, like share of what I'm looking at. I'm only going to Pocket to look at the things that I've saved as a per. That might not always be the case, but they're using less than 25% of the real estate to show me only three things that I've saved and at least 50% of things that they're trying to get clicked through for me to click on other links. Like, as a business model, I understand why that's the case, but as a user experience, it's awful. So I would personally rather not behold it, be beholden to that type of experience when I just want to save an article. So obviously that's different if it's going into a markdown file that's in Obsidian. So that's why it was a big appeal to me. So anyway, that's enough of that topic, I think.

##### Charlie Potts
Yeah, I agree. Pocket sold out like five years ago

##### Matthew Oatts
when they started changing it like that. Charlie enters the chat and he goes, pocket sold out five years ago. I've never met you, Charlie, but I already like it my Pocket.

##### Boris Smus
Why not like another clipper? Why not Rewise?

##### Matthew Oatts
I didn't want to keep paying for Readwise and I liked Readwise experience. I just didn't want to keep paying for it. I was a big fan of Readwise and I just was like, I don't want to spend money. And also just like the time, energy and effort started to diminish because as people can sure to solve for my workflow, I encounter things that I don't have the time to actually read it. And I want, as quick as possible way to essentially, with low effort as possible, drastically narrow down the Internet to things that are relevant, based upon my human experience of what I've encountered for potential retrieval down the road by either me or an AI agent.

##### 🌴 Brian
Yeah, I think there's a lot of, like, future proofing involved too, you know, having all this as markdown. Like, not only does it make sure if that website disappears, that you still have that information, but also the markdown format is just so accessible, you know, for things like Smart Connections to parse it into useful data. And then, you know, I imagine in the future there's just going to be more ways to manipulate that markdown. You know, to provide value to you.

##### Gregorio Muraca
Yes, I agree.

##### Matthew Oatts
Cool. All right, next topic is web search and Smart Connections for Obsidian. I don't know what this means. So who wants to.

##### Gregorio Muraca
Yes, so I wrote it. So basically let's say you are. You are chatting with your, with the AI and then you want AI to perform acceptance search. Like yeah, if you try open. Open web UI.

##### Matthew Oatts
I've never heard of that.

##### Gregorio Muraca
It's a kind of UI where you have let's. It's like the copy of ChatGPT. And then you can add, let's say functionality like web search. So the model can start searching online and then you can add at some point also image generation. So ideally, let's say you are doing something you're reading and then you want the AI to start searching online and comes with new idea. It's like you improve. You enlarge your database of information by asking the AI, maybe you can find connection with something external of your vault and then bring it in and say, okay, there is this this and this that you could. You should look. No, it's about reasoning, more or less.

##### 🌴 Brian
Yeah.

##### Matthew Oatts
You know, so I think Stefano maybe brought this up. Brian, did he bring this up on a previous call too? So obviously I want you to react to it, but I'm trying to connect that dot.

##### 🌴 Brian
I don't recall for sure. But as far as search in the Smart Chat, Gregorio, just so I'm clear, you're specifically referring to the Smart Chat which is inside of Obsidian, right. And not the ChatGPT. Yeah. Okay. So, you know, because if you're using the ChatGPT, there's already that limited search capability that's provided there. You know where the Smart Chat is currently is. It's currently in a, like, it's in a bit of an in between phase because the code there is pretty old and I've been working on developing a new architecture for that code so it better fits into all of the other pieces of the Smart Environment. But I did want to bring up the open Web UI that you mentioned. That is a very interesting project. And I've considered like, okay, should I just replace the Smart Chat with this open web ui? And you know, because it does what it does really well. It's just I'm not sure that, you know, like, I would have to do a lot of like fitting like my current architecture to that architecture and that just adds like an extra layer, you know, so it would like remove the development of chat like. From my plate. But it would also add this development of transformations of transforming what I'm doing to fitting the Open UI or Web UI model. Basically, what I decided on is rewriting the Smart Chat so that it'll be more amenable to future developments like integration with Smart Actions. Smart Actions are what is used by the ChatGPT GPTs to access your Obsidian. And so I know I'm kind of going all over the place here, but the point that I'm trying to get to is that I see that search functionality basically becoming a Smart Action. And there, you know, the cool part about that is that, you know, the search that would be happening would like everything else, you know, in Smart Connect and Smart Connections, it would be happening locally, you know, so I did just record a video this morning showing the first custom actions that integrate with the browser. So these actions, you know, for example, will search Twitter and then return tweets or bookmark a tweet or schedule a tweet. And I imagine that the search capabilities would, you know, follow those same patterns where, you know, there's this new action and, you know, with the. With the new version of the Smart Chat, we will be able to utilize those actions very similar to how you can use actions and GPTs, except for those actions will be available in the Smart Chat in Obsidian. One of those actions could become a Google search, another action could become a Bing search. And, you know, we could even go further and use perplexity, because the way those actions are developed is that they're just using the browser to run the search, to scrape the results, and all of that happens locally. So to answer your question, there will be web search in the Smart Chat. I don't have a timeline for that. I think that it could be. The action could actually be pretty near in the future. It won't be long to develop that action. I think the biggest part right now is I'm rewriting the Smart Chat and there's a lot of things I want to do in that rewrite to make those conversations really deeply integrated into the Smart Environment. I think that has a lot of benefit as we move into the future where the environment can learn from your past. Conversations and you know, like, improve its outputs in the future. So like, you know, that's why I want that deep integration versus interfacing with something like the Open Web ui.

##### Matthew Oatts
I got a question for you, Brian. I want to make sure that I'm able to orient this. And by the way, what I'm drawing from is previously in coffee, by the way, if you ever see any very rudimentary drawings, it's likely my doing because I'm likely the least technical person on all of these calls. And so what I want to do again, to get it into Matthew's elementary understanding of what you're talking about, if I were to look at where like Open Web UI fits into all of this, I think what you're essentially saying is like, there's some architectural considerations as like, is there a link between Smart Chat plugin and Open Web ui or is actually, does that need to go more like directly here or do you not even do an integration there at all and instead evolve something about this architecture? Could you react to that, Brian? And then we'll kick it over to Matt Parker, who has a question.

##### 🌴 Brian
Yes, I need to update myself with all the capabilities of Open Web ui, but I do imagine that the Smart Connect app and the Smart Actions provided there which integrate with the Smart Environment, given that Open Web UI provides a sort of functionality like GPTs, which just off the top of my head, I don't see why a GPT type of thing, if they don't have it already, I don't see why it wouldn't be on the roadmap. And basically what that means is to enable the chat to access other API endpoints in addition to whatever is built in. As long as they have that, then the Open Web UI will be compatible with the Smart Connect app. I think that there are some UI things that's the reason why I think that I still want to have my own version of a chat, you know, so like, for, for the time being, I think, you know, like there still will be a separate chat, but I don't see why Open Web UI wouldn't be compatible. You know, given that they have a feature that is similar to GPTs in chat. GPT. Okay, does that answer your question?

##### Matthew Oatts
Yeah, yeah, yeah. Essentially I. Yeah, I'm hearing the answer to the question is part of how you're designing a lot of this stuff with intent is to focus on the things that you can focus on to make sure that. Compatibility with well designed other solutions is possible without necessarily catering and customizing what you're working on to ensure that there is some integration with third party. Because ultimately that's a slippery slope where now you're spending a bunch of time integrating with other things as opposed to. And you know, going back, way back into the archives of our Lean Coffees. This idea of, you know, you're trying to make sure that you're, you're focused more on innovation. Innovation as opposed to necessarily like integrating to an ecosystem that is so rapidly evolving that you'll stop innovating and just end up being a third party integrator.

##### 🌴 Brian
Yeah, and I think to sum that up, like part of the mission of like especially the open source side of things where I'm developing these open source components, it's to minimize dependencies. It's like I want to have all of the code in those open source components. Unless absolutely it's a hell yeah to include another library, for example Transformers js, which provides access to the local embedding models. I think that's a hell yeah.

##### Matthew Oatts
Cool. I know. Matt Parker, you raised your hand. What you got?

##### Matt Parker
Yeah, quick question. Thanks for the chat and everything. It's more of like a workflow question. So I use Smart Connections and Smart Visualizer, the plug, like kind of like the plugin that obviously visualizes the Smart Connections. And I'm more like asking more of like if anyone has a workflow. So I use Snip to take notes on like podcasts and books and that sort of thing. It all obviously loads into Smart Obsidian, Smart Connections. And then I'm using the visualizer to see like what notes I have obviously like link to each other and how to, how to view them. And I know, Brian, you had a video on like creating literature notes off of those notes, right? Where you're like condensing your thoughts into that. But I struggle with like finding like I take the notes and I go through. But I struggle with like actually spending like the time to actually link and write the literature notes to like condense my understanding of whatever topic I'm looking at. So I'm wondering if anyone has any workflows or recommendations on doing that.

##### Matthew Oatts
Basically. Cool. What I'm going to do, Matt, is and you can see sort of on the board here what we're doing is prioritizing certain topics and I've added another sticky to the board here so that when we get through the ones that were prioritized, we can either hit this or we can add the archive to go into the next one. Does that work for you? Definitely not. Trying to be dismissive. Want to make sure that the structure of what we're trying to do is gives everybody the opportunity to have the things that were prioritized to get into. But I think it's a great topic for sure.

##### Matt Parker
Sounds good. Thank you so much.

##### Matthew Oatts
Yeah. And then there's a link, by the way, snip was a thing.

##### Matt Parker
Yeah, the snip snip is pretty cool because it'll take in whatever. There's an app called Libation or Libration that downloads like the Audible books and you can load them through Snip and run AI processing on them. And then while you're listening to them rather than through Audible, you can just like click your steering wheel or headphone and it'll take a note of your whatever like you know section in the book that you're reading. And you can customize the GPT like the how it does. It's like a condensed version or long or custom. And then that all will load to Readwise and Readwise thanks to Obsidian. And then from there I use obviously Smart Connections to actually understand them, right? Because once you listen to them once, it doesn't mean you actually learn the topic intensely. You just have a better knowledge base. But then I'm trying to follow Cal Newport's techniques on Cal Newport's an author that goes over a lot of studying techniques and work planning and focus block planning, things like that, but actually taking them kind of writing in your own words and developing your understanding of whatever topic you're interested in. And then I think the cool part with Smart Connections is you can see how things web Interlake, Interlink and various books or articles you're reading and there's a lot of crossover that you're those random thoughts your brain has, but you can see them with Smart Connections. Like you can literally see that same type of thing on the, on the display.

##### Matthew Oatts
Very cool. So what I'm doing is and by the way, people are probably seeing in terms of personal workflow and I encounter certain ideas. I'm demonstrating what I like to do here, which is when I learn things that I don't know about, I often will ask Perplexity and then I will be able to copy the link to my consulting work I have become known for. If I don't know something during a meeting, I will hijack the screen share ask it in perplexity and then give everyone in the thing the link to the perplexity so that I can create safety for people that all of us don't have to know all of the things all the time. So here's that someone else. I've linked it to this and like

##### Matt Parker
why, like why to take notes. And I'm like, well, you don't know to. You don't know. You don't know something until you come across it. You know what I mean? Like you're not gonna know certain topics until you like dive into them. And then obviously that's where the Smart Chat comes in. Because you're like, as you're building out your thoughts on something, you could ask those questions that your lack of understanding or the gaps in something. So that's why I was like, have you heard of Dexa AI? It's like a podcast searching app. So if you just go to Dexa AI, it's like a data, not database. It's like a web face. And you can just search like, hey, Tim, what does Tim Ferriss think about this particular thing? Like, whatever question you have, and it looks through all of his. Podcasts and pulls out statements and then it'll actually just go straight to the video, like the section of the video that he's talking about it. And you can do like Andrew Hooperman or whatever author you're kind of interested in.

##### Charlie Potts
That's really cool.

##### 🌴 Brian
Yeah.

##### Matthew Oatts
All right, so I've taken. Thanks, Matt, for all of that decks. Thanks, guys. Appreciate it.

##### 🌴 Brian
Yeah, thanks for joining us.

##### Matthew Oatts
Yeah. So Dex, here, I'm gonna, I'm gonna just again archive some of this stuff and then we'll be able to hop into this.

##### 🌴 Brian
So were there any more thoughts on the web search topic? No.

##### Matthew Oatts
Gregorio, were you good on that one?

##### 🌴 Brian
I saw a thumbs up. He's on mute right now. Okay, cool.

##### Matthew Oatts
All right, next topic we had talked about.

##### Matthew Oatts
Did you, did you have anything else on web search, Gregorio?

##### Gregorio Muraca
Yes. So I saw that you on YouTube, some video that you can build in Python, your agent, and then it does web search through Terminal.

##### Matthew Oatts
Ooh, do you have a link to that so we can check that out?

##### Gregorio Muraca
Yes. So I was trying to post, I had a kind of file, but it doesn't allow me to have a markdown file. Miro, let me see if I can find the link of the video. Let's see. Yeah, if you can start going to the folder that's the other topic.

##### Matthew Oatts
I will. Okay. Yeah, if you do that, what I'll do is I'll, I'll grab that YouTube link and I'll. Here's this, this I saw Charlie Potts mentioned search, so I'll add that one into this, their topic here and we'll keep going. So, yeah, folder analysis. Who wants to kick that off while I do just keep taking notes around some stuff.

##### Gregorio Muraca
So what's my idea? Folder analysis. Basically, I saw that you can search or you can interact with the file, but let's say I have more files and they want. Not a summary, I want an understanding. I want an evolution of that topic that is made by, let's say five, six files. And they want some kind of exploration like, or thinking around it. So that's what's the idea. Because I saw you can just link one file. So ideally because it's an AI and it can handle multiple data. So the idea was how. How many data? Like it's only 4096 tokens. So you can do, let's say more like you can do, let's say one step, two steps and then start thinking about it.

##### 🌴 Brian
Yeah, yeah, you know, so right now I know you're using the Smart Chat in Obsidian and that has, you know, because it's. Still, that old version that I told you, I've been working on making the next version. So that first version is frozen. There's not going to be any more changes to that. But with the new version there will be the ability to do multiple steps. Right now, in that first version, it is just one step. So even if the AI, if it retrieves the folder structure and even if it wanted to say, okay, open up another folder and start looking through files, the Smart Chat in Obsidian is not capable of doing that right now. If you're using the ChatGPT, those GPTs like the Notes GPT, well, ChatGPT already has the built in capability to make subsequent or execute subsequent actions. So with the, with ChatGPT, you know, you could say, you know, start exploring through my, you know, this specific folder and you know, maybe build a report on this specific topic based on my notes. How you would go about instructing the GPT to do that, that is something I've actually been taking a lot of notes on recently because I think that one of the, you know, like one of the big next steps in improving the results that we get from these chats is some sort of system prompt that is able to instruct the GPT to continue its search until it like finds all of the most useful information and somehow exclude the information that might have came up but is not so relevant. So is that kind of where you're getting at, like having the GPT be able to take like a multi step process towards analyzing the contents?

##### Gregorio Muraca
Yeah, yeah. So you can have more than one fine interaction. Let's see.

##### 🌴 Brian
Yeah, definitely. I think that just falls under improving that retrieval process. It's definitely something I'm working on from both a code side and a prompting side. I think the prompting side is really important too. I don't know how familiar you guys are with code, but even if you're not familiar with code, if you have ideas about how to prompt the thing to do what you want, that's definitely interesting to me too.

##### Gregorio Muraca
Yeah, so I started doing the chain of thoughts since yesterday. So as I made the kind of prompt, like a system prompt that can, let's say, create a kind of structure in the way you approach any single prompt. So in order to have, let's say the same. Not style, but the same thinking approach between. How do you say, generation of that of information. There is a nice online. A nice video from George Hilton. They did a conference. I'm in Toronto now. And they did a conference Monday and Tuesday. So you can find on YouTube if you write George Hilton and they talk about the risk of AI and also the advantage. And it's nice talk. And then that's where I start doing this about this chain of thought. He was introducing an argument like the scratch pad, thinking that I think it's similar to chain of thought. I'll put the link now with the other one. And yeah, it's nice because you can. I mean, I mean it's a new way of coding at the end because it's a neuro nlp. No. So you give instruction and then the machine is able to perform the operation, the task by itself. So that's super cool.

##### 🌴 Brian
Yeah, I do. I have a thing that I'm working on, depending on how much you follow my work. Like something that I've been working on is what I call smart templates. And a smart template is basically like imagine having a template with prompts in it and each prompt is completed by the AI to output the output of the template. It's like a template that gets filled out by AI. But I think I've been designing it is so that it can actually be a workflow. Even though it's like a template, you draft this template. Imagine the template was like a standard operating procedure sop. Then instead of having that template generated all at once by just one response from the AI. What I'm anticipating calling it is a progressive template. Or using, say if you're making the template in markdown using frontmatter to define that the template should be outputted progressively. What that would do is instead of outputting the results of all the prompts in the template all at once, it would start with the first prompt. That prompt could trigger a retrieval, and then it would output into that first section of the template and then feed that output into the context for the subsequent prompt. It would do that for all of the sections of the template, which I imagine would provide a better output. Instead of just trying to come up with all the context at once and then outputting. For all of these prompts all at one time because it would be this like progressive or iterative approach.

##### Matthew Oatts
Is that by the way, did I find these right links here?

##### 🌴 Brian
What's that?

##### Matthew Oatts
Did I find the right links here? As you were talking, I was trying to bring up some of these things. So like I see you have a video here. Is that what you're talking about?

##### 🌴 Brian
So yeah, that's the very start. So like what's out there? So there is an Obsidian plugin, I call it Smart, Smart Templates, which has the first iteration of this concept. But I've been working on the second iteration of it and the next iteration when that's released, it will have these capabilities of progressive execution. I want to add a multi step execution, goes progressively through the template but also then repeats, you know, because maybe like as it got farther down to a later section, you know, it discovered something that would impact, you know, the first section. So then maybe you could say, you know, execute this or like create this or render the template progressively, but also do it three times, you know, so then the final output would be the third and you know, so I think question for you Brian,

##### Matthew Oatts
just to connect us to some of the other. Is this tied to that idea of like the progression dimension? Like this idea like you've talked in others lean coffees around. Like part of your intent and design for Smart Connections isn't supposed to be just transactional, but actually is supposed to be able to like progressively elaborate on and not just look at the data that is retrieved in sort of its static state, but then keep up with the change control. And like I think I did again really crappy diagram of this last time. But this idea of your first notes was like you have ChatGPT look at something notes and then retrieve something back. But then like the future of these things is both being able to look at parts of your note and changing parts of your note, but then being able to look at what you've changed over time as you've changed parts of your note and use that to have better overall outcomes in terms of how you're interacting with Smart Connections. Is that similar theme of what you were just talking about with smart templates.

##### 🌴 Brian
So the desired outcome of both is the same, you know, which is just improved outputs. The what I was just talking about would utilize that, what I was calling like a progression dimension basically that has to do with the, you know, like basically giving the AI the ability to retrieve like sequential memories, you know, like if you imagine how did you improve this note over time, you know, like. Having access to that data. That's sort of what I was calling the progression dimension in the memory context. But as far as the smart template thing goes, it would be progression in the form of outputs from the AI. It's like when the one is, they both would work together, the smart template would retrieve that past data of progression. But then this progression template rendering would be like right here, right now, generating a progression of output.

##### Matt Parker
Would this work for. I'm a manufacturing engineer, but root cause analysis, you know what I mean? Because I almost feel like that. Is that because root cause analysis you're using, I can send you a template that we use, but it's like a 6W 2H. So you're kind of getting the overview of the thing, what, when, where, who, why, how much, how many. And then you kind of transfer that down into a fishbone. And the fishbone is like a problem solving technique. And you're iterating exactly what you just said though. You're iterating through a problem solving process and it's refining it. Because as you gather information, right, you're figuring out top causes and you're ending up with a root cause analysis of some breakdown or whatever. But I almost feel like that's what that template is doing that you're

##### 🌴 Brian
saying, yeah, I think using that root cause analysis template that you already have, putting it into a smart template that can be executed progressively. I think the difference is you would get a better output from this progressive generation rather than if you just dumped everything into chat in context, you know, and just one shot at it.

##### Matt Parker
One. One problem I always see in the, in the root cause analysis is people have trouble, like questioning the data they're entering, right? Because you, you're. It's like you're of this single track mind. So maybe we could work on that. But like, I could definitely see an RCA version of this that like, as you're inputting information, the steps like the sys, the template, right? Would question you on like on some fact that you're putting in, right? If you think something is broken down for some specific reason, it can give you like that branch of like. Well, did you consider this? This, this.

##### Matthew Oatts
Cool, cool. I know we're a couple minutes over. This was a really great conversation. What I do every time is in this mural board, I will essentially use the agent that we have that's joined us to break down each of the parts of the conversation. I'll paste that into the green folder here or the green spot on this Miro board, and then we can always. This is always persistent. So we can use this backlog of topics to maybe feed the next topic. Appreciate everybody accommodating the reschedule and then Matt, I think it'd be really cool. I just. Flagged your root cause thing if you have the time, energy or effort if you could maybe put some links to some of that near this post it note I'm going to stick that up in this other topic here.

##### Matt Parker
I can flatten out a template and send it to you but like it's a it's actually I work I work for manufacturing but it actually came from Procter and Gamble is who actually developed this but I can I can push that if you guys have any ideas of how to you know build that out I think that'd be I mean a lot of businesses use this right so it's like it definitely has a use case for it.

##### 🌴 Brian
Yeah it would be interesting to see and I'll keep that in mind as I'm designing and putting things together.

##### Matt Parker
Sounds good.

##### Matt Parker
I'll try to upload it to you guys and then go from there.

##### Matthew Oatts
Thank you again for your time. Sounds good. Thanks everybody.

##### 🌴 Brian
Thank you for joining everyone. 😊🌴