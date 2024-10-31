##### Matthew Oatts
Of a church, and I was a leader in the church when the pandemic happened. And so I was, like, the youngest person, and I was the one that had figure out how we're gonna do, like, virtual services and all this kind of stuff. And at that time, you know, teaching a bunch of people who could barely know how to access their, you know, email, how to join a Zoom meeting, and then what to actually do on a Zoom meeting and all that stuff was a whole experience. But one of the things that we very quickly learned that we needed to do is to have everybody always be on mute when they join. And we didn't do a waiting room, but we definitely had, like, a moderator who was, like, ready to kick people out, which is very weird in a religious situation, to be like, oh, who's going to get punched out of the room next?

##### Stefano Coppo
I know.

##### Matthew Oatts
Yeah.

##### Matthew Oatts
Excommunicated from the Zoom call. That was fun as a member of a community trying to figure out how people and technology, you know, interact with that.

##### Stefano Coppo
So.

##### Stefano Coppo
Well, obviously, I hadn't really factored that into my calculus that, you know, I'm used to meetings that are closed, business meetings, you know, and you have a prescribed list of attendees, and. But then when you open this up broadly, you know, for a public forum, boy, you got to be guarded and ready.

##### Matthew Oatts
You saw me. I wasn't really ready. I was. I told my wife, and I was like. I was like, I don't want to. I certainly don't want to watch what happened, but I want to watch everybody else's reactions. I was like, yeah, so I haven't gotten around to doing that yet. But anyway, all right. People will be mysteriously confused if they watch this recording as to what we're talking about, but it's a secret. All right, so I'm in the Miro board. I can share my screen. And then one of the things I'm thinking, since at the moment it's the same crew of folks, is maybe we could just, like, go back to where we left off last time. I could copy that down. Let's see.

##### 🌴 Brian
Not the screen. Yeah, that sounds good to me.

##### Matthew Oatts
Just the right screen. Yeah. Okay, here we go. So we can just change this to be the September 6 and 20th meeting, and then maybe take a look at where things landed here. And if there's anything I do. I mean, I got to go look at my notes. I do want to have, like, three or four minutes to find some stuff that I had compiled to add to the board. So maybe I'll just start a timer for I'll start a timer for, like, four minutes, and then we can add extra topics if you think of it. And I'm going to have to find where it's and. Was.

##### 🌴 Brian
Yeah, I just added a couple topics that came up on the GitHub where, you know, they're pretty, pretty broad topics. So I didn't want to, you know, be spending the time answering in text. I figured this would be a good format.

##### Matthew Oatts
Yeah. Oh, that way too. We could record it and you could have the clip and then you could post a clip to. This is how we answer the question. So by the way, I'm totally cool with that. If you, if there's things where you sometimes, especially if it's like not too many people, you know, I'm not going to speak for Stefano here, but Brian, if there's like a. You have a backlog, it's just going to be easier to talk about these things, you know, and just knock out things quickly within the hour of the lean coffee.

##### 🌴 Brian
I'm perfectly okay with that. Yeah. So I added them in there in case you guys are interested in the topics. But, you know, I don't like, at least this time, I don't feel like we specifically, specifically have to get to them. I think it was Justin from the community is the one who posed the questions. I invited him. So, you know, if he shows up, I think that that would be a good time to go into it. But, you know, if he doesn't show up, then I'm fine with sticking to, you know, whatever we agree is top priority today.

##### Matthew Oatts
I've added a couple that are sort of minor, mostly because I sort of troubleshoot. Troubleshooted. I don't know what that word is. Some things on my own and I couldn't figure out actually how it works. So I added a few things here. Stefano, did you have anything else you wanted to add to the Miro board?

##### Stefano Coppo
No, I'll follow the lead here. I do have some technical glitches I'm running into, but I noted we're not to address those unless they've been documented in the get. So I want to wait until I can properly document them and then we can go from there.

##### 🌴 Brian
So, Stefano, those are probably that you're referring to the Smart Connect app.

##### Stefano Coppo
Yeah. Thank you for your help. It was my oversight as far as custom GPT, so I've got that. But I'm running into some other issues that I want to just really understand before I throw out a false negative. So I am having some issues with that and just chatting with my notes, basically my resume to job description matching. Is kind of broken at this point, so.

##### 🌴 Brian
Okay, yeah, if you create a GitHub issue, I'll definitely check it out. But I just want to also mention that the Smart Connect app is a little bit behind right now. You know, like I pretty much spent since the last meeting getting the plugin up to speed. And, you know, now a lot of the changes that happened in the plugin, you know, since they share the same, a lot of the same open source components, the Smart Connect app still needs to catch up. Plus there's a few things I want to add specifically to the Smart Connect app. So whatever the issues you're running into, if you post about them in the next few days, that would be a great time because I'll be hopping into that code.

##### Stefano Coppo
Okay. And when you speak to shared open source, is that your JSBrainss?

##### 🌴 Brian
That's correct.

##### Stefano Coppo
Okay.

##### 🌴 Brian
Yeah, there's, you know, I would say 90% of all the code is shared between the plugin and the app via those JSBrainss components.

##### Stefano Coppo
And as I track your changes and the change logs, I do detect that you're making changes to the JSBrainss, which then are foundational to probably the plugin and the Smart Connect proxy.

