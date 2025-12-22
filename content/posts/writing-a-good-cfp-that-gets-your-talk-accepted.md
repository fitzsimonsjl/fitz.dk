---
title: "Writing a Good CFP That Gets Your Talk Accepted"
date: 2025-12-20
description: "Some thoughts on putting together a good Call for Papers or Call for Proposals conference submission."
tags: [Personal, Conferences]
draft: false
---

## Introduction
This is part one of what will probably become a two or three part series around doing research/giving conference talks. I probably should have started with the whole “how do I get into doing research?” question first, but this one sort of flowed easier, so it is what it is. Cart, meet horse. 

For now, I’ll leave a couple of good blog posts on getting into security research until I find the time (inevitably in about 3 months or so) and come back to write up something more mainframe focused...

[Demystifying Security Research: Part 1 - Alex Plaskett](https://alexplaskett.github.io/demystifying-security-research-part1/)

[Getting into AWS cloud security research as a n00bcake - Daniel Grzelak](https://dagrz.com/writing/aws-security/getting-into-aws-security-research/)

## So you want to write a decent Call for Papers/Proposals...
2025 has been a pretty good year for giving talks and presentations (both internally and and externally), and with a couple more already planned for 2026, I figured its time to look back and reflect on what makes a good Call for Papers (or Proposal - you pick), otherwise known as a CFP.

---

As per usual - all views are my own. I’m only writing here what I feel makes a good CFP based on the talks I’ve given so far. This isn’t meant to be prescriptive in what constitutes best practice. Feel free to take bits and pieces if you feel they’re of use to you.

---

Over the past couple of years (starting at the tail end of 2023), my success rate is 5 out of 7 - or around 71% for getting a talk accepted. Now, I can’t legitimately put that all down to my writing alone. Though I consider myself a decent writer, I’m definitely no Hemingway. It’s also quite possible that as my interests within security are quite niche (mainframes), that it’s something interesting to put in the schedule that doesn’t really get talked about a lot and by default increases my chances somewhat. 

Realistically, if the conference in question is well known and gets a) a lot of attendees and b) has a decent reputation for the quality of speakers, then the chances are that whoever is on the board reviewing what comes in is going to be wading through far more proposals than they know what to do with. 

Regardless, here are a few tips for writing a good CFP that’s more likely to get accepted whilst also helping those reviewing them save time and appreciate your submission.

## Pick an obvious title 
Make it obvious, or reasonably obvious, what your talk is about based on the title. Ideally, keep it short and sweet, and if you can make it somewhat humorous whilst also being on point then go for it. It can never really hurt.

A few I’ve used to get the topic of my talk across:
- Fun Having; Mainframe Hacking - Exploring z/OS
- Bending the Big Iron: An Introduction to Mainframe Hacking

Both of them make it clear that the topic is mainframe related - with one specifically calling out IBM z/OS as the particular mainframe I’ll be talking about.

## Be explicit in the abstract
By explicit, I mean that your abstract should do the following things:
- Pose the question or statement that your talk will answer (whether this is proving or disproving something)
- If it isn't a specific question or statement problem, and you're just talking about cool research you've done or cool tool you've made, then give a high overview of the journey you took
- Let attendees know what they will get out of it so they can decide whether they want to turn up and watch you present

Using an example of a previously submitted CFP:

> ...“Today mainframes are commonly thought of as outdated and legacy technology - with most not realising that although your AD might be the keys to the kingdom within the company, your mainframe is still the crown jewels. They also still underpin a lot more of society than we think, and are an integral part of day-to-day life from card transactions through to airlines and supermarkets.
> 
> This talk will demystify some perceptions and assumptions about mainframes in general, show that they're far from legacy technology, and explore the different ways we can gain access and elevate our privileges on a z/OS system. Along the way you'll learn key z/OS concepts, and how you can get started with mainframe security research.”...

The first paragraph goes into some commonly held assumptions (that I’ve heard more than once), and stresses that these are quite outdated. The second elaborates on what the talk outcomes are, and what people who decide to turn up and listen will learn from it. Two paragraphs that tell you everything you need to know.

## Make use of the fields you need to fill in

... Even if some are optional.

Normally when submitting a CFP, there are some mandatory fields that often at a minimum include:
- Your talk title
- The public abstract 
- Notes for the organisers (not public)
- Possibly some others such as links to previous conference talks
- A place for you to include a link to draft slides - we’ll come back to this one

Although it might seem counterintuitive at first thought - seeing as it’s not going to be published on the conference website, I feel that the “Notes for the organisers” section is probably where you should add the most detail. They are, after all, the people who will be deciding whether your talk makes the cut. 

This is especially true when there are either a few different tracks to pick from in terms of subject matter, or if there are a few different lengths of talk slots (e.g. 20, 40, or 60 minutes). This is where you can make it clear to them that you’re not wasting their time by lobbing a not so well thought out submission over the fence, and lay out what exactly you plan on doing with the time that your slot would give you. 

Use the field to go into detail on what exactly the topic of your talk is, what it’s going to cover, and give an indication if possible of each section with rough timings so that the organisers know you’ve thought about the best way to use the talk slot. 

Lastly, you can also leave things more open ended and mention that this is how you see the talk going, but that you’re open to feedback. If the conference you’re submitting to happens to offer things like practice/dry runs or presentation feedback for chosen presenters whose talk makes the cut, then they’re going to appreciate that you’ve put time in up front and are open to improvements so that your talk is the best it can be.

