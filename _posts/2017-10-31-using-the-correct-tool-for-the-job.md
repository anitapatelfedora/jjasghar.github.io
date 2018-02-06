---
layout: post
title: "Using the Correct Tool for the Job"
date: 2017-10-31 15:22:37
categories: sysadmin essay opinion
---

>You wouldn't use a saw when you needed a hammer, or a hammer when you needed a saw right? - Thomas Cate

The above is a quote from a great friend of mine who, rattled this statement off, in a way that he has said it a million times, when I was discussing writing on this topic. It really hits home if you think about it; working on some construction project, you find yourself needing to hammer in a nail, you wouldn't go grab your saw and start whacking the long side at it right? On the other hand, if you needed to cut a 2 by 4 in half you wouldn't grab your hammer and start smashing it hoping it'll break where you need the cut to be? The mental image of this is so ludicrous it brings a smile to my face, but this highlights the problem that people say when they don't want to learn or train their team on _another_ tool.

## Past

There is this misconception floating around our industry that won't seem to be left for the history books. We've fought it in the past, it comes back every couple years or so, almost consistently with new recruits out of University. I'm convinced that every new cycle of engineers are taught, that there was a time whereas a Systems Administrator all you needed to do your job was a terminal, command prompt and a scripting language like Perl. Somehow this was ingrained into our culture and industry and became a concept of "one tool to do everything I need." I seem to see the focus of teaching at coding in Universities not exploring new languages then Java as a framework to teach computer science. Java as a teaching tool makes a lot of sense to a budding engineer, but to focus on "one tool to do everything," this can reinforce this stereotype. Then you take it one step farther, looking at companies outside of University adopting Java and creating application stacks this way causes this vicious cycle never exploring newer tools.

But I digress, over time, these Perl wizards, and yes, let's admit it they _are_ wizards, either moved on or got promoted and the Systems Administrators were forced to solve the same problems but with newer tools, like Python, or VBScript. I highlight Python and VBScript here because at least as I became a Systems Administrator, there was a clear line where the "new Linux blood" was picking Python, while the "new Windows blood" was picking VBScript. It almost seemed as these became the "one tool" to do everything in, and it was so ubiquitous that even [xkcd](https://xkcd.com/353/) had a comic about it at one point. Even with this change of the main tooling, there was still was this consistency of "one tool to do the job." There was this colloquialism and accepted truth that a budding Administrator could read one massive O'Reilly book and know everything they needed to be confident in their job.  I remember going to an interview with the [large Perl book](https://www.amazon.com/Programming-Perl-Unmatched-processing-scripting/dp/0596004923) all 1176 pages in my backpack and pulling it out to reference something. I’m convinced that it was one of the things that impressed the interviewers because I got the job offer later that day.

## Present

It's safe to say this is no longer the case. With Digital Transformation and the DevOps movement, it's required to learn multiple tools to do your work. System Administrators have become modern-day digital tool smiths shaping their workflow and pipelines into what they need to do their required jobs, no longer can you just buy some code off the shelf and drop it into your environment and expect it to work. Our culture and industry practitioners, have moved away from this old core concept of using one tool to do every job, and have a majority embracing find the _best tool_ for the job at hand. This does means as a seasoned practitioner need to learn more tooling and experiment, and this is a good thing. Training your staff on multiple applications and frameworks allows them to learn the newer technologies in our fast moving industry. As a side effect, the ability to experiment with the cutting edge technologies to help fix long-standing inefficiencies with fresh eyes. The ability to use not only something like `bash`, `python`, `ruby`, and `go` will allow for deeper understanding of technology stacks, but allowing for your business to be more stable, agiler, and get features to market quicker.

I've heard stories of companies that audit their tooling. If this is true at your company this doesn't make any sense. Limiting your worker's ability by only having "approved" tools not only will force arbitrary constraints on them, it will cause a slowdown in innovation. The ability to look at a problem from any viewpoint to overcome the problem with the tooling they are most comfortable will bring faster and more consistent success. There does need to be a balance though, you don’t want to start picking up tools because they are they “new-shiny” tools. There should be a level of scrutiny, and standardization, but it shouldn’t be scared to try to find something new.
I understand that there are specific sectors of our economy that can't have the ideal level of flexibility due to Governmental or legal reasons, but this is something that should always be looked at and challenged. With how fast our core industry moves if you don't ask why you can only use `ksh` as your shell, and accept it this will only cause more friction during the next round of changes. Our industry doesn't work in the waterfall "drop new versions twice a year" anymore, every day something can come out and if you don't focus on this you'll find you and your sphere having to deal with much larger compatibility changes instead of incremental safe changes.

There is a debate about extending pre-existing tools in your environment and extending them to do more than they are initially designed to. This has echoes of the Perl days where System Administrators picked a universal tool and molded into what they needed to get done. With how many tools are out there now, this isn't discouraged per se but instead frowned upon. The Open Source movement has birthed Software Engineers and Administrators that are now empowered to scratch the itch they have, and easily find others around the world that have that exact same itch; collaborate with them and create amazing applications. If you create an in-house tool that does something or are thinking about doing that, you are doing yourself a disservice not looking out to the Open Source community as a whole and see if someone has created something that fits that use case. You can use some tools to extend out to do tasks they aren't designed to do, but the risk of learning how to jimmy rig this tool to do that extension is better suited to another tool. Extending a tool to do something requires deep knowledge of that tool, where in most cases taking the beginning tutorial of another tool to do one piece of the process to hand off to another tool is all you need. This goes to the [Unix philosophy](https://en.wikipedia.org/wiki/Unix_philosophy):

> This is the Unix philosophy: Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface. - Doug McIlroy

This quote and paradigm can be unbelievably powerful. I concede that it can be scary to managers and senior level people, the idea that a pipeline or workflow is a Rube Goldberg Machine of tools, but that is the reality way of the DevOps movement. You choose the best tool for the job and you learn what you need to it, and you move on to the next task. Automation and efficiencies are something that comes with experimentation and the ability to learn, not with forcing a round peg into a square hole.