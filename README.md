# Talk Prep

## Preparing a Tech Talk

There are countless ways to prepare a good tech talk. 

One particularly popular approach is to procrastinate, board a plane to your conference without a deck, and crank your deck out in a caffeine-induced rampage at the hotel. 

One incredibly reasonable alternative is to only apply to speak at a conference after you already have a full-fledged presentation ready and waiting. In theory, this approach likely decreases stress and preserves sanity. However, that's all theoretical because, as far as I know, no one has ever tried it. 

This guide is for the people that fall in between -- neither the black swan of preparation nor the majority of speakers that end up giving talks in a state of sheer panic and exhaustion. In particular, if you are giving your first tech talk or helping someone else give their, this guide will hopefully add some structure to the process. (Disclaimer: lack of panic and exhaustion not guaranteed even if you follow these steps.)

Generally, I try to approach talk preparation in 5 main steps:

1. Decide your call to action
2. Shape the story
3. Test the talk
4. Create the slides
5. Practice
6. Bonus: Don't Overthink

### Step 0: Find a conference, find a topic, and apply!

Naturally, a prerequisite to giving a tech talk is to find a conference and write a proposal to speak on a certain topic. That's an interesting topic in and of itself but out of the scope of this post. You can find many good resources for thinking of talk ideas and writing abstracts online.

From here on, we will assume you've been accepted to speak at a conference -- congratulations!

### Step 1: Decide the call to action

It's shockingly easy to write a compelling abstract without fully understanding your own story. (It's unfortunately easy to *give* a conference talk without ever understanding this.) Naturally, the first step is to figure out what your "call to action" should be. 

Don't think you have a call to action? Every talk does! By "action", I don't mean you have to be asking your audience to *do* anything. But inherently, you are trying to get them to *think* about something differently, *wonder* about something, or want to *try* something. As a speaker, you are asking for their attention, and we all know that the value of attention is at an all-time high. What is it you want to do with this valuable resource?

Remember that your audience will be listening to a *lot* of presentations over the course of the conference. Whether you give a 5 minute tech talk or an hour long keynote, imagine your goal to be making one single impression so compelling that they can still recall it when they wake up the next morning. Anything else is details that they can get by referring to your slides, searching online, or reaching out to you the presenter.

Here are some possible calls to action for common types of R talks:

- **package demo**: you should consider using package x to solve problems like y
- **tutorial**: this is how you can use package x to solve problem y like y
- **case study** *(e.g. "how my company uses R")*: when teaching a / organizing b / hiring c / facing barrier d / etc., try tips x, y, and z
- **data analysis**: you should consider using method x to solve problems like y *OR* when thinking about problem z, you should bear in mind the interesting insight q that I found

This is not to say you cannot make more than one point. I've heard many successful talks along the lines of "five things to consider when designing an A/B test" or "three common mistakes when building random forests". Your aim is still to encourage your audience to think about a problem differently whenever they next encounter it.  

### Step 2: Shape the story

Once you know the main point you want to make, your temptation may be to start working on your slides. Please don't. This temptation may be exacerbated by conference organizers asking for your slides ahead. Why not make the slides first and then you can always figure out what you want to say later, right? Please don't. 

I say this piece rather passionately from personal experience. Slide making is one of the stickiest time investments in writing your presentation. Making slides too soon can result in many bad outcomes. If you decide to change the story later on, you might have to scrap hours of hard work on beautiful slides. Even worse, having slides may lock in your thinking so you resist change even as a better idea emerges.

Instead of jumping straight into deck making, it is easier to plan a talk and seek feedback by first making a minimum viable product outline. Move from your call-to-action into a story by thinking of your talk piece-by-piece. I first tend to write "topic sentences" (thanks, SAT essay writing!) for each subpoint I want to make to tell my story. You should be able to read through these clearly and they alone should tell a logical story which ultimately emphasizes your call to action. 

After that, fill in sub-points or ideas you want to expand on to support each claim. As a general rule of thumb, I like to try to make no more than two or three supporting points for each topic sentence, but you mileage may vary. This depends quite a lot on the type of talk you're giving.

For example, here's the beginning of an outline I wrote a few months ago about analytical communities of practice. Not everything below was kept in the final presentation. Some of its redundant, some of its tacky, some of it I'd be embarrassed to stand up and say in front of an audience, but regardless it was a way for me to organize my ideas:

```
# What do we mean when we talk about community?

We have the raw ingredients of a thriving community: a lot of people working to solve similar problems with a common set of constraints (e.g. governance) and opportunities

However, we often don't act like a community and solve problems in silos

Too often, we are missing the catalyst that brings a community to life

# High-functioning communities drive outsized values 

The whole is greater than the sum of the parts

On the technical side, open source software is a clear example, with phenomenal tools and resources like R and python coming from open-source

Alternatively / more rudimentary: looks at ants and bee communities; each work modularly and autonomously but ultimately create a whole greater than the sum of the parts

# High-functioning community overcome barriers

Specifically, {{Project Q}} is posing countless challenges as analysts are having to quickly learn new tools and systems just to do their BAU work.

We also have finite FTE devoted to solving these problems

While we are here to help and doing as much as we can, we can also be more successful if we help each other

Examples:
- {{Team X}} has more better infrastructure rating and is sharing methods / practices
- {{Team Y}} will have advanced SME on {{System Z}} before {{Team X}}'s migration 

# Our team seeks to deploy technology-driven solutions to solve human problems

We want to make it easier to share:
- Methods 
- Code
- Problem-Solving

We are doing this with:
- Packages (+ contribution; methodologies & implementation on package websites)
- Training / consulting (office hours)
- Proactive knowledge capture (GitHub, Slack)

# Rich communities require engagement

The richness of communities comes from user engagement and community ownership. 
This can mean many different things and require a range of levels of effort and investment. 
We want to take some time today to thank some early engagers who exemplify how to get involved.
```