Using another previously submitted CFP example, here's what went into a "Notes for the organisers" section:

> ...“Mainframes underpin a lot more of society than we think - banks, airlines, supermarkets, day-to-day card transactions etc. Daily life would become much more inconvenient - or come to a halt entirely, without them. Yet many in the security community still know very little about them and/or consider them legacy technology.
> 
> Having started working with mainframes around 2 years ago, I'd like to raise a bit of awareness and share some knowledge of the area.
>
> The focus will be on IBM z/OS as it is the most accessible in comparison to other mainframes from HP, UniSys, and Fujitsu.
>
>This talk will be divided into three main topics:
>
>**A quick z/OS Primer**
>
>- What mainframes are - demystifying some outdated assumptions 
>- Why you should still care about them (especially if your company has one!)
>- Some key concepts
>
>**Hacking a mainframe**
>- The current state of mainframe pentesting/offensive security methods for z/OS, including demo(s)
>
>**Getting involved**
>- Setting up your own "mainframe" for security research purposes
> Some good resources for going further
> A call to action - there's lots of areas still unexplored within mainframe security”

> The aim is to spend 5-10 minutes on the background and key concepts, with the rest of the time dedicated to mainframe pentesting methods along with some demos and then 5 minutes for Q&A at the end.

 By going into more detail like above, you’ll have touched on:
 - Reiterating the statement or question that your talk will answer or prove/disprove
 - Why you’re suited to giving this particular talk (without overdoing it on the tooting your own horn)
 - Why you’ve chosen the specific topic - is it because it’s the most interesting? The most accessible considering the audience? What you can more easily fill 30/40/60 minutes with?
 - How you’re going to break the talk down by section so it’s clear what is being covered 
 - What attendees will learn from your talk (which is one of, if not the main reason why they’ll be wanting to give you a talk slot to begin with)

By doing all these things and adhering to a similar format, you’re making it as easy as possible for the organisers to make a quick decision on whether your talk goes further for final review and improves your chances of getting accepted. If they’ve got any questions, or think another angle might be better suited, you’ve also given them plenty to work with in terms of what they feel would go down best based on events held in previous years.

## Misc advice
This section is for last few things that didn’t really fit anywhere in the above, written in no particular order.

**Picking relevant conferences**

If it’s your first conference talk, a BSides (or generally smaller) conference is always a good shout. They tend to be more generalist and take a wider variety of content. If it’s your first time speaking in public, it also means that the audience at a BSides is (probably) going to be a bit nicer if your talk doesn’t go perfectly. 

When looking at the conference website CFP page, you’ll usually get a solid feel for the type of content that the organisers are looking for. Unless it’s more niche (e.g. fwd:cloudsec, or Blue Team Con), then chances are whatever you’re looking to submit as a talk has a fairly equal chance of getting a yes. 

On another note - location is always one to bear in mind. Though some conferences will fully/partially cover some travel or accommodation costs for you speaking, if it’s a smaller event then there’s every chance that they may not. Just something to consider before you find yourself saying yes to speaking and then having to figure out the cheapest way to somewhere else in Europe (or the US) from wherever you’re based.

**Don't overdo  your speaker bio**

There's definitely going to be a field for you to fill in about yourself that will get published along with your talk abstract. Use it to give a bit of background about yourself - what your focus at work is on, where you're based, a bit about your experience. Even better - include mentions of previous conferences you've presented at (if any). With that said, don't go ham and use it as a spot to exhaustively list every single certification you've got, or give a detailed work history. 

This is going to come across as potentially controversial, but I've - so far, at least - noticed a relatively high correlation between the amount of space used for a speakers bio on the things mentioned above and the actual technical level/polish of their talk not being up to the same standard.

**Preparing some draft slides** 

I’ve been seeing draft slides as a requirement more frequently in recent years, and to be perfectly honest I don’t think it’s a bad thing. Don’t get me wrong, I’m all for Talk Driven Development (TDD), but I also understand where the organisers are coming from. When you get 60 or 80+ submissions that are just vague bullet points that don’t really make a coherent case for why they should get the talk slot of which there are only 10 or 20, it can be a lot of work sorting the wheat from the chaff.

A CFP asking for draft slides doesn’t mean that they expect you to submit a fully polished and finalised slide deck. What they really want to see is that you’ve put some thought into the things that we’ve covered earlier. In the majority of cases, an agenda slide and some chapter slides with a few slides detailing what you’re going to cover in each section is plenty. Don’t let the idea of having to make some slides just to submit put you off!

## Closing thoughts
By putting a bit more effort into your submission at the start (TDD aside - because there’s nothing like a hard deadline to force yourself to get the research finished in time for the talk!), you’ll get a better end result. Bear in mind that the people who come to the conference and are going to see your talk have paid to do so, potentially having travelled a decent distance. The organisers chose your talk to be one of the few available slots - don't do them or the attendees or disservice by not respecting their time and effort by getting up on stage without having polished your talk as much as you reasonably can.

Hopefully this has been somewhat useful in giving you an idea of how to put together a half decent CFP - and I really hope that I see some of your talks at the next lot of conferences I’m going to.

In the next post, I’ll go through some tips on putting together a good slide deck once you’ve got a talk submission accepted.





