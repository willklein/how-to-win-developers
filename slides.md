---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: hello.jpg
# some information about your slides (markdown enabled)
title: Welcome to Slidev
info: |
  ## How to Win Developers and Influence Adoption
  A talk by Will Klein to help developers communicate the value of their work

  Learn more at [howtowin.dev](https://wwww.howtowin.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: none
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# open graph
seoMeta:
  # By default, Slidev will use ./og-image.png if it exists,
  # or generate one from the first slide if not found.
  ogImage: auto
  # ogImage: https://cover.sli.dev
---

---
layout: image
image: hello.jpg
---

<!--
Before we begin, please humor me

when i greet you in a moment, please, everyone, say hello back

Hello!
-->

---
layout: image
image: paper.jpg
---

<br>

# How to Win Developers

# and Influence Adoption

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

# Will Klein

<!--
Today I'd like to share how to win developers and influence adoption.

Whether you maintain a library or develop a application, if you write software,
I'm here to help you reach other developers more effectively.

Writing code is the easy part. Getting other developers interested and engaged is much harder.
-->

---
layout: image
image: lights.jpg
---

<!--
Over my career I've been able to guide library choices, testing strategy, software design, and elevate the adoption of my team's work among other developers.

Even as a junior and mid level dev, I was able to make an impact that would normally come with a staff-level title.
-->

---
layout: image
image: dim.jpg
---

<!--
But it wasn't always that way. Early on, I struggled to articulate my ideas and I was very UNsuccessful with steering our technical direction, even at the team level.

I used to think, it was about having the best idea, articulating it clearly, and everyone would magically rally around it.
-->

---
layout: image
image: scales.jpg
---

<!--
but there's really no best idea, there's always a tradeoff

how well you articulate and communicate can only get you so far

and the hardest thing of all turned out to be all the noise of async notifications, and creating a clear signal
that others wanted to hear
-->

---
layout: image
image: point.jpg
---

<!--
So how do we win developers, and influence adoption?

today i have three lessons I've learned that I hope will serve you

whether you maintain a library or an application, we all encounter this challenge. software development is HIGHLY collaborative and highly opinionated. to be effective beyond building features, these three lessons will greatly improve your reach and impact
-->

---
layout: image
image: point.jpg
---

# Build Trust

# Deserve Attention

# Remove Friction

<style>
  h1 {
    background-color: #000;
    font-size: 54px;
    line-height: 54px;
    width: 450px;
  }
</style>

<!--
As developers, we're very skeptical, we need to be convinced beyond any doubt, that something is not just a good idea, but worth our time and attention. So what is the foundation of earning that attention?
-->

---
layout: image
image: help.jpg
---

# Be helpful

<style>
  h1 {
    background-color: #000;
    font-size: 54px;
    line-height: 54px;
    width: 260px;
  }
</style>

<!--
Be helpful.

About everything.

In terms of having an impact within an organization, this is the single biggest takeaway I can offer you.

I've worked on some very strong teams and early in my career, I was the most junior developer, learning from some amazing senior devs. I couldn't code as fast or as well as everyone else, at least on my own, so I looked for other ways I could contribute. Our team was well known so we'd get a lot of questions, so I jumped on those questions whenever I felt I could be helpful. After a few months, I realized that folks on other teams were coming to me directly. I didn't just build trust, I built a reputation.

I've seen this lesson repeated in other ways too.

I worked on a design system team that wasn't very well known across the company at first. There were always lots of questions about React, TypeScript, and other related areas, that weren't the design system, but within our area of expertise. Our team was full of experts, and we helped out at every opportunity. It didn't matter how busy we were, we took it upon ourselves to help other teams be successful.

Over time, this elevated the profile of our team, and it got people curious what we were up to. And when we applied the next lesson, it caught on that much more.
-->

---
layout: image
image: attention.jpg
---

# Attention

<style>
  h1 {
    background-color: #000;
    font-size: 54px;
    line-height: 54px;
    width: 260px;
  }
</style>

<!--
Attention is a precious resource.

I've seen library releases come out and just list all the new features, which, make sense, but it comes from the perspective of the author.

It turns out, that doesn't always work very well. As the reader, I don't know why this matters to me, without reading more. And I'm not going to read more, unless I have a reason to. The first few words tell me whether I should read the first sentence, and the first sentence tells me if I should read the first paragraph, and if that paragraph is too long, I skip the whole thing.
-->

---
layout: image
image: mute.jpg
---

# @everyone will @nnoy everyone

<style>
  h1 {
    background-color: #000;
    font-size: 54px;
    line-height: 54px;
    width: 790px;
  }
</style>

<!--
@'ing everyone doesn't work either, it just annoys everyone. I have muted so many Slack and Discord channels because of this.

So how do we acquire attention?
-->

---
layout: image
image: meet.jpg
---

# Meet developers where they are

<style>
  h1 {
    background-color: #000;
    font-size: 54px;
    line-height: 54px;
    width: 800px;
  }
</style>

<!--
The best way I've heard it described, is "meeting people where they are."

This can be applied in several ways.

Fundamentally, it means thinking from the perspective of other developers and what they are trying to do.

I've seen lots of very fact-oriented announcements, and those work when the audience is familiar with what you mention and knows how it will solve their problem. You need the facts, sure, but seen better reaction when I lead with something different.
-->

---
layout: image
image: demos.avif
---

# Use a Hook

<style>
  h1 {
    background-color: #000;
    font-size: 54px;
    line-height: 54px;
    width: 290px;
  }
</style>

<!--
If you ever study content, writing, or marketing, you'll learn about what a hook is.

To get people to read the facts, or better, go deeper and actually digest your blog post or documentation,

you need to grab their attention.

There's a lot to writing a good hook, so today I'll just share a quick example.

Here's one from Storybook...

When I was on a design system team, I used this tactic all the time to spark conversation and get people to join our office hours. Ask a question, it's one of the simplest forms of a hook.

And if you have a feature to share, instead of speaking from your perspective about your API, speak in terms of the problem it solves.
-->

---
layout: image
image: storybook-full.png
---

<!--
Here's one from Storybook...
-->

---
layout: image
image: question.jpg
---

<!--
When I was on a design system team, I used this tactic all the time to spark conversation and get people to join our office hours. Ask a question, it's one of the simplest forms of a hook.

And if you have a feature to share, instead of speaking from your perspective about your API, speak in terms of the problem it solves.
-->

---
layout: image
image: path.jpg
---

<!--
So you've built trust, earned the attention of developers, but how do we get them to take action?

Good developers are famously called lazy developers. We will take the path of least resistance.

There are two stages where difficulty is highest in adopting our work. Getting started, and keeping up with changes.
-->

---
layout: image
image: chakra.png
---

<!--
It doesn't matter how good your solution is if you don't give developers a clear path to implement.

Good documentation is a killer feature. When I evaluate technology, the docs are my number 1 criteria.

It can be as simple as a README too, but define the steps to get started with your solution

or how to adopt what you're proposing

Here's a common but effective pattern from Chakra UI, where you spell out what to install,

then what code changes come next. along the way, they explain a few things as well.
-->

---
layout: image
image: start.png
---

<!--
Like Jack mentioned yesterday with TanStack Start,

CLI tools can also really help with adoption and getting something working even faster
-->

---
layout: image
image: package.jpg
---

<!--
One of the harder problems I've seen isn't adoption, but keeping up with changes,
bumping dependencies and things like that.

I've lost MONTHS of my professional life to bumping dependencies.

this is where investing in upgrade guides can make a massive difference.

which by the way, can also really help developers using AI to upgrade and adjust for breaking changes.
-->

---
layout: image
image: package.jpg
---

[Tanexample](https://tanstack.com/query/latest/docs/framework/react/guides/migrating-to-v5)

<style>
  a {
    /* background-color: #000; */
    font-size: 40px;
    line-height: 40px;
    /* width: 800px; */
    right: 50px;
    position: absolute;
  }
</style>

<!--
Here's an example of both I'd like to share...
-->

---

# Be helpful

# Earn attention

# Remove friction

<!--
Remember these three things to win developers and influence adoption

be helpful at every opportunity.

earn attention, with hooks baited with value

remove friction, making your path the easiest one. especially with onboarding if you want adoption, and make it stupid simple to keep up with things as they change

i promise you the reach of your team's work will grow and so will your influence on technical direction at your company
-->

---


---
layout: image
image: thank-you.jpg
---

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

## <logos-x /> @willklein\_

## <logos-bluesky /> @willkle.in

## <carbon-link /> howtowin.dev

## <carbon-lightning /> toolspace.dev

<style>
  h1 {
    /* background-color: #000; */
    font-size: 64px;
    line-height: 80px;
    width: 300px;
  }
</style>

<!--
I want to quickly thank my team at North, who supported me to attend and speak here today.

Our team supports our payment APIs and developer experience,

and one thing I love about what we do is how much we care about being helpful.

it's become exceedingly rare that you can ask for help and reach a real human easily,
and that's something I love about how we operate.
-->
