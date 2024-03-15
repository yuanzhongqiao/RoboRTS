<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人即时战略</font></font></h1><a id="user-content-roborts" class="anchor" aria-label="永久链接：RoboRTS" href="#roborts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://travis-ci.org/RoboMaster/RoboRTS" rel="nofollow"><img src="https://camo.githubusercontent.com/8a24893d8359658294ef3d777e3a728ae8e590c4d79589d031a6a43b1cd295b4/68747470733a2f2f7472617669732d63692e6f72672f526f626f4d61737465722f526f626f5254532e7376673f6272616e63683d6d6173746572" alt="构建状态" data-canonical-src="https://travis-ci.org/RoboMaster/RoboRTS.svg?branch=master" style="max-width: 100%;"></a>
<a href="https://gitter.im/RoboMaster/RoboRTS?utm_source=badge&amp;utm_medium=badge&amp;utm_campaign=pr-badge" rel="nofollow"><img src="https://camo.githubusercontent.com/ed5dc4ba437243ba313f81f961e537cbbbec7636266059d279ba892d186a0b23/68747470733a2f2f6261646765732e6769747465722e696d2f526f626f4d61737465722f526f626f5254532e737667" alt="吉特" data-canonical-src="https://badges.gitter.im/RoboMaster/RoboRTS.svg" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍</font></font></h2><a id="user-content-introduction" class="anchor" aria-label="永久链接：简介" href="#introduction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/RoboMaster/RoboRTS/blob/icra2019/images/robot.jpg"><img src="https://github.com/RoboMaster/RoboRTS/raw/icra2019/images/robot.jpg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RoboRTS 是一个用于移动机器人实时策略研究的开源软件堆栈，由 RoboMaster 开发并受到</font></font><a href="#competition"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RoboMaster 人工智能挑战赛的推动</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RoboRTS的框架由两部分组成：自主移动机器人层和智能决策层。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/RoboMaster/RoboRTS/blob/icra2019/images/system.png"><img src="https://github.com/RoboMaster/RoboRTS/raw/icra2019/images/system.png" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅自主移动机器人层就可以让RoboMaster人工智能机器人平台官方支持的机器人展现出一定程度的智能。</font><font style="vertical-align: inherit;">其机载计算机上运行感知、运动规划、决策模块。</font><font style="vertical-align: inherit;">它在 ROS 中得到完全支持，具有社区驱动以及平台定制的代码和示例。</font><font style="vertical-align: inherit;">在其 MCU 上，实现了 RT 低级机器人控制器来控制机器人驱动系统。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">智能决策层包括多智能体决策框架和游戏模拟器，即将发布。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">教程</font></font></h2><a id="user-content-tutorial" class="anchor" aria-label="永久链接：教程" href="#tutorial"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多关于RoboMaster人工智能机器人平台和RoboRTS框架的信息，请参考</font></font><a href="https://robomaster.github.io/RoboRTS-Tutorial/#/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RoboRTS教程</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">竞赛</font></font></h2><a id="user-content-competition" class="anchor" aria-label="永久链接： 竞争" href="#competition"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RoboMaster自2017年起举办AI挑战赛。挑战赛中，多个机器人在不同的规则下自动在游戏场上进行对战。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欲了解更多信息，请参阅</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><a href="https://icra2019.org/competitions/dji-robomaster-ai-challenge" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DJI RoboMaster 2019 ICRA 人工智能挑战赛</font></font></a></p>
</li>
<li>
<p dir="auto"><a href="https://icra2018.org/dji-robomaster-ai-challenge/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DJI RoboMaster 2018 ICRA 人工智能挑战赛</font></font></a></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版权和许可</font></font></h2><a id="user-content-copyright-and-license" class="anchor" aria-label="永久链接：版权和许可" href="#copyright-and-license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="/RoboMaster/RoboRTS/blob/icra2019/COPYING"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RoboRTS 根据GPL-v3</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供</font><font style="vertical-align: inherit;">。</font></font></p>
</article></div>