##### 🌴 Brian
Yeah, yeah. So long term vision for JSBrainss is actually somewhat like a framework that people could use to build, you know, similar, similar software. So, you know, like a lot like, there's kind of almost like a meme in the AI space, which is like, all of these startups are like, they're essentially chat with your PDF startups. Yeah. You know, so I think that with the open source components that I'm building there, you know, I could provide a demo or like example where it's like build this chat with your PDF application and really very few lines of code, and that application would work in the browser. There could be another example to make it a desktop app. The beauty of that open source project is it's all vanilla JavaScript for the most part. There's a little bit of node js in there. I actually make it not dependent on node JS because that's what enables the mobile version of the Obsidian plugin to work, because the mobile version of Obsidian does not have access. To node js, like the desktop app does. But that side effect makes it so that the code in that open source repository ends up working virtually everywhere that you can run a web browser.

##### Stefano Coppo
Yeah, no, very elegant. I think. So I like the architecture, and I kind of followed that as I saw the micro changes you were making to JSBrainss.

##### 🌴 Brian
Yeah. And then just one last little bit. The JSBrainss. The reason for the name is because I spend a lot of my time learning about the brain. And, you know, there's specifically this guy, Jeff Hawkins. He writes the thousand brains book and also on intelligence, and he takes a look at, like, how the brain works, but from, like, a technology perspective. And I really. It's. I really think it's, like, one of the best architectures for building an intelligent application that I've come across. So a lot of the changes are, like, me trying to figure out how can I make the code better reflect this cortical architecture. And the beauty of that is, if I can get it to emulate that cortical architecture that he describes, it's like a recursive type of system. So really, it's like, once that base is developed, that base architecture, you can just add layer upon layer upon layer. And with those layers, I think you can do really, really cool things. So that's the high level direction, you know, from a. From a cognitive architecture standpoint.

##### Stefano Coppo
Okay, cool.

##### Matthew Oatts
Sweet. That was a fun little side conversation. So I captured some notes around that here.

##### 🌴 Brian
Oh, cool. Yeah. And if you guys are interested in the cognitive architecture stuff, I think his books are very accessible. You know, like, they're. They're fun listens, and I. You know, like, I think he does a great job of, you know, packing a lot of information in. You know, I can tell you that, you know, I own the hard copies and the audible versions of both books. You know, like, I've. I've highlighted the. The hard copies, and I've listened to the audible versions of each book. Easily a dozen times, which is, you know, pretty, you know, it's like that's, that's definitely an outlier. You know, like, I listen to a lot of books multiple times, you know, when they, when they deserve a re listen, you know, but approaching a dozen times, you know, for each, I think, really gives, you know, credit to the, the quality of information he has in there.

##### Matthew Oatts
How do you, what is, what is this word? Cortical architecture.

##### 🌴 Brian
Yeah. So it's like, you know, I guess, you know, like a derivative of the cortex.

##### Matthew Oatts
Cortical architect. Is that how you spell it?

##### 🌴 Brian
Yeah, that looks correct.

##### Matthew Oatts
Architecture. All right, cool. I put a little link to your JSBrainss thing here. And then I also put a link to. And I told you about this hack that I do when I explain things to people. I just ask perplexity and then copy the conversation so people can have all the little nodes to go off of. Oh, yeah. While you guys were talking, I just essentially terribly misspelled the question. Tell me more about this and all that kind of stuff. And so it generated a little article for us around that. So I included those links and some fun stickies to get us going here.

##### 🌴 Brian
Yeah. Yeah, that's a. I love how you do that.

##### Matthew Oatts
Cool. All right, so I'm going to, I personally think instead of voting, I. Stefano, I don't know about you, but I'd love to have Brian just dealer's choice, pluck some of these things off based upon what's top of mind for him if, like, I don't have a strong opinion about any of these topics. So, Stefano, what do you think about offering Brian that opportunity?

##### Stefano Coppo
I concur.

##### 🌴 Brian
Okay.

##### Matthew Oatts
Okay. Go for it, Brian. Let me just tell you which one you want to talk about.

##### 🌴 Brian
There's two at the bottom. You know, those are the topics that I mentioned, you know, were brought up on the GitHub. So since they've been. Yeah. So since they've been in my mind, I'll just, I'll give a brief overview of my thoughts there.

##### 🌴 Brian
So, you know, to elaborate on the software stability question. You know, the, the sentiment was, you know, like, you know, now that the plugin is working properly, like, is there a way we can ensure the stability? And I definitely see why that would be desired. And it's something that I do try my best to accomplish. I want there to be a stable version of the software so any new user that comes to get the plugin can just hop right in and not have any issues. But the trouble is, is that I see stability being on a spectrum with innovation. And the more stable the software, I think it's going to reduce the innovation of the software. So while I try to keep things working, I really don't want to promise stability because I think it's the innovation side of the spectrum where ten x outcomes will develop. And that I think contributes more to the primary mission, which is empowering individuals with AI through this open source software by leaning towards innovation, I think even sacrificing stability for intermittent periods of time. I think in the long term we will better empower individuals with AI by discovering new innovations, by worrying less about stability and focusing more on what might a ten x improvement look like. I also, from the development side of things like I created the early release for supporters so that there could be some level of stability in the main release. But there's always this period of time where I need to update that stable release or update that general release, and that's where the instability starts to, to arise. So I would love to say that the software is going to be stable from here on out, but I think that's a promise I can't make, and it's one that I don't think I want to make because I think for the long term mission, innovation is the goal. So did you guys have any questions about that?

