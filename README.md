# About Me



## My skills & hobbies

- I have 15 years of experience in web development, and proficient in HTML, CSS, JavaScript, TypeScript, NodeJS, Electron.
- I'm also proficient in both Graphic and Imaging algorithms, and have experience building these types of apps.
- I enjoy collecting and categorizing data.



## Education and work career

- 2004~2008: WuHan University - Computer Sciences and Technology
- 2010~2011: Worked at a small company in ShenZhen, called <https://cfzx.cn/> (Not available any more), as frontend developer
- 2011~2015: Worked at MorningStar [Advisor WorkStation](https://workstation.morningstar.com/support/help-topics/blt9ac9152cd301abb7/blt717e87c790ee413a?lang=en-us) team, as frontend developer
- 2015~2018: Worked at [WangXuTech](https://www.wangxutech.com/), as frontend manager
- 2018~2019: Self-study on Design, Machine Learning
- 2019~2023: Worked at [WangXuTech](https://www.wangxutech.com/), as algorithm engineer
- 2023~2025: Think and design, working on some open-source projects like [lupos](https://github.com/pucelle/lupos)


## Betweens 2008 ~ 2010

After graduated and before first work.

- Played World of Warcraft much, made several plugins and model modifying tools.
- Created [WoW Professions](https://github.com/pucelle/wow-professions), [WoW Rare Finder / Atlasloot](https://github.com/pucelle/wow-rare-finder-atlasloot), they are not only tools, but also the expression of my feelings to wow.



## Betweens 2010~2011

Worked at <https://cfzx.cn/> (Not available any more), daily work is building web pages by HTML and CSS, few JS.



## Betweens 2011~2015

Worked at MorningStar [Advisor WorkStation](https://workstation.morningstar.com/support/help-topics/blt9ac9152cd301abb7/blt717e87c790ee413a?lang=en-us) team.

My daily work is developing and maintaining an advisor system for investors. Here we use [Ext.js](https://www.sencha.com/products/extjs/) framework, it's a professional and amazing framework, which totally affected my code style.

The culture and design style of MorningStar have greatly influenced on me.



## Betweens 2015~2018

Joined [WangXuTech](https://www.wangxutech.com/) to meet more challenges, as frontend leader.



### [web.airmore.com](http://web.airmore.com/)

<img src="./images/web.airmore.jpg" width="800" height="400">

It's a web tool that can manage phone resources.

Although still available, some features had been broken due to lack of maintenance, and some ugly ads had been added.



### Developed common ui library, and built sites by the library:

- [airmore.com](https://airmore.com/)
- [apowersoft.com](https://www.apowersoft.com/)
- [wantxutech.com](https://www.wangxutech.com/)
- [videograbber.net](https://videograbber.net/)
- ...



### [Phone Manager](https://www.apowersoft.com/phone-manager)

<img src="./images/phone-manager.jpg" width="800" height="532">

Powered by Electron.



### Translation Management

<img src="./images/translation-manager.jpg" width="800" height="400">

It's an internal web app, I created it in my pocket of time to manage translations of Phone Manager, it saves much time for translators, so later it serves more projects.



## Betweens 2018~2019

A gap year, making a 'white-space' in mind to avoid just being a task-doer and to try to become a thinker.



### Reading

Reading design books, especially design psychology books.



### [CSS Navigation](https://github.com/pucelle/vscode-css-navigation)

**CSS Navigation** is a VSCode plugin.

When I'm learning TypeScript and wanting to go deeper, and found no good css plugin at that moment, I created this plugin.

It is 10x faster with only 1/10 memory usage and package size than it's competitors. Has 580K installs.



### [Azeroth Venture](https://wow.playjournals.com/classic/en/)

<img src="./images/azeroth-venture.jpg" width="800" height="400">

On 2019, when World of Warcraft Classic launched, I created this site, it's a single-page web application, it helped me exploring Azeroth.

It provides much more convenient user experience for querying than other apps, I designed this app from my own perspective, and try to reach final query result directly.



### Others

- [flit.js](https://github.com/purhya/flit.js): A MVVM framework, had been obsoleted.
- [flit.ui](https://github.com/purhya/flit.ui): A UI library based on flit.js, serves [Azeroth Venture](https://wow.playjournals.com/classic/en/), had been obsoleted.
- [Run on Save](https://github.com/pucelle/vscode-run-on-save): A vscode plugin, just for convenience when compiling Sass codes.



## 2019~2023

Back to WangXuTech, start new career as an algorithm engineer.



### [OpenGL Effects](https://github.com/purhya/gl-effects-preview)

OpenGL effects, serves some photo/video editing apps. Feature includes:

- [Color Adjustment](https://purhya.github.io/gl-effects-preview/#color-adjustment/)
- [Transitions](https://purhya.github.io/gl-effects-preview/#transitions/)



### [AEGL](https://purhya.github.io/gl-effects-preview/#aegl/)

<img src="./images/aegl.jpg" width="800" height="500">

**AEGL** aimed on rendering After Effects template with OpenGL, I created it for enhancing [LightMV](https://lightmv.com/).

This project had been abandoned because it encodes videos too slowly on browsers (20x slower than desktop apps), and AE is too complex, especially it's plugin system.

Two years later, web codecs APIs becomes available, I replaced the video encoder and achieved 10x increasement in encoding speed. If aimed on implementing an independent app, not reply on AE to make template, this project is more closer to reality.



### [Mindmap Core](https://github.com/purhya/mindmap-preview)

<img src="./images/mindmap.jpg" width="800" height="400">

**Mindmap Core** is a mindmap library for [GitMind](https://gitmind.com/).

This library uses SVG to render just like other mindmap apps, but it increases performance much by reducing document reading and writing and re-layout times. Otherwise, the library uses vector and direction modeling simplifies complex math computations.



### Others

- Matting Algorithm Implementation and Improvement: By removing image background, an alpha image generated. My task is to research papers, and implement several in Python AOT / OpenGL, optimize parameters, compare and choose.
- Other Image Enhancement Algorithm Design and Implementation: Like skin smoothing, tune enhancement...



## 2023 ~


### Researches & Solves.

Research on Information Flow Design.



### [lupos](https://github.com/pucelle/lupos)

**lupos** is a framework to support component-based programming in TypeScript.

In my web system programming career, especially in [AEGL](https://github.com/purhya/gl-effects-preview/#aegl) and [Mindmap Core](https://github.com/purhya/mindmap-preview), I realized there are two problems can't be solved by experience or design:

- Observing data changes
- Efficiently update after data changes

**lupos** was designed to solve them.

- How to observe data changes - by TypeScript aot analysis and injecting optimized tracking codes
- How to efficiently update after data changes - by pre-compiling template literal



### [lupos.js](https://github.com/pucelle/lupos.js)

**lupos.js** is a library for building Web User Interface, powered by **lupos**.

It's code is superior simple, it proves **lupos** can be used to build modern libraries like React.



### [flit](https://github.com/pucelle/flit)

**flit** is a lightweight Web UI system based on **lupos** and **lupos.js**.

**flit** was highly inspired by [MorningStar Design System](http://designsystem.morningstar.com/index.html).