### Step 3: Test the talk

You have a minimum-viable product talk, and what do we do with MVPs? You test them!

Practice talking through your story at this stage. Assess (alone or with a practice audience member) if its *functional*. At minimum, it should be:

- **roughly right length**: does your talk take up roughly the right amount of time? If anything, err on the short side. It's much worse etiquette to run over (and risk taking up another speaker's time) than under, and this leaves time for questions
- **motivated by your call to action**: does the story consistency emphasize your key point? No matter how interesting some of your tangents may feel, don't risk confusing your audience. Ruthlessly cut out things that aren't relevant
- **coherent**: do the different pieces of your story fit together?
- **comfortable**: do you feel good talking through it? Does it feel natural?

Iterate until you feel you have a good outline that meets all of the above criteria. As you practices at this stage, you'll probably find yourself adjusting many of the subpoints. Ideally, as you get additional reps here, you can begin to incorporate more personal voice into your presentation. In subsequent iterations, consider whether your presentation:

- **is interesting**: are you stating a series of facts or telling a story?
- **has voice**: do you sound like you're talking to a friend (ideally) or giving a closing argument in a trial?
- **feels authentic**: do you feel like you're playing a role or acting like yourself? You'll have enough on your mind when presenting without learning how to act.

### Step 4: Create your slides

Now, finally, move towards creating your slides. There are many great books and resources already and creating impactful presentations, and I don't pretend to have better (or as good of) advice as any of these. However, there are a few specific things I'll call out about tech talks. 

Some things to consider at this stage:

- **let your story determine the number of slides you need**: personally, I hate guidelines on "try to get through x slides per minute". With some tech talks, you could easily spend a great deal of time walking through a single flowchart or example piece of code; other times you might simply want to flash up a bullet list, an impactful image, or a quote. I find it easiest to let my topic sentences guide when I should create a new slide instead of making arbitrary rules for myself.
- **paint a picture; don't write a novel**: in academic or professional settings, you may have created report-like presentations which can be read and comprehended in your absence. However, for tech talks don't feel like you have to cram your whole story onto your slides. Slides are more of an illustration that help you speak to your points or provide concrete examples of concepts you're discussion.
- **put branding at the beginning**: don't feel embarrassed with a little shameless self-promotion! Add social media handles (especially Twitter) to your title slide so conference members can opt to follow your are tweet about your talk. If you handle is hard to spell or remember, you can even consider putting them as footers on all of the slides. 
- **convey your key point(s)**: returning to the ideas of a "call to action" and to the potential for your slides to end up on social media, remember that clean, simple, and visually interesting slides can help emphasize a key point and potentially disseminate it to a wider audience.
- **don't fall in love with your slides:** similar to jokes and ideas, you may make some truly beautiful, awesome, epic slides that absolutely do *not* belong in your story. It's hard but resist the urge to keep things because they look cool or because you worked hard on them

### Step 5: Practice

Practice, practice, practice! Different people clearly prefer different amounts of practice, so if you feel confident in your story, don't practice until you are sick of hearing yourself talk and sick of thinking about your topic. That serves no one. But do practice until you feel like the story flows, like you know your transitions, and like you aren't distracted while talking by wondering what's coming next. 

It may feel weird, but it's probably courteous to practice your first few iterations by yourself. On these reps, you will still be figuring out how you want to tell the story, so an audience won't be able to give you much constructive feedback. It's not the best use of their time and may just make you feel more stressed. 

In these early rounds, you might also consider recording yourself so you can play it back. This can help you perfect your phrasing and also notice things you don't like in your tone, phrasing, etc. Some jokes may not sound as funny listening to them as they feel when saying them; sometimes things feel more fun to say than they are to hear.

After a few of these practice rounds, practice in front of an audience. Everything will feel different. You might get self-conscious or start talking fast. Get your listener's candid, honest feedback. Some of the best feedback I ever got was that I needed to stop "presenting" and just start talking as I would to another person. This made my presentation tons easier to give and far more palatable to listen to. 

Practice until you feel confident you know your story. Or until you're bored or tired or other things come up in your life. You've got this thing. 

### Step 6: Don't Overthink!

I cannot emphasize enough the extent to which all of these steps are in no way necessary to give a successful talk. Everyone has their own process, so don't let any of this advice add makework to your process. Also don't stress out. Conference talks are not theatre; they are, at best, a genuine coming together of people eager to share ideas. The fact that you applied to speak because you have a story you want to tell means you're already a long way there. My intent is only to give process and structure to anyone looking for some traction and a good way to get started. 