##### Matthew Oatts
I do. Do you mind if I ask you some almost interview style cutting questions? Because you know me, I support your mission wholeheartedly. But then I do think there's a perspective that I think people would want that like better understand. So you mind if I like, sort of like I'm going to seem like I'm coming at you, but I'm actually just trying to challenge you because I think it would be healthy to have people better understand what you're getting at. Is that okay?

##### 🌴 Brian
I 100% love that. Okay.

##### Matthew Oatts
You know, cool. Sounds good. So a question. One question that I have for you is if stability is necessary for there to be a adoption and usage, then where are you positioned? Part of me goes to from a Runway funding vision perspective, if that were to happen and then user base were to drop. Or I think more importantly, the cohort of people who are deep power users give up and potentially don't return. How does that impact your journey towards your vision? Is that you seem to be describing that the conditions don't require you to, like, stability isn't as necessary as maybe certain power users or people, you know, believe that it should be. Is that what's, is there any truth in that? Like what's your position with respect to that? Does that, first of all, does the question make sense? Because I just thought of a simpler way to ask the question.

##### 🌴 Brian
So if the question, so if you think there's a simpler way, that will also give me some.

##### Matthew Oatts
If your user base were to plummet, can you still continue?

##### 🌴 Brian
So I think that the answer to that is yes. Because while the like, that would be negative, that would be a negative impact on progress. The reason why I think I would still be able to continue is that there is a lot to do with marketing and growth type of plans that I've been sort of just collecting these like, ideas and these different like avenues and directions. I could go along those lines. So I think that the recovery from that situation is very much doable.

##### Matthew Oatts
And for this helps provide clarity, I think, which is useful, I think I'm cracking exactly what you're saying.

##### 🌴 Brian
Yeah, because I think that I've been putting the marketing and growth in the same bucket as stability. Where like right now, if I spend my energy on that marketing and like growing the user base, then that actually not only directly takes my focus away from the innovation, but it also increases the need for stability. Because presumably, if I'm going on that marketing growth route, I'm trying to either sell more subscriptions or get more supporters. So then I feel more obligated to keep those people happy and that would increase the urgency and the importance of that stability. But, you know, right now I have a pretty okay Runway where I can feel comfortable just going the direction that I see best for creating the best software and the best innovations with regards to that, for at least the. Few months. Even if all the revenue stopped coming in today, I could still keep going for at minimum a few months, and then that would be prior to me even switching gears into the marketing. I would also still want to leave myself a few months to get things going again from the marketing and growth standpoint. But if everything dried up today, I could still spend a few months working on improving those innovations. And when I came back to the marketing and growth plan, assuming everybody just was like, okay, this doesn't work, we're not using it, well, then I would actually be able to move even faster on the innovations and I would hope to come back with what instead of being, hey, this is the same as all those chat with your PDF startups, except for it's in your Obsidian. You know, like, instead of just being like this alternative to all these things that exist, I would come back to the market with something extra, something new. And I think that also lines up with how I see this persisting into the future. Because if I have a very stable software that does the same thing as a bunch of other software out there, then eventually people are going to say, oh, well, you know what? I'm already in Google Docs all the time, so let me just use Google's notebook LM, or like, I'm already in Microsoft, so let me just use copilot. Like, if I don't focus on the innovating, I think that that same drop in users is going to happen regardless of the stability, because there's going to be equivalent alternatives that may be more convenient than what's in Obsidian or with the application and ChatGPT.

##### Matthew Oatts
Cool.

##### 🌴 Brian
Did that answer your question?

##### Matthew Oatts
Yeah. So I was sort of drawing this little picture, and for me, what it does is, as someone who's bought into the mission, but quite frankly, also my usage has absolutely tailed off in the last, I don't know, three months part significantly because my own factors, but also because it's difficult to get back in the pool if wherever I left things off and the settings don't work. Like, I don't even know if you noticed this, but in the last recording when I was like, oh yeah, what about this little field? You probably didn't even notice that I hadn't even filled in the required fields to have the thing even work at all. And so you could immediately see from my configuration that nothing would work. Well, I hadn't seen those fields because I hadn't been in the pool for the last, you know, 30 days. And so part of what's useful and what you're describing, and I sort of got a little bit of like, My product manager type hat on here is like, with effort, intent. Part of what I heard you just describe as a story is like right now you're experiencing some growth without any effort or intent. So you're sort of at this inflection point is if you stop, and I actually think this is what you described as a little bit different than this, but like, you could just keep trying to make things stable and things might continue to increase. I think what you're saying is that green line actually tapers off and go and crashes permanently if you just focus on stability. Whereas if you do a little bit of mix of both, then you might be able to stay, but it's still going to recover if you don't actually worry about stability, sure your users might plummet, but to the point, this black line where if they do get low, all you have to do is actually turn on with like, effort and intent around marketing if you needed to do that. So I love how you're characterizing the fact that, like, the growth right now is based upon, you know, not as much intent around trying to grow user base. So you can afford to have attrition as much as it, from an emotional perspective, might frustrate users because they've invested time, energy and effort into a thing that they just want to work for them the way that they encountered it at first. Like from a bigger picture impact, you are differentiated enough that if you focus on innovation, it might hurt a little bit with some people, but it gives you the better shot that months down the road you'll have something that they won't be able to get to again from anywhere else, which is, quite frankly, where they encountered you the first time. So I totally am picking up

