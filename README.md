Brackets에 오신것을 환영 합니다. [![Build Status](https://travis-ci.org/adobe/brackets.svg?branch=master)](https://travis-ci.org/adobe/brackets)
-------------------

Brackets은 HTML, CSS 그리고 Javascript로 만들어진 HTML, CSS, Javascript를 위한 현대적인 오픈소스 코드 에디터 입니다.  

이 프로젝트는 예전에 Adobe가 관리하던 [프로젝트](https://github.com/adobe/brackets)의 포크입니다.  
우리는 밀래에 이름을 변경 할 것입니다. 

A lot of work needs to be done to make this fork become independent. Feel free to open a PR!
Want to help coordinating the project itself? Check the projects tab ([here](https://github.com/brackets-cont/brackets/projects/1?fullscreen=true)).

다른 웹 코드 에디터들과 Brackets은 어떤 차이들을 만드나요?

* **Tools shouldn't get in your way.** Instead of cluttering up your coding
environment with lots of panels and icons, the Quick Edit UI in Brackets puts 
context-specific code and tools inline.
* **Brackets is in sync with your browser.** With Live Preview, Brackets
works directly with your browser to push code edits instantly and jump
back and forth between your real source code and the browser view.
* **Do it yourself.** Because Brackets is open source, and built with HTML, CSS
and JavaScript, you can [help build](https://github.com/brackets-cont/brackets/blob/master/CONTRIBUTING.md) the best code editor for the web.

Brackets는 1.0 버전이 되었습니다. 하지만, 우리는 멈추지 않을 겁니다. We have many feature ideas on our
[trello board](http://bit.ly/BracketsTrelloBoard) that we're anxious to add and other
innovative web development workflows that we're planning to build into Brackets. 
So take Brackets out for a spin and let us know how we can make it your favorite editor. 

당신은 위키에서 약간의 [Brackets 스크린샷](https://github.com/brackets-cont/brackets/wiki/Brackets-Screenshots)을, 유투브에서 [소개 비디오](http://www.youtube.com/user/CodeBrackets)를, 그리고 [Brackets 블로그](http://blog.brackets.io/)에서 소식을 볼 수있습니다. 

Brackets 설치 및 실행
-------------------------------
#### 다운로드
마지막 Mac과 Winsows를 위한 안정버젼 설치관리자는 [여기](https://brackets-cont.github.io/)에서 다운로드할 수 있습니다.

#### 사용

By default, Brackets opens a folder containing some simple "Getting Started" content.
You can choose a different folder to edit using *File > Open Folder*.

Most of Brackets should be pretty self-explanatory, but for information on how
to use its unique features, like Quick Edit and Live Preview, please read
[How to Use Brackets](http://github.com/brackets-cont/brackets/wiki/How-to-Use-Brackets). 
Also, see the [release notes](http://github.com/brackets-cont/brackets/wiki/Release-Notes)
for a list of new features and known issues in each build.

In addition to the core features built into Brackets, there is a large and growing
community of developers building extensions that add all sorts of useful functionality.
See the [Brackets Extension Registry](https://registry.brackets.io/)
for a list of available extensions. For installation instructions,
see the [extensions wiki page](https://github.com/brackets-cont/brackets/wiki/Brackets-Extensions).

#### 도움이 필요한가요?

Having problems starting Brackets the first time, or not sure how to use Brackets?  Please 
review [Troubleshooting](https://github.com/brackets-cont/brackets/wiki/Troubleshooting), which helps 
you to fix common problems and find extra help if needed.

Brackets를 도우는 법
----------------

#### 나는 버그를 발견 했습니다. 

If you found a repeatable bug, and [troubleshooting](https://github.com/brackets-cont/brackets/wiki/Troubleshooting) 
tips didn't help, then be sure to [search existing issues](https://github.com/brackets-cont/brackets/issues) first.
Include steps to consistently reproduce the problem, actual vs. expected results, screenshots, and your OS and
Brackets version number. Disable all extensions to verify the issue is a core Brackets bug.
[Read more guidelines for filing good bugs.](https://github.com/brackets-cont/brackets/wiki/How-to-Report-an-Issue)


#### 제안이 있습니다만, 프로그램을 개발하지 못합니다. 

For feature requests please first check our [Trello board](http://bit.ly/BracketsBacklog) to
see if it's already there; you can upvote it if so. If not, feel free to file it as an issue as above; we'll
move it to the feature backlog for you.


#### 프로그램 고드로 도움을 드리고 싶습니다. 

Awesome! _There are lots of ways you can help._ First read 
[CONTRIBUTING.md](https://github.com/brackets-cont/brackets/blob/master/CONTRIBUTING.md), 
then learn how to [pull the repo and hack on Brackets](https://github.com/brackets-cont/brackets/wiki/How-to-Hack-on-Brackets).

The text editor inside Brackets is based on 
[CodeMirror](http://github.com/codemirror/CodeMirror)&mdash;thanks to Marijn for
taking our pull requests, implementing feature requests and fixing bugs! See 
[Notes on CodeMirror](https://github.com/brackets-cont/brackets/wiki/Notes-on-CodeMirror)
for info on how we're using CodeMirror.

Although Brackets is built in HTML/CSS/JS, it currently runs as a desktop 
application in a thin native shell, so that it can access your local files.
(If you just try to open the index.html file in a browser, it won't work yet.)
The native shell for Brackets lives in a separate repo, 
[brackets-cont/brackets-shell](https://github.com/brackets-cont/brackets-shell/).


I want to keep track of how Brackets is doing!
----------------------------------------------

Not sure you needed the exclamation point there, but we like your enthusiasm.

#### 이 다음에 Brackets 어떤 작업을 할 것입니까?

* In our [feature backlog](http://bit.ly/BracketsBacklog), the columns to the right
  (starting from "Development") list the features that we're currently working on.
  "Ready" shows what we'll be working on next.
* Watch our [GitHub activity stream](https://github.com/brackets-cont/brackets/pulse).
* The entire development process is outlined in the [Developer Guide](https://github.com/brackets-cont/brackets/wiki/Brackets-Developers-Guide).

#### 연락처 정보

<!-- * **E-mail:** [admin@brackets.io](mailto:admin@brackets.io)
* **Slack:** [Brackets on Slack](https://brackets.slack.com) (You can join by sending a mail to [admin@brackets.io](mailto:admin@brackets.io) with the subject line `slack registration request` specifying the email addresses you would like to register).
* **Developers mailing list:** http://groups.google.com/group/brackets-dev
* **Twitter:** [@brackets](https://twitter.com/brackets)
* **Blog:** http://blog.brackets.io/
* **IRC:** [#brackets on freenode](http://webchat.freenode.net/?channels=brackets)
-->
* **Matrix:** [@brackets-cont:matrix.org](https://matrix.to/#/#brackets-cont:matrix.org)
* **Discord:** [Brackets Discord Server](https://discord.gg/rBpTBPttca)
* **Reddit:** [r/Brackets](https://www.reddit.com/r/brackets/)
---

Please note that this project is released with a [Contributor Code of Conduct](https://github.com/brackets-cont/brackets/blob/master/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.
