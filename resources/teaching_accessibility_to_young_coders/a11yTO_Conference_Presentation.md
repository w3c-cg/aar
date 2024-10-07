---
layout: default
title: Teaching Accessibility to Young Coders
show_description: true
description: 2024 a11yTO Conference Presentation
---

[Presentation Slides](https://bit.ly/a11yto_teaching_young_coders)

Transcript follows

## Introduction

### Personal introduction
Hello, my name is Brian Elton. It’s really exciting and a bit nerve wracking to be standing up here at my hometown accessibility conference in front of all of you lovely people. I have been coming to this conference for years and look forward to it every year. 
I do live in Toronto and have wonderful 13-year old twin girls, which makes the topic I am about to discuss all the more important. 

I am the practice manager for training at TPGi, which is a large accessibility consultancy (formerly known as The Paciello Group). I spend my working days teaching our clients how to make their digital projects accessible.

Up until early this year I was also the co-chair for the Accessibility Education and Outreach Working Group (EOWG) with the W3C, but that group has successfully met its mandate and has not re-chartered. 

I now co-chair the Advancing Accessibility Resources (AAR) Community Group* which is a very new group with the intention of creating community driven resources for accessibility education. I’ll talk a little more about that towards the end of this presentation.

The slides for this presentation are available at https://bit.ly/a11yto_teaching_young_coders

As you may notice, the title I had on screen for this presentation is slightly different from what is in the playlist, which is “Accessibility for young coders”. I realized that as I was talking with people about accessibility for young coders, it was often perceived as having to do with the tools that kids with disabilities use to help them to learn code and whether they are accessible or not. Things like Accessible learning materials and Accessible integrated development environments. 

While that is an excellent and very interesting topic, there are a lot of initiatives and resources looking into this subject. 
I want to talk about how to teach digital accessibility principles to young students as they start to learn about code, as this is something that I have found is not discussed nearly enough..

But before we do that, let’s take a step back…


### Current State - Professional
With TPGi, a lot of the work that we see comes our way because of current and impending legislation that governs accessibility and the threat of lawsuits and fines often drives accessibility efforts.

The accessibility training that I do with TPGi tends to be focused on existing product teams in an effort to fix existing accessibility issues and then work towards integrating these accessibility efforts into the development lifecycle. But a lot of the time these teams have little or no accessibility knowledge or training.

A lot of these teams have come into the professional world without ever covering accessibility in their education. Until fairly recently, accessibility has not been included in computer science or digital design programs.

### Current State - Education
There are now some fantastic initiatives to include accessibility into the curriculum of college and university computer science programs, and even into intensive coding bootcamp programs where it had historically been omitted or not covered in much detail.

[Teach Access](https://teachaccess.org/) is a great example of programs that support accessibility education, but its resources skew towards the collegiate or university level. 

Unfortunately, not as much emphasis has been placed on resources for the integration of accessibility into early education. 
I feel like we all have touted the concept of introducing accessibility earlier, in the form of “shifting left” and we should be not only encouraging that as part of the SDLC, but also as part of a future coder’s or digital designer’s education, looking at ways to teach children as young as 10 about accessibility principles.

Computer science is introduced earlier than ever in school, and I believe learning about accessibility should follow suit.

### Learn to Enable, Digital for Everyone
Having said that, There is one really great research project happening in the UK called [Learn to Enable](https://www.learntoenable.co.uk/), Digital for Everyone. Their basic premise is “by sowing the seeds of basic digital accessibility awareness early into the curriculum or mindset of every young person, our next generation could grow up with lifelong skills to be able to think digital, think everyone.” Perfect premise - I love it.

Their website provides some easy to understand explanations for digital accessibility concepts that could resonate with younger students, mostly given from the perspective of document accessibility - using the tools within the software to ensure an accessible experience.

They speak to Colour and Colour contrast, image text alternatives, headings and titles, good link text, and additional advice for social media and multimedia. And these subjects will resonate. I know my 13 twin girls have been using Google productivity software for years - Google Docs and Google Slides in particular.

But we also need to bring these topics into the computer science conversation, and I think it needs to be done in a slightly different way.

## Problems with introducing accessibility earlier in education

### Limited coding knowledge and ability to relate it to accessibility
The first one seems a bit obvious because this is when kids are first learning about computer science.
* A lot of what is being taught is fairly generalized in nature and not always specific to a particular coding language
    * Logic, structure, looping, if/else statement, etc. 
* A lot of what they are learning does not relate to the typical aspects of digital accessibility - visual design and front-end development

### Limited control over the environments that they are learning on
* The students may have access to PCs in the computer lab, but many kids in middle school (in ontario at least) have been issued Chromebooks, and are limited to the assistive technology and other features that are available (ChromeVox, for instance)
* The students learn in a lot of web-based environments, such as Scratch and Code.org
    * Tend to be WYSIWYG editors or drag and drop interfaces
* The coder doesn’t have much control on the finished product so may not be able to introduce accessibility even if they knew how.

#### Scratch
Scratch, in case you are not familiar, is this really fun drag and drop tool that kids can use to create animations and game using logic and event blocks, which is great for learning computing logic, but limits them on what the actual output is.

### Educators do not have the knowledge or resources to teach accessibility
* Teachers have gone through the same education system that did not put any emphasis on accessibility, and many of them have not had the benefit of learning accessibility in a professional environment.
* Learning curriculums are often not very prescriptive in what gets taught in the early years of computer science, so it’s often up to individual teachers to include or not include a11y, which could play more into it not being taught, as they may not have the cycles to educate themselves 

But on the upside, technology is introduced to kids earlier and earlier, so their familiarity with digital technology is quite incredible (at least for how they choose to use it).

## Finding concepts that resonate with the students

### Kids are interested

This past spring (2024) I visited my daughter’s grade 7 computer science class to talk about digital accessibility and try to get a sense of what things resonated with them.

I asked them to describe what they think disability means and if they could describe different disability types. I then asked if they ever thought about how someone with a disability would use a website or their phone.

They had a fairly decent grasp of what disability is and the different generalized types of disability, but when talking through the idea of people with disabilities using digital technology, there really was a gap.

For instance, many had used zoom on their browser, but they didn’t generally tie it to someone with low vision. Or think about anyone needing to zoom to 400%.

When talking about the use of colour, there was familiarity with colour blindness and the possibility of confusing colours, but not necessarily that someone may not see something with low contrast. 

Some of the kids who I know were gamers had used the keyboard for interacting with websites, but few had ever really tried to navigate around a website using just their keyboard.

They all seemed to know about text-to-speech because of the Google browser extension Read&Write, which is a commonly used tool for helping with literacy at their age. But I don’t think any of them realized that they have a built-in screen reader with ChromeVox. Or even on their phones (which most had).

But one of my biggest takeaways is that they were all engaged, at least as engaged as a group of 12 years can be. They are fairly tech savvy and keen to learn more. It did not seem to be a drag for any of them.

## So what do we teach? 
Well, it would be different obviously depending on what age we are talking about, so for today I want to look at the earliest ages, when first introducing accessibility.

### Disability awareness
The key to learning any subject, in my opinion, is to understand why you are learning it. The kids I spoke with in the spring had a good understanding of different disability types, but most had never thought about how someone with a disability interacts with digital technology. Giving examples of real people using assistive technology will ground their knowledge in reality and hopefully bring understanding and empathy along with it.

Even if it’s simplified to relate common disability types with the tools they may use. Such as,
* Blind people using a screen reader or refreshable braille display, 
* People with Low vision using zoom on the browser to make everything larger
* A physically disabled person using their keyboard

I don’t think we would need to get into the nuances of what disability could mean, except to stress that every disabled person is different and will have their own unique way of interacting with digital content.

### Use of Colour
Colour has been ingrained in the education system from the earliest of ages, and by the time kids are learning about code, they would have used colour for graphs and maps, if they were participating in those visual activities. The kids I talked to are very aware of colour blindness, and so discussing how using colour can be problematic for some people would resonate well. I’m sure my classmates noted the times that I coloured the ocean purple or mixed up which line on a graph referred to which legend item. Yes, I’m colourblind. 

This could be as easy as just stressing the need to pick good colour combinations, ones that are very clear for everyone, and avoiding using colour alone (I wish I had thought of ways to add another dimension to the legends when doing graphs in school).

### Screen Readers
As I mentioned earlier, the kids will most likely have already had experience with text-to-speech, through things like the Google browser extension Read&Write, but text-to-speech only reads text with no information about roles and states. Remember the main intention of the Read&Write extension is to help with literacy, allowing students to hear the words announced as they are reading them on a website or document. 

There are keyboard controls for Read&Write, so there may already be a concept of an idea of how to control something like a screen reader.

So, Get the kids to fire up ChromeVox, give them some simple keyboard commands and let them explore. Or even use VoiceOver or Talkback on their mobile devices.

Using a screen reader is a very impactful way for someone to experience a website, and hopefully by exposing them to a screen reader early it will take away some of the hesitation to use one later in life, as they can be somewhat intimidating for someone that has never used one before (including me, back in my early days of learning accessibility). 

We also have to remember, kids have fun with technology and are naturally curious about it, so having them use a screen reader is not a big ask.

### Text alternatives
Now with the experience of screen readers under their belt, talk about visual aspects of a website wouldn’t be accessible to a screen reader user without some sort of text alternative. We don’t need to go into the alt attribute in an HTML image element just yet - just the notion that if there is something purely visual, that there has to be another way for a screen reader or other similar assistive technology to interpret it. 

### Zooming
Most kids will have played with the built in browser zoom feature, but to what extreme? Changing the zoom levels and then using a website is a very easy activity to show how sites that don’t make proper use of responsive design can be really tough to navigate. Particularly when zooming to 400%.

### Keyboard 
Keyboard accessibility is another fairly easy thing to demonstrate and see immediate ramifications. Ask the students to push their mouse to the side and try to use a website. Focus order, visible focus should be fairly easy topics to address, as there is natural visual feedback for the sighted students.

### Goals
The goal of all of these things is not to necessarily learn how to code for these scenarios (at least not yet), but to just to have some first hand experience with what someone with a disability could encounter every day.

And then when they start to build their own projects, they will hopefully know to ask the right questions when issues come up. 
* How do I make sure I’m using the right colours for my text?
* My site doesn’t work with a keyboard - how do I fix that?
* I thought I put a button in my site, but ChromeVox doesn’t say that it’s a button. Why? 

## What not to teach 
WCAG, legislation, SDLCs, accessibility programs. We want the kids to think about accessibility as the default. There was discussion earlier about creating a culture around accessibility in the workplace, and I see no better way to do that than to introduce it at this age where it just becomes part of code, part of design, and not based just on avoiding lawsuits. Also, we don’t want to bore them…

## Creating resources for educators

### Teachers need the knowledge and resources

As I mentioned at the beginning of this talk, there are some great resources available for teaching accessibility at the collegiate or university level - Teach Access being one of them. 

The only resource that I have found that targets a younger audience is the Learn to Enable project in the UK, and as mentioned, it focuses mostly on accessibility principles as they relate to documents.

If we are going to be successful in teaching digital accessibility to these kids, their teachers need the knowledge and resources.
I mentioned at the beginning that I am the co-chair of the AAR CG. This group is part of the W3C’s community group program that promotes these groups as “open forums where Web developers and other stakeholders develop specifications, hold discussions, develop test suites, and connect with W3C's international community of Web experts.”

The community groups are open to anyone that wishes to be involved. 

### Where do we go from here?
As part of the AAR community group, we are building a resource specifically for teaching digital accessibility to young coders, to not only talk about the concepts that we should be teaching, but also to provide education and resources for their teachers. It is in the very early stages and there is a lot of work to do!

The next steps that I am preparing for
* Identify or validate the accessibility topics that will resonate, both at the very beginning of their CS education, which is along the lines of what I have been describing, and as they learn more about HTML, CSS, and digital design
* Brainstorm on the most appropriate and impactful ways to teach that information, which could depend on age and the CS topics that they are learning
* Create resources to help teachers, in the form of learning materials, example websites, and resources for the teachers themselves to learn more about accessibility

If this is something that interests you, I encourage you to join the AAR CG as an active participant. You do not need to be a part of a W3 member organization or have any special qualifications - just an interest in contributing to what I hope will be a very valuable resource.


It is never too early to start learning about accessibility!