##### 🌴 Brian
on, I love this diagram here. I think that yellow, you know, like while the green would be great, I think the yellow is definitely what I anticipate happening. You know, like at some point it's going to tail off and I'm going to need to put that effort in the marketing. I mean, that's been the plan the whole time. I see the current features, and this is probably, in my opinion, you know, why things like really tailed off for you, is that the features are more of a novelty than truly useful. Yeah, like, and the reason why I know that is because I build this software, the reason I first built it was for myself and I want to use it myself and even my own usage, you know, I see it tailing off. As far as the Smart Chat within Obsidian, I very rarely use the Smart Chat in Obsidian. I'm I much more frequently use the ChatGPT version. But even that, you know, like besides the transcribing, the the ChatGPT, like where it currently is with the Smart Connect. Connect app, my usage has tailed off there as well. And then with the Smart Connections view in Obsidian to show you similar notes, it can be so much better. So the reason why the suggestions are not so much better, they've basically been the same, with the exception of bugs making the suggestions worse at times. But like, as far as the underlying algorithms go, nothing really has changed there. But I see so much opportunity to improve just that Smart Connections view itself from being able to add feedback into the Smart Connections view, so that even if you look at the same note at a future time, the suggestions would be better, and then that bleeds over into the chat being more useful.

##### Matthew Oatts
Yeah, I wonder too, based upon what you're describing, and I know we can probably hop to the other part of the topic here, but the part of the effect, I think we were. So, because I played video games, but it's not just a video game thing in the last decade, the hijacking of what it really means to be in alpha, in early release, in like, being a part of a thing that you get early access to something, and then the sort of mutual and understanding and agreement that by definition that means a thing that's different than if it was software that you're paying for that's stable. I think that's gotten so watered down and dissolved that we just were desensitized to it. And so, like, part of the, like, the only reason I'm, you know, continuing to, I can't remember, I think I did the yearly plan, I was always confused as to whether or not there's a yearly plan or whatever. But, like, part of the reason I very quickly learned I'm actually not giving you, you know, a few hundred bucks a year for an app. I'm actually giving it into a mission. And I think that transaction is probably nothing deeply understood. And that's not a you thing, that's just the pragmatic reality of how you get something. That's innovation, that's from a small company without a lot of overhead, like a small entity without a lot of overhead. Like, that's just part of it. And I think part of the struggle is just to grapple with that, that reality, because I could also probably spend the equivalent or same amount of money to a corporation that is going to have 40% to 60% of the same things that maybe I would intend to do right now, maybe a little bit more with Smart Connections, but it's not going to check other boxes. Like, I'm not going to be able to own the files. And, like, the root of the data, and someone else is going to use my data. So I think it's just individual users. We as a community also just have to grapple with, like, what we're spending our money on. And there's no, like, universal right answer for people there, too. Like, it is completely understandable if people, you know, thought they were going to be getting a stable thing, even though they probably are looking past the fact that they're not necessarily getting a stable thing. And then, you know, I believe you would probably encourage people to say, like, hey, if that, you know, if that's too much money for you to spend now that you realize, like, don't, don't give me your money. I don't want to go into that agreement with you is sort of what I'm picking up on from you as well, is like, you want people to have what they need and that's okay. Like, you don't need. You would probably rather not have someone's money to have them have a false expectation of what they're actually getting in exchange.

##### 🌴 Brian
That's 100% accurate. You know, like, I'm, I'm really, even though, you know, it was in the terms of the transaction not being a well understood type of transaction in general, I'm glad that you really picked up on what I was trying to go for. I really do position everything as you're supporting the project, even the subscription, which is more of a productization of the Smart Connect app for access via chat, GPT, even that. I spent a lot of time making sure that I position the offer such that it's an offer to support the ongoing work on the project rather than purchasing this product. And, you know, I really have no hesitation if somebody comes to me and they say, you know what, I didn't, you know, like, I didn't know what I was getting into. Can I get a refund? Like, I will give you a refund, no questions asked, and you can keep the license key, you know, for as long as it's active for, you know, they do expire eventually, you know, but the purpose there, like, to, you know, like, for this positioning was so that, yes, I can fund the continued work, but also without bringing in unnecessary headaches, you know, because if it was too strictly a product, there are, you know, like, well, it's not very understood, this, like, support type of transaction. What is very well understood is that if you buy a product, you're going to get support. You're going to have expectations that the thing's going to work all the time. And I really wanted to avoid that expectation as much as possible. You know, not that everybody's going to understand everything immediately, but, you know, as far as getting into the second part of these two topics that were in there, I think we really did. Hit both already.

##### Matthew Oatts
You know, like, I think so.

##### 🌴 Brian
You know that the growth plans, I mean, I've got a lot of cool ideas that I'm working on, you know, like as far as innovating and improving the software, and that that's where I really believe the growth is going to come from. You know what I, you know, like, while I could put this extra time into the marketing, I think that the real growth will happen when the innovation happens, such that when you look at the alternatives, it's no longer that they check 40% to 60% of the box, is that when you look at the alternatives, they don't check that one box that matters most. And that, I think, comes from that innovation. And I think that's where the real growth happens.

