---
classes: wide
header:
  image: /assets/images/niubanner2.png
permalink: /portfolio/index.html
---



# Blog Posts

<details markdown="1">
  <summary>BP-1</summary>

## What is open source?
*Open source* means that anyone can view the source code. It means that anyone can contribute. It means that anyone can modify the source, build off of it, use it in a project, and generally just <u>do whatever they want with and/or to it.</u>

It's a framework for the collaborative and iterative manifestation of ideas in a way that makes excellent use of the time of those participating.

It's also not limited to software! There are tons of open source projects focused in part or in whole on hardware. A lot of this category can be found on [Thingiverse](https://thingiverse.com), a website that primarily hosts files for 3D printing.
## What surprised me?
I was surprised that Verizon had any involvement in the open source scene whatsoever. I don't think particularly highly of them and this doesn't change that, but it *was* surprising.

I also learned that *[Tux Paint](https://tuxpaint.org/)*--a paint program I used back in elementary school--was <u>*and still is*</u> open source! Warms the heart, doesn't it?
## Which well-known companies and projects use open source, and why does that matter?
Companies that use open source:
- [Google](https://opensource.google/)
- [Microsoft](https://opensource.microsoft.com/)
	- They own GitHub!
		- (because they bought it for billions of dollars in stock)
- [Mozilla](https://github.com/mozilla)
- [Facebook](https://opensource.fb.com/)/[Meta](https://github.com/facebook)

Projects that use open source:
  - [GNU](https://en.wikipedia.org/wiki/GNU) + [Linux](https://en.wikipedia.org/wiki/Linux)
  - [GIMP](https://www.gimp.org/), a photoshop alternative.
  - [Marlin](https://marlinfw.org), the 3D printer firmware.
  - [*<font color="#7f7f7f">Thousands more...</font>*](https://github.com)
	- [*<font color="#7f7f7f">and more!</font>*](https://codeberg.org/explore/repos)
<img alt="Tux, the mascot of Linux. He's a penguin." src="https://upload.wikimedia.org/wikipedia/commons/3/35/Tux.svg" width="100" align="right">

There's more benefit than just being able to vet the code of a corporation when they use open source. Their use of open source allows hobbyists and myriad impassioned developers to improve the tools and platforms they rely on in their workflows and everyday lives. It allows them to modify the projects to their liking and occasionally to the liking of others as a fork. It brings what could otherwise be a locked-down experience into the hands of the people who experience it. In a sense, the end-users are just the beginning.

---

Bonus content:
- <https://www.gnu.org/philosophy/open-source-misses-the-point.html>
- <https://www.gnu.org/philosophy/free-software-even-more-important.html>
</details>

<details markdown="1">
  <summary>BP-2</summary>
  # BP-2
## What I have learned about Markdown and Git
I've learned more about how branches and merging work. I still need to study it for a bit before I'm fully comfortable, but I've already found branches useful in my projects. I had never given thought to using a branch to work on developing features and leaving the main branch in a working state, but it makes a lot of sense in hindsight. I might even consider relying entirely on the command line interface once I've become more familiar with Git.

I'm familiar with Markdown, so it's not often that I learn something new about it. Lucky me, then, since I learned that I could add links to sites by enclosing a word or phrase in square brackets and then in the footnotes specifying what that something would link to, but this is something I learned from the website [Daring Fireball]. Of course, I've implemented that method for the purposes of demonstration with the link to that site in this paragraph.
### How they help me contribute to open source and improve professionally
Markdown has allowed me to communicate my thoughts more effectively than plain text would. This has helped me to document issues in programs and suggest features. Professionally, it hasn't seen much use, but I'm more than willing to teach colleagues how to use markdown to their advantage.
## Have I used Markdown and Git before?
Yes, I have. I've been making use of Git since about 2020. In fact, [my personal GitHub account](https://github.com/Lord-Memester) turned five years old on September 9th, 2025! I mainly used Git (through GitHub) to update open-source [Minecraft](https://www.minecraft.net/en-us) mods. Markdown and I have a long-standing relationship that started with the introduction of [Discord](https://discord.com/) (the communication platform, not the concept) into my life. I fell in love with the simplicity, the versatility, and the readability of the format. These days, I still use it in Discord—*and something like it in Reddit when I spend hours perfecting the structure and format of posts that nobody reads*—and in Obsidian, which is a (closed-source ☹) program I use to take notes and write these blog posts. I also use it when writing documentation for any of the programs I’ve written that someone other than myself might use.
## What surprised me about Markdown or Git?
Git is a much more complex and versatile version control system than I would have thought based on the graphical user interfaces for it that I've interacted with. Markdown... well, it's markdown. I'm far from inexperienced with it, so there isn't anything of much significance I learned that I could do with it that I didn't already know. I suppose the most surprising thing about Markdown for me was the lack of easy support for underlining text. At the moment, text can only be underlined through the use of HTML styling.
```html
<u>For example, this would be underlined!</u>
```

[Daring Fireball]:https://daringfireball.net/projects/markdown/
</details>

<details markdown="1">
  <summary>BP-3</summary>
# BP-3
> [!Note]
>  Prompt: “How I chose a repository to explore and what I found interesting about its structure, community, and contribution process.”

## How I chose a repository to explore
A couple of years ago, I picked up a Wii Balance Board at a secondhand store. It didn't see much use, and ended up under my bed until a couple of months ago. I was looking through recently updated apps on [F-Droid](https://f-droid.org) and found [openScale](https://github.com/oliexdev/openScale), and then I found out that it didn't have support for the Wii Balance Board. To summarize, I chose this repository because I'm trying to add support for the Wii Balance Board to the app. It was convenient for the purposes of this blog post and some other assignments. I hope I can be forgiven for doing things the easy way.
### What I found interesting about its:
#### Structure
The structure of the repository wasn't really anything to write home about. I appreciated that they used a branch for the active development of the latest version. The app is written mostly in Java, which is a language I'm unfamiliar with. I like how the project has split up adding support for different scales by dedicating one or two file(s) to each scale's protocol.

The [wiki](https://github.com/oliexdev/openScale/wiki) also [provides](https://github.com/oliexdev/openScale/wiki/Trisa-Body-Analyze) [some](https://github.com/oliexdev/openScale/wiki/Custom-Bluetooth-Scale) [pretty](https://github.com/oliexdev/openScale/wiki/Xiaomi-Bluetooth-Mi-Scale) [in-depth](https://github.com/oliexdev/openScale/wiki/Medisana-BS444) [explanations](https://github.com/oliexdev/openScale/wiki/Beurer-Sanitas) of *how* some of the scales' Bluetooth protocols are interpreted by the app, which could be useful if trying to add support for a new scale.

#### Community
The community of people interested in and involved with this project is a small one, and there are far more users than developers. The people who are interested come from multiple places in the word. The repository owner seems to be from Germany, and there are users in the UK and the US.

#### Contribution Process
[The wiki outlines how to begin adding support for a scale](https://github.com/oliexdev/openScale/wiki/How-to-reverse-engineer-a-Bluetooth-4.x-scale), but there is no dedicated file I could find that provides guidelines for how and in what ways to contribute to the repository.

---

I made a [contribution](https://github.com/esm7/obsidian-map-view/pull/347ithub.com/esm7/obsidian-map-view/pull/347) this week! Not to openScale, though. It wasn't anything too special, just a minor typo fix, but I figured I should still mention it. I'm glad the repository owner seemed grateful. I notice stuff like this all the time in projects but chose to address this one because of how much this class has been encouraging me to do just that. Thanks!
</details>

<details markdown="1">
  <summary>BP-4</summary>
  
> “After exploring Reveal.js, describe how it’s structured, what it’s for, and what you found interesting about the way the project is documented and maintained. Could you imagine yourself contributing to this? Why or why not?”

- - -

## What is Reveal.js?

*Reveal.js* is a web-based presentation framework with a slew of features and plugins to enhance and otherwise modify its functionality.

## How is it structured?

The project is not documented entirely in the [README.md] file and the majority of the information is instead found at [the project’s website](https://revealjs.com/). There seems to be a wealth of [example presentations](https://github.com/hakimel/reveal.js/wiki/Example-Presentations) in the repository’s [wiki](https://github.com/hakimel/reveal.js/wiki). The [contributing guide](https://github.com/hakimel/reveal.js/blob/master/.github/CONTRIBUTING.md) is contained within the repository and is short and to the point. It provides information on how to report bugs, create pull requests, and clarifies that plugins should not be submitted as pull requests. There also doesn't appear to be a dev/working branch that's in use.
<img width="1351" height="557" alt="image" src="https://github.com/user-attachments/assets/aec17827-cf9c-46f3-b2ee-fd714a5bfe75" />


## What did I find interesting about the way the project is documented and maintained?

I’m not used to seeing the [documentation](https://revealjs.com/markup/) for projects being located on another site entirely. Usually some information about usage or setup can be found directly in the [README.md] file, but that wasn’t the case with this repository. Instead, the [README] serves as a pointer to other resources that serve these purposes.

It also seems like it takes a fairly long time for pull requests to be merged, and very often they are closed without being merged.
<img width="1218" height="895" alt="image" src="https://github.com/user-attachments/assets/c70299dd-c59c-4c93-bf20-08e21ae01a1d" />


## Could I imagine myself contributing to this? Why or why not?

If it was a non-code contribution, I could see it happening. That’s not to say it’s very likely, as it seems that most of the contributions on that front have already been made. I believe [calling out a single missing semicolon in example code](https://github.com/hakimel/reveal.js/pull/3817) indicates how slim those pickings might be. I am unfortunately not familiar with JavaScript or CSS, so I’m afraid I would be out of my element. I do know some amount of HTML, so there could be something there for me to contribute though I wouldn't think it likely.

[README.md]: https://github.com/hakimel/reveal.js/blob/master/README.md
[README]: https://github.com/hakimel/reveal.js/blob/master/README.md
</details>

<details markdown="1">
  <summary>BP-5</summary>

> [!NOTE] 
> _“Ownership, Access, and Innovation: What I Learned About Licensing.”_
> - Reflect on something you learned about **open source licenses** (e.g., MIT vs GPL, what’s allowed, what’s restricted).
> - How did the **Tetris movie** shape your understanding of software ownership and distribution?
> - What surprised or intrigued you about **NIU’s approach to IP, patents, and tech transfer**?
> - How do you think licensing empowers or complicates open innovation?
> 
> 
> 
> _Bonus_: Can you find and interpret the license used in a project you’re interested in contributing to?

# BP-5

## What did I learn?
Today I learned the [WTFPL](https://www.wtfpl.net/) is a genuine license that dedicates what’s being licensed to the public domain. I had heard about it before and I thought it was a joke, making it perhaps the most amusing of the facts which I’ve become privy to over the past two meetings. I’ve also learned that the [GPL](https://www.gnu.org/licenses/gpl-3.0.en.html) is *awesome*. There’s a specific clause within it that clarifies that anyone should be allowed to modify the source code of a project. This further explains that devices that restrict or deny users access to the same abilities that the manufacturer has are “fundamentally incompatible” with the license. As a lifelong hacker, this is right up my alley. Kudos to you, Free Software Foundation!

The Tetris movie showed me that recognition of ownership of a product can be very difficult to acquire and can be subject to interference. I identified that there was a lot more money exchanging hands than I would have expected for something as seemingly simple as a game. Admittedly, I’m not certain what else I could have gleaned. That the world of business is corrupt and ruthless? That it was hard to own software when one lives in a communist country? Both of these were pretty central themes in the film, though it’s very possible I missed something.

I suppose it makes sense to observe that one’s ability to claim ownership of things they’ve created can be dependent on where in the world those creations come into being. That ‘where’ can be as large as a continent or as small as a single room within a building. In this same vein, I was surprised to learn that making use of the facilities exclusive to NIU could lead to them claiming ownership of something one invents. In retrospect, that makes sense, but I would never have come to that conclusion on my own. It’s also a fairly good fact to keep in mind if I endeavor to make things using some or all of the resources at my disposal.

## How do I think licensing empowers or complicates open innovation?

As demonstrated exceedingly well by the Tetris movie, finding and understanding how something may be or is licensed can be a highly arduous task. In some of my personal projects on GitHub, I’ve chosen to use the [Creative Commons’ ‘Attribution-NonCommercial-ShareAlike 4.0 International’ license](https://creativecommons.org/licenses/by-nc-sa/4.0/). I like the idea of ensuring people only make use of my work for their own purposes and don’t try to market it to someone when it can be employed and acquired freely. I desire to restrict them to use by individuals or corporations that do not charge others for the use of the idea or solution. In my case, the license I’ve chosen does inhibit fully open innovation.  After Mark’s presentation, I may be looking into using a different license that more closely reflects my own values.
</details>

<details markdown="1">
  <summary>BP-6</summary>

> [!Note]
> Blog Prompt: _“__My experience participating in MLH Global Hack Week: what I learned, what I contributed, and who I connected with.__”_
>
> 
>
>Write about:
>
>- What you learned from participating in MLH Global Hack Week
>- What contribution (or challenge) you made
>- Who you connected with or learned from
>- How this experience shaped your view of open source collaboration

- - -

# BP-6
<details>
<summary>
<sub>Expand for a disorganized and lengthy complaint.</sub>
</summary>

After joining the [MLH] Discord server and writing an introduction I considered that task complete and went to work on other things. When I got a notification through Discord for something with a title similar to [the machine vision event I planned on attending](https://events.mlh.io/events/13096), I was struck with worry that the event I planned on attending was beginning right that very moment. I quickly opened [the event link](https://events.mlh.io/events/13073), registered, and checked in. It wasn’t until the livestream started that I fully realized this was a different event. Given that it seemed relevant enough to the one I planned on attending, I decided to stick around and get a feel for what I could expect on 2025-10-15.

It began simply enough with a presentation that introduced some computer vision models and explained what tasks they were each best suited to and how they worked. The headlining models were [YOLOe](https://docs.ultralytics.com/models/yoloe/) and [Moondream](https://moondream.ai/). I took some notes on what these are.

- [YOLOe](https://docs.ultralytics.com/models/yoloe/)
	- A zero-shot **promptable** [YOLO] model designed for open vocabulary image segmentation
	- Detects objects
	- Probably not well suited to extracting written text from images
- [Moondream](https://moondream.ai/)
	- A *<u>V</u>ision <u>L</u>anguage <u>M</u>odel*
	- It understands images using text prompt
	- Sidenote: very poor documentation.

Less focused on was [OpenCV](https://opencv.org/), which I asked some questions about and also took notes on.

- [OpenCV](https://opencv.org/)
	- Best for manipulating images
		- applying filters, transformations, etc.
	- You can do edge detection with it

After these slides I found it difficult to pay attention. The event just turned into reading documentation, a 15 minute break to download files, and running too few demos too many times. When [Moondream](https://moondream.ai/) became the focus, I was actively disinterested. The presenter (Jocelyn Velarde) struggled to get things working and it was clear to me that it was not a tool I would want to use. I did manage to get it running locally on my desktop after the stream ended. It was painfully slow, running at a self-reported rate of a *whopping* 0.0 tokens per second. Running it through their cloud API would have been much faster, but you were only provided $5 worth of credits. In my opinion, this particular event was poorly executed. </details>

I wasn’t sure what to make of [MLH]. I expected the events to be highly polished and corporate or uninteresting in nature. I don’t know why I assumed this, but I was definitely proven wrong. 

The only event I planned to attend was [Object Tracking with YOLO and DeepSort](https://events.mlh.io/events/13096), and it was very informative! I have always been interested in computer vision and never seemed to have the motivation to pursue it in the right moments, so this was a rare opportunity I was not going to pass up.

## What I learned from [MLH] GHW

I learned how to use [YOLO] and what it was, how to train my own [YOLO] model, how to use [DeepSort](https://pypi.org/project/deep-sort-realtime/), and how to use it in conjunction with [YOLO] to track objects in videos. I also learned more about [MQTT](https://mqtt.org/) and how that works with Python.

On a more personal level, I learned that I need to up my typing game. I was scrambling to keep up with Buly during [Object Tracking with YOLO and DeepSort](https://events.mlh.io/events/13096)!

## What contribution (or challenge) I made

I completed the challenges [Star an Open Source project](https://www.mlh.com/challenges/0199ba1c-a06d-6a9e-1998-0ce925f02ef8) and [Open Source Licenses](https://www.mlh.com/challenges/0199ba20-0fe2-112f-b1bb-f877358ea7d6). Other than those, I contributed my opinions and questions to the presenters.

Outside of [MLH] GHW, I worked on getting support for the Wii Balance Board added to [openScale](https://github.com/oliexdev/openScale) with (the very significant help and extensive use of) GitHub Copilot Pro through the free and open-source [Zed editor](https://github.com/zed-industries/zed). The LLM claims to have added support for Bluetooth 3.0 devices, which I am inclined to believe as the board now shows up in the list of supported devices… *sometimes*. It’s still a huge step in the right direction and the biggest hurdle that was preventing me from progressing on my own.

<img width="308" height="302" alt="cropped_Screenshot_20251015-094934_shareable" src="https://github.com/user-attachments/assets/7a262198-7b7a-4f15-8f0f-4601a8300ef0" />

Since the code to do this was entirely written by a LLM and only kind of supervised, I haven't yet pushed this change to remote. I'd like to check that it didn't make any particularly strange or unnecessary changes before I do that.

## Who I connected with or learned from

I spent the most time with Buly (Charbel Breydy). He was the presenter for the events [MQTT + IoT with Python](https://events.mlh.io/events/13090) and [Object Tracking with YOLO and DeepSort](https://events.mlh.io/events/13096) that I attended. He was quick to answer questions and he seemed to know what he was talking about. I followed him on [GitHub](https://github.com/Buly1601) and [LinkedIn](https://www.linkedin.com/in/charbel-breydy/).

## How this experience shaped my view of open source collaboration

My view of open source collaboration is largely the same as it was prior to the event. It’s not perfect, but it can create some truly beautiful things.

[YOLO]: https://docs.ultralytics.com/models/yolo11/
[MLH]: https://mlh.io
</details>

<details markdown="1">
  <summary>BP-7</summary>

> [!NOTE] 
> Blog Prompt: _“What counts as a contribution in open source? My thoughts on the value of code and non-code contributions. How diagrams help clarify a workflows. How communication and collaboration shape successful non code contributions. What non code contribution opportunities did you find?”_

# BP-7

## What counts as a contribution in open source?

In open-source, a contribution can be:
- Translations
- Documentation
- Art
- Code

## My thoughts on the value of code and non-code contributions

Code contributions are perhaps the most common contributions on GitHub. From what I’ve observed, the most desired contributions are those that require skills programmers typically do not excel at such as creating art and writing documentation (of course, there are exceptions). I would argue that getting the word out about a project is heavily reliant on artists and writers to lower the barrier of entry for users, which makes non-code contributions likely to be more valuable than code contributions.

## How diagrams help clarify workflows

Diagrams are an incredibly useful tool. They can communicate the technical to the non-technical and vice versa much more efficiently and interactively than text on its own. They are especially useful for indicating where and why one might need to go backwards in a process. Diagrams actually have their own field of academic study known as *Diagrammatology*, which studies the role diagrams play in the creation and communication of knowledge. 

## How communication and collaboration shape successful non-code contributions

Much like any contribution in the open source community, very little will happen or go well without communication and collaboration on non-code contributions. 
- Documentation has to  be verified to be correct before it is published
- Art involves a lot of back-and-forth with the repository maintainer(s)/owner(s)
- Translations have to be agreed upon before publishing.
Ensuring all of these tasks go smoothly can only be achieved if the contributions are evaluated by multiple people. Effective communication is a requirement for these evaluations to take place and for feedback to be implemented.

## A non-code contribution opportunity I found

The android application *[Qalculate](https://github.com/jherkenhoff/qalculate-android)* has an issue calling for improvement in their documentation. Given that I use the app and agree it could benefit from improved documentation, I would be more than willing to contribute.
</details>