##### Stefano Coppo
Brian, I have. That's excellent. It gives me a strong understanding. And I like the way you visualized kind of stability, innovation, tension, the natural tension that exists between those two goals. And I like the way things are going. One thing that has slowed me down maybe, is, for instance, you're building for multiple platforms, and I think you're using a framework that lets you code once distribute on Mac and Windows platforms. So in the case of Smart Connect, for instance, it's a forced update. And my feeling was that you did that so that you got everybody up on the same code stream, and that's going to probably reduce the support that you need to provide. You don't have three versions of Smart Connect out there across two different platforms with minimal resources trying to support that. But sometimes that forced update puts me in a position where what was working isn't working any longer, or there wasn't adequate documentation, and I didn't understand that. Action groups is now where you go to, you know, fiddle with custom GPT settings, that sort of thing. In the case of the plugin, you've allowed a contributor to go into an advanced version with a cautionary note that it might be less stable, but you're going to get a first glimpse. At some innovation that I'm providing and if it doesn't work for you, there's a revert back to a known more stable version. So I don't have an ultimate answer to that, but so I understand your thinking and your motivation to do what you've done with Smart Connect. So I'm tolerant of that. But I'm wondering if and also when I stuck my hand up and said, hey, I'll write some documentation, and then realized, man, I can't keep up with the pace, what version of the product am I going to be writing documentation for? Which 01:00 a.m. i going to be screenshotting which 01:00 a.m. i going to develop a video for. So I kind of quickly jumped in the back of the line at that point and said, wow, I can't keep track of that. So some of that organic marketing could happen maybe if we did have a body of documentation that was for a known stable release. And here we have this more innovative, cutting edge set of releases and you kind of use at your own risk, adopt as needed, and if it doesn't work for you, you can revert back. I don't know if that makes sense. That was a ramble.

##### 🌴 Brian
No, I think it makes a lot of sense. So I actually, I just want to make it a note for myself. You know, basically I think what you're sort of asking is, you know, can there be a early release and stable release for the Smart Connect app similar to the plugin?

##### Matthew Oatts
That was, that's what I heard.

##### Stefano Coppo
I have those thoughts on occasion, yeah.

##### 🌴 Brian
Okay, so I'm just making a quick note to myself here. Allow stabilise for SC app. So I've had some thoughts about how that would work for the Smart Connect app. I think up until fairly recently it would have been more difficult because, you know, like everything you said was true. There was one part that you missed, which is there's a server component with the Smart Connect app. So one of the reasons I needed to make sure that the latest update was always forced was because if I made any changes to the server, the prior version may no longer be compatible. However, the server has been very stable. I pretty much it. Like, I've made sure that like pretty much all the logic happens in the application rather than the server. The server is about as bare bones as it can get. So I think that having a stable and early release for the, for the Smart Connect app is definitely doable. I don't want to give any sort of ETA for that, but my thought on how it would work would be something like, I would still potentially force an update on the stable release, but only if necessary. And then, so what it would look like is there would be some sort of like update now button that pops up for getting to the latest release unless there's some sort of breaking compatibility issue and I need to force it. And I think that there's, we're definitely approaching a point with that software where implementing that makes a lot of sense. So I appreciate you bringing that up because that'll make sure I add a little extra priority to that. Is there, is there anything I missed? Like with regards to, you know, like what would make sense for, for this? For you?

##### Stefano Coppo
No, I think my omission of the server component and then I, I don't use the plugin Smart Chat that much. My vision was I could use custom GPTs to interface through the Smart Connect proxy to my vault of notes. And that's kind of where I gravitated towards using this. Then it gave me a couple control points. It gave me OpenAI's custom GPT controls to, to upload additional files, write custom instructions. It also gave me the Obsidian alignment notes and what I can do there. So I felt I had this Obsidian and custom GPT configurability around my raspberry PI second brain or my old guy health vault that I wanted to have. So that's where I went with it. I seldom do I use the Smart Chat inside of Obsidian.

##### 🌴 Brian
Yeah, good to know about that. I think that the Smart Chat will actually pick up an adoption. Right now I'm working on a major, essentially a refactor of those components, which really just brings them up to speed with the other components. One of the outcomes of that will be actually bringing the actions that are available in ChatGPT, bringing that into the Smart Chat. And so one of the reasons why I think that'll be very interesting to a lot of people is right now those actions are limited to use in ChatGPT, which personally I like, because I don't have to worry about token usage. So there's no surprise API bills. And up until this zero one preview model, which seems to be incompatible, you know, with the custom GPTs, up until then, you know, you're always able to use the latest models, you know, with these actions. But the point about getting the chats in the Smart Chat is that's going to open up all of the other platforms. So whether you want to try anthropic or any of the other chat model providers out there, having the Smart Chat integrate with the Smart Actions, I think will allow, you know, people to, you know, that don't want to use OpenAI for whatever reason, you know, to use whatever their preferred provider is, including self hosted models.

##### Stefano Coppo
Yes. Yeah, good. Yeah, I would, yeah.

##### 🌴 Brian
You're interested in the self hosted models?

##### Stefano Coppo
Yeah, I have several of those, and one of my former colleagues I'm introducing to that, and we're going to train a model self hosted for their business needs. And so we're coming up to speed on that. But that I would use that then if I had the actions, the Smart Actions in Obsidian and was able to save money and on my own self hosted models, I probably would use, I would stay in Obsidian more.

##### 🌴 Brian
Yeah, yeah, that makes sense. And I also think it's surprising to me that, like anthropic and Google haven't come out with something similar to custom GPTs yet. I really, that's one of the reasons why this Smart Chat update hasn't happened sooner, is because I sort of imagined if Google's Gemini and anthropics Claude had a layer that was equivalent to the custom GPTs, that it would just make a lot more sense for people to pick their preferred provider and that would sort of pigeonhole. The Smart Chat into local models only, which is there's a huge demand for the local model integration. But while I think it's a very vocal demand, I don't think it's, I don't think it's representative of the broader market. I think the broader market mostly just wants to use the platforms that are accessible via the cloud. But I definitely see that that local model integration is very valuable because there is a market for it where they don't have, there's not too much user friendly software in the self hosted LLM space. It's all fairly technical and I think Smart Connect can make it much easier to use those with the Smart Chat integrated into Smart Connect.

##### Stefano Coppo
Yeah, I agree. You have to have some infrastructure to self host a model. So I agree.

##### Matthew Oatts
I had a question for you. We were talking about the Smart Actions and it sounds like that's going to be a cool thing. I'm completely frank with you. Don't know the value prop or like a good usage example of Smart Actions and I just like cranked open my Smart Connect itself and it's not self as evident to me. Like could we have like a brief sort of description? I can even show my smart app thing, I think, if I need to.

##### 🌴 Brian
Like yeah, I think that's. I'm very happy you brought up that question. So Smart Actions. Smart Actions, right now they are very limited to just what I call crud operations, which is create, read, update, or destroy or delete your notes. So, you know, the actions are very much geared to being able to pull in the notes as context and then with the more recent updates, making editing those notes also possible, which there are definitely some issues in the pipeline that I'm aware of with the editing, but those should be cleaned up in some future releases. But the overall. So while the Smart Actions are currently limited to just interacting with notes in markdown format, one of the objectives of the backend architecture that I've been working on is to abstract the markdown pieces of the logic logic and, and have them confined to a like a clear, like this is, this is where the markdown logic. Happens so that we can then add additional file types, and the first one of those is going to be PDF. Unfortunately, we won't be able to edit PDF's, but having that readability, I think is going to add a lot of value for a lot of people. But it doesn't stop at just file types. So the way I look at how the markdown is imported or the PDF's would be brought into the system, I look at those files as external sources, and there's virtually unlimited external sources that can be integrated into the platform. So something that I've been, I've been trying to get everything cleaned up with everything that's public, but something I really want to work on that's a personal prototype that will eventually be public, is where the file system integration is right now, adjacent to the file system integration, a browser integration. What that would look like is you have this browser Smart Action where you say, okay, I want to create a Smart Action for my Twitter timeline. So you put in the link to your Twitter page and it will open up the Twitter page, be able to pull in your content from Twitter. And in addition, because of the way it works, would be a browser integration. And that has a lot to do with the underlying framework that Smart Connect uses. So the reason why Smart Connect works on all the different platforms is because at the core it's essentially a chrome browser. So since we already have that core chrome browser, when you put in your Twitter link, even though they want you to sign in, when you do sign in, all of that authentication just persists in the browser, as it would if you were using any other chrome browser. That really makes the whole authenticating with virtually any website. It makes it the same as if you were just logging in via your normal browser. Interesting. Which that removes a lot of complexity from the development standpoint because, you know, being like, let's say you were building an automation and you wanted to scrape Twitter.

##### Matthew Oatts
Well, yeah, I was about to say, you're talking, it feels like almost like RPA like kind of stuff like screen scraping type thing. Things, but it's not that.

##### 🌴 Brian
So it's actually not like it's not screen scraping, because with the browser we would actually have access to the exact HTML. And I imagine the workflow could be fairly simple to build these custom browser actions for a non code, like somebody that doesn't program themselves. So it would be like this no code paradigm because you put in that URL, and I briefly mentioned this before, but there are going to be community action. So there might be a Twitter browser action that already has a lot of this setup, but just for the sake of discussion, imagine that there's just a generic browser action. You put in the Twitter link, you log in and then you have ChatGPT say okay, now get the link. ChatGPT gets all of the HTML from that page. What you can do from there is have the ChatGPT come up with what they call selectors. And this may be like a CSS selector, it could be Xpath, anything that is compatible with JavaScript. And then by simply discussing with ChatGPT based on the HTML that was returned by the action, the ChatGPT can come up with like hey, here are these selectors, we can name them as such so that when you call this action in the future, instead of returning all of the HTML, the action will just return the content at these selectors. So maybe you say, I just wanted to return my most recent tweet. So then when you call this action, it returns your most recent tweet, or maybe you wanted to return all the tweets. I think that development right there, just with that browser component, I think that there's going to be a whole lot possible from that point. So what I was just mentioning would be the read type action.

##### 🌴 Brian
But then there's also input, you know, like I also want to be able to say schedule a tweet. I think that the same workflow should be possible to say okay, now I need you to click the create tweet button. I need you to come up with the selector to click the, you know, schedule the tweet button. And then, you know, from, from the point of just having this generic browser action, adding a URL and then talking to ChatGPT, I think you could have both data come into the system which can be saved, similar to how notes are saved. So, you know, The tweets can be surfaced even in the Smart Connections pane, but in addition, have actions to be able to say, okay, now that we know what my last tweet was, now let's schedule a new tweet. And Twitter really just represents any website out there that you may want to retrieve data from and interact with.

##### Matthew Oatts
And what's interesting is one of the things you're describing, are you familiar with RPA, like the space around RPA?

##### 🌴 Brian
Very much so, yeah.

##### Matthew Oatts
Okay, cool. And it has been probably seven years since I messed around with RPA, but my background was in like, business process automation with IBM. But what you're describing is what sort of. I remember when I had to do, like, the only I got certified on was, like, uipath. But that idea of like, programmatically navigating the Dom of a page and then building in things and adding, you know, different, sort of like the idea of there's literally no application that you couldn't technically integrate with at varying levels of interfaces. You know, this, this was relevant, and sounds like it still remains relevant when you don't actually have API integrations. How do you layer in something that you actually need to have an ape, you need to have an API for on a platform that architecturally isn't even designed to be able to have an API? And so sort of what you're talking about has a lot of like, it feels a lot of like sort of similar domains is what RPA solutions have been trying to sort of work on. And I'm sure they're all brand. I haven't looked at this industry in years, but I'm sure they're all branded as AI enabled now, attempting to do what you're talking about.

##### 🌴 Brian
Yeah, I think one of the key differences is that from what I remember, a lot of what you'd be building in something like UiPath is the workflow. So you have this flowchart from going from start to finish. What Smart Actions provide are each of the nodes in that workflow. And then as far as getting to them in the correct order, we're actually able to rely on ChatGPT for coming up with that order. I think that there's ways that we can force flows or workflows in the future, but I think just having the ability to create those nodes and then let the AI access those nodes in whatever order might be best for the current task, I think that's hugely valuable.

##### Matthew Oatts
Yeah. And that reminds me of, that's getting closer to this idea of like, Digital selves and the fact that, like, oh, you know, you have an agent. Well, you got your matthews, you know, researcher agent who needs to, every single morning, wake up and look at these feeds and if needed, have another hit on four other feeds that might be relevant, and then summarize it this way. And then, oh, you know, oh, this month, the Harvard Business Review article came out. So go to Harvard Business Review, actually understand, and read these things to figure out what's relevant and still an ethically responsible way to then compile that for Matthew so that when he gets in his office at 830 in the morning on February 4, 2025, he's essentially got an agent that has done all of these things that he didn't have to pay RPA developer to go program a workflow. I think that's sort of the future you're talking about there 100%.

##### 🌴 Brian
And I think that just for a little glimpse of what I see is coming is something. And this is something I started actually working on, on a separate project that fizzled out. But I think the idea is still there. And that is a smart inbox. So by having these actions, it'd be somewhat trivial to just say, now that you have that ability to get the content from Twitter, just say now. Check it every hour or something. As long as the application's running, it can check at whatever cadence you want it to check and then pull content into the system. So then, very similar to how you have the Smart Connections pane that shows you similar content, we create a new game that is designed to prioritize based on what you know, what's out there and what's most relevant to you at this exact moment. And that, I think, is probably the culmination of all of the architecture changes that I've been working on. It's to provide a feature like that.

##### Stefano Coppo
Yeah, Brian, that makes sense. That is brilliant. And the last point on messaging coming from my background, you know, knowledge gets locked into.

##### 🌴 Brian
Stefano, I think we lost you folder.

##### Matthew Oatts
Oh, am I there? Maybe he's back.

##### 🌴 Brian
Yeah, you're back.

##### Stefano Coppo
Yeah. I think that last point of the mailbox, access the browser. I think that's brilliant. So Smart Connects based on a chromium browser. It solves the problem of authentication against all these locks. Subscribe sites like Medium.com where I have a bunch of articles that I've bookmarked and put in my library. I have all these emails in certain folders that get forgotten and siloed away. And now I could, and a lot of the legacy products are kind of a pre designed workflow. It's linear. First you go here, then you go here, follow up with this, stop in the workflow and then I want to schedule it. And it's very manual, but if I could just let chat, GPT or some AI model, help me decide or just give it an instruction, you know, check this folder or check my medium, and I start gathering all these knowledge tidbits from different sources, aggregating them into my second brain, and then decide what I want to do with it.

##### Matthew Oatts
Yeah, I know we're a little bit over time here, but what's interesting, I had a conversation I probably washington ten years ago when I stumbled upon the idea of something that's been going on for, you know, hundreds if not thousands of years. But I was like, wait, there's a job role called a chief of staff. Like, I heard of like chief of staff and like politics. But like I was, I encountered this ten years ago. Like corporations have chief of staff. And I talked to somebody who had a chief of staff. He's like, for, you know, hundreds, probably thousands of years as you move up the scale of efficiency, but also responsibility and authority and power, like it's been figured out that you need to have, you know, the term, like right hand man, right hand woman. Like you need to have people that you can delegate to and follow alongside you just because the sheer scale and stakes are that much higher as from an organization or a systems perspective, you go up the top and I think what you're trying to do is almost like democratize or flatten the idea of having digital chiefs of staff. That yes, there's the digital self, digital brain, but the world is getting so complex that we're all sort of humans propped up against something that's getting even more and more and more and more complex, that it's a proven pattern for a thousand years that people with great responsibility or great power probably have people alongside them that are helping them do the thing. That's what I'm picking up on, sort of like with your vision.

##### 🌴 Brian
That's cool. That's a very, very interesting way to put it. I like it. It reminds me, I'm pretty sure it was. Like Charlie Munger, you know, you know, somebody that, you know, writes, you know, they say, like, you, you know, somebody in a higher position just needs somebody to also just, like, filter out all the bullshit from people, you know? So.

##### 🌴 Brian
And I imagine that could be like the, you know, smart inbox. And in that same vein, also, how the inbox could actually help fight the misinformation problem, because the misinformation problem is not that this, you know, misinformation just exists. The problem is, is that it's in front of you and taking your attention. But, you know, it's. It's very possible that if you just have the things that are most important to you right up front, then the misinformation just doesn't even make it into your, you know, into your mind space. And then, you know, that really just reduces that effect.

##### Matthew Oatts
Yeah, I can't help it. I know we're over time here, but I want to show you, and I do call, but I have to show you this because what you just described hits on something. I was consulting with a client earlier. Let's see, I can find this earlier this week. I don't know if you're familiar with. Let me get rid of this here. Oh, the scale is messed up here. I don't know if you're familiar with Stephen Covey's seven habits of highly effective people, but he talks about, he has a quadrant around, like, the important, not important and urgent matrix. The idea that we sort of have to do some of the stuff over here, quadrant four is stuff you just essentially always want to avoid. And the best way to keep getting more and more effective is try to shift stuff out of, like, kill stuff in three and use that time in two. So the idea of actually using time on important, not urgent things. And so a way to look at it from, like, return on your time is you get more return on your time working in quadrant two, this top right thing. And, you know, I use this frame a ton, just talk about sort of the different patterns of how that effect works. But I added it to our little Smart Connections thing here. Yeah, thanks for that. Yeah. But I. Cause I think that's what you're trying to do is like, you're trying to have essentially an agent that can handle some of this quadrant three stuff and, you know, so that you can free up time to actually do more, like higher order thinking, important, not urgent work, which is kind of neat.

##### 🌴 Brian
So. Yeah, I think definitely, yeah. I mean, I could talk all day about this, but I know we're already over time. I appreciate you guys, you know, spending the extra time and, you know, for contributing. It makes a big difference, so. And. And thanks again, Matthew, for organizing these.

##### Matthew Oatts
Yeah, my pleasure. This is. This was great. I just realized I forgot to actually. Capture the full recording, which is not that big a deal because the grain thing is here, too. So because we had no unsavory interruptions, I will very quickly be able to just post the chat clips from this one. I'm probably just going to ignore last week's and then make sure I prioritize getting this one out sooner rather than later. So that, because I know you want to share some of this stuff out, too. So I'll get that stuff done today in a day and I'll post it in the lean coffee channel.

##### 🌴 Brian
That's awesome.

##### Stefano Coppo
Brian and Matthew, thank you both. One burning question for our viewers, though. I know Brian is with the ceiling fan, the colorful shirt, you know, the coconut trees you have in your icons. I'm trying to pinpoint your location.

##### Matthew Oatts
Is it, I guess, wrong? Stefano, the first time I did it, I guess wrong.

##### Stefano Coppo
Okay, so I, you know, Hawaii comes to mind. Me being a West coast kid, having visited Florida several times, there's that thought, Caribbean, some island that you own. So I don't know what it is, but, you know, I don't have my ceiling fan on in my house this morning.

##### 🌴 Brian
So, yeah, that ceiling fan is basically on permanently. So is the one in front of me. And that's because here in St. Petersburg, Florida, it is just constantly hot. You know, there's, there's a month out of the year where it's too cold. And then for the rest of the year, I walk outside and I have a good habit of just quick rinsing off in the shower because it's the only way to, you know, survive. You need to rinse off all that sweat that you're undoubtedly going to pull. But, yeah, St. Petersburg, Florida, I can't say enough good things about it. It's, I never lived somewhere that I loved as much as St. Petersburg. You know, it's, it's great here. And I think a lot of people are discovering it. The, the prices are going crazy. I live in this little condo right on the water. You know, I'll just, I'll do a quick, I don't know if you can see out my window there, but there's like a bunch of boats out there, I guess because we're ahead. I have this, I guess, I don't know. I don't want to mess around and waste more time by unblurring. But I've got a canal there with dolphins that come by. I basically do all of my thinking out by the bay, Tampa Bay. It's just beautiful. I'm out there at sunrise I'm out there at sunset walking around for my stack of note cards, just thinking about these things. I come in here, get them dumped into my Obsidian, and start working my way through figuring out what's next. And honestly, the reason why I'm just going on about this is because I think to myself sometimes I'm like, who the hell are you to think that? Can do what you're doing. And then I think to myself, who better to try to empower individuals with these tools than somebody who just is like, you know, also an individual trying to empower themselves and somebody who's been fortunate enough to live in a place where they just love doing it.

##### 🌴 Brian
And that's all I have to say about it, about location.

##### Stefano Coppo
Well, we're great.

##### Matthew Oatts
We're grateful. We are grateful, for sure.

##### 🌴 Brian
I appreciate it. Well, I'm grateful for you guys.

##### Matthew Oatts
All right. See everybody later.

##### Stefano Coppo
Have a great weekend. Be well. 😊🌴