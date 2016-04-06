##CN
机器翻译,参照EN下面原文理解
<article class="markdown-body entry-content" itemprop="text"><p><a href="https://webpack.github.io"><img src="https://camo.githubusercontent.com/ebc085019011ababb0d35024824304831c7dc72a/68747470733a2f2f7765627061636b2e6769746875622e696f2f6173736574732f6c6f676f2e706e67" alt="webpack" data-canonical-src="https://webpack.github.io/assets/logo.png" style="max-width:100%;"></a></p>

<p><a href="https://www.npmjs.com/package/webpack"><img src="https://camo.githubusercontent.com/1e98799463a629b608590357e12a1eb4714bcb60/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f7765627061636b2e737667" alt="NPM version" data-canonical-src="https://img.shields.io/npm/v/webpack.svg" style="max-width:100%;"></a> <a href="https://gitter.im/webpack/webpack"><img src="https://camo.githubusercontent.com/3db5d4b84b3433346c6536b78368154bda809d88/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6769747465722d7765627061636b2532467765627061636b2d627269676874677265656e2e737667" alt="Gitter chat" data-canonical-src="https://img.shields.io/badge/gitter-webpack%2Fwebpack-brightgreen.svg" style="max-width:100%;"></a> <a href="http://badge.fury.io/js/webpack"><img src="https://camo.githubusercontent.com/2ae104f2d51e538878bca62b79cba656b62e41a6/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f646d2f7765627061636b2e737667" alt="Downloads" data-canonical-src="https://img.shields.io/npm/dm/webpack.svg" style="max-width:100%;"></a></p>

<p><a href="https://www.npmjs.com/package/webpack"><img src="https://camo.githubusercontent.com/14b447ef2083508fafdbe47c0f2a2bff6747c851/68747470733a2f2f6e6f6465692e636f2f6e706d2f7765627061636b2e706e673f646f776e6c6f6164733d7472756526646f776e6c6f616452616e6b3d747275652673746172733d74727565" alt="NPM" data-canonical-src="https://nodei.co/npm/webpack.png?downloads=true&amp;downloadRank=true&amp;stars=true" style="max-width:100%;"></a></p>

<p><trans data-src="build
" data-dst="建立">建立</trans><a href="https://travis-ci.org/webpack/webpack"><img src="https://camo.githubusercontent.com/3312bc2144e3708c725e9167fc396e51d2504f7f/68747470733a2f2f696d672e736869656c64732e696f2f7472617669732f7765627061636b2f7765627061636b2e737667" alt="Build Status" data-canonical-src="https://img.shields.io/travis/webpack/webpack.svg" style="max-width:100%;"></a> <a href="https://ci.appveyor.com/project/sokra/webpack/branch/master"><img src="https://camo.githubusercontent.com/daa677a689cea40c2b45be8ed8e428c271cb8242/68747470733a2f2f63692e6170707665796f722e636f6d2f6170692f70726f6a656374732f7374617475732f6769746875622f7765627061636b2f7765627061636b3f7376673d74727565" alt="Appveyor Status" data-canonical-src="https://ci.appveyor.com/api/projects/status/github/webpack/webpack?svg=true" style="max-width:100%;"></a>  <a href="https://coveralls.io/r/webpack/webpack/"><img src="https://camo.githubusercontent.com/fb005c349d6e4b6671baeedd5a90f30c5841c4d3/68747470733a2f2f696d672e736869656c64732e696f2f636f766572616c6c732f7765627061636b2f7765627061636b2e737667" alt="Coverage Status" data-canonical-src="https://img.shields.io/coveralls/webpack/webpack.svg" style="max-width:100%;"></a></p>

<p><trans data-src="dependencies
" data-dst="依赖">依赖</trans><a href="https://david-dm.org/webpack/webpack"><img src="https://camo.githubusercontent.com/1ef3de968f0aa82b54146c53b18b363c9733b24f/68747470733a2f2f696d672e736869656c64732e696f2f64617669642f7765627061636b2f7765627061636b2e737667" alt="Dependency Status" data-canonical-src="https://img.shields.io/david/webpack/webpack.svg" style="max-width:100%;"></a> <a href="https://david-dm.org/webpack/webpack#info=devDependencies"><img src="https://camo.githubusercontent.com/8679285d5ea5c17729a7e4f6c2efb360436b7114/68747470733a2f2f64617669642d646d2e6f72672f7765627061636b2f7765627061636b2f6465762d7374617475732e737667" alt="devDependency Status" data-canonical-src="https://david-dm.org/webpack/webpack/dev-status.svg" style="max-width:100%;"></a> <a href="https://david-dm.org/webpack/webpack#info=peerDependencies"><img src="https://camo.githubusercontent.com/dd7ac890932dbce07e57dfa8cc8238460aaa45d9/68747470733a2f2f64617669642d646d2e6f72672f7765627061636b2f7765627061636b2f706565722d7374617475732e737667" alt="peerDependency Status" data-canonical-src="https://david-dm.org/webpack/webpack/peer-status.svg" style="max-width:100%;"></a></p>

<p><trans data-src="donation
" data-dst="捐款">捐款</trans><a href="https://gratipay.com/webpack/"><img src="https://camo.githubusercontent.com/ee066f22dcbe51a907e845674c9c0b1f874068c0/68747470733a2f2f696d672e736869656c64732e696f2f67726174697061792f7765627061636b2e737667" alt="gratipay donate button" data-canonical-src="https://img.shields.io/gratipay/webpack.svg" style="max-width:100%;"></a> <a href="http://sokra.github.io/"><img src="https://camo.githubusercontent.com/a47ee6401545d0ea8f98db88d43d960a6ee1a764/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e6174652d736f6b72612d627269676874677265656e2e737667" alt="Donate to sokra" data-canonical-src="https://img.shields.io/badge/donate-sokra-brightgreen.svg" style="max-width:100%;"></a></p>

<p><a href="https://github.com/defunctzombie/badginator"><img src="https://camo.githubusercontent.com/e0d762d2ebbfe38e5cae5bc7e001e9c5ceb36577/68747470733a2f2f62616467696e61746f722e6865726f6b756170702e636f6d2f7765627061636b2f7765627061636b2e737667" alt="BADGINATOR" data-canonical-src="https://badginator.herokuapp.com/webpack/webpack.svg" style="max-width:100%;"></a></p>

<p><a href="https://webpack.github.io/docs/?utm_source=github&amp;utm_medium=readme&amp;utm_campaign=top"><trans data-src="documentation" data-dst="文档">文档</trans></a></p>

<h1><a id="user-content-introduction" class="anchor" href="#introduction" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Introduction" data-dst="说明">说明</trans></h1>

<p><trans data-src="webpack is a bundler for modules. The main purpose is to bundle JavaScript
files for usage in a browser, yet it is also capable of transforming, bundling,
or packaging just about any resource or asset." data-dst="一捆WebPACK模块。主要目的是把JavaScript 
文件在浏览器的使用，但也可转化，捆绑，
或包装几乎任何资源或。">一捆WebPACK模块。主要目的是把JavaScript 
文件在浏览器的使用，但也可转化，捆绑，
或包装几乎任何资源或。</trans></p>

<p><strong><trans data-src="TL; DR" data-dst="TL博士">TL博士</trans></strong></p>

<ul>
<li><trans data-src="Bundles both " data-dst="束">束</trans><a href="http://wiki.commonjs.org/"><trans data-src="CommonJs" data-dst="CommonJS">CommonJS</trans></a><trans data-src=" and " data-dst="和">和</trans><a href="https://github.com/amdjs/amdjs-api/wiki/AMD"><trans data-src="AMD" data-dst="AMD"><trans data-src="AMD" data-dst="AMD">AMD</trans></trans></a><trans data-src=" modules (even combined)." data-dst="模块（甚至结合）。">模块（甚至结合）。</trans></li>
<li><trans data-src="Can create a single bundle or multiple chunks that are asynchronously loaded at runtime (to reduce initial loading time)." data-dst="可以创建一个单束或多块，在运行时异步加载（减少加载时间）。">可以创建一个单束或多块，在运行时异步加载（减少加载时间）。</trans></li>
<li><trans data-src="Dependencies are resolved during compilation reducing the runtime size." data-dst="依赖减少运行时编译期间解决大小。">依赖减少运行时编译期间解决大小。</trans></li>
<li><trans data-src="Loaders can preprocess files while compiling, e.g. coffeescript to JavaScript, handlebars strings to compiled functions, images to Base64, etc." data-dst="装载机可以在编译预处理文件，如CoffeeScript的JavaScript，车把字符串编译功能，图像以base64，等。">装载机可以在编译预处理文件，如CoffeeScript的JavaScript，车把字符串编译功能，图像以base64，等。</trans></li>
<li><trans data-src="Highly modular plugin system to do whatever else your application requires." data-dst="高度模块化的插件系统做任何你的应用需要。">高度模块化的插件系统做任何你的应用需要。</trans></li>
</ul>

<h1><a id="user-content-getting-started" class="anchor" href="#getting-started" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Getting Started" data-dst="入门指南">入门指南</trans></h1>

<p><trans data-src="Check out webpack's " data-dst="看看WebPACK的">看看WebPACK的</trans><a href="https://webpack.github.io/docs/?utm_source=github&amp;utm_medium=readme&amp;utm_campaign=trdr"><trans data-src="documentation" data-dst="文档">文档</trans></a><trans data-src=" for quick Getting Started guide, in-depth usage,
tutorials and resources." data-dst="快速入门指南，深入应用，
教程。">快速入门指南，深入应用，
教程。</trans></p>

<h1><a id="user-content-installation" class="anchor" href="#installation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Installation" data-dst="安装">安装</trans></h1>

<p><trans data-src="project:
" data-dst="项目">项目</trans><code><trans data-src="npm install webpack --save-dev" data-dst="NPM安装WebPACK --拯救开发">NPM安装WebPACK --拯救开发</trans></code></p>

<p><trans data-src="global:
" data-dst="全球：">全球：</trans><code><trans data-src="npm install webpack -g" data-dst="NPM安装WebPACK g">NPM安装WebPACK g</trans></code></p>

<p><trans data-src="Usage:
" data-dst="使用：">使用：</trans><a href="https://webpack.github.io/docs/tutorials/getting-started/"><trans data-src="https://webpack.github.io/docs/tutorials/getting-started/" data-dst="https://webpack.github.io/docs/tutorials/getting-started/"><trans data-src="https://webpack.github.io/docs/tutorials/getting-started/" data-dst="https://webpack.github.io/docs/tutorials/getting-started/">https://webpack.github.io/docs/tutorials/getting-started/</trans></trans></a></p>

<h1><a id="user-content-examples" class="anchor" href="#examples" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Examples" data-dst="实例">实例</trans></h1>

<p><trans data-src="Take a look at the " data-dst="看一看">看一看</trans><a href="https://github.com/webpack/webpack/tree/master/examples"><code><trans data-src="examples" data-dst="实例">实例</trans></code></a><trans data-src=" folder." data-dst="文件夹">文件夹</trans></p>

<h1><a id="user-content-features" class="anchor" href="#features" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Features" data-dst="功能特色">功能特色</trans></h1>

<h2><a id="user-content-plugins" class="anchor" href="#plugins" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Plugins" data-dst="插件">插件</trans></h2>

<p><trans data-src="webpack has a " data-dst="WebPACK有">WebPACK有</trans><a href="https://webpack.github.io/docs/plugins.html"><trans data-src="rich plugin
interface" data-dst="富
接口插件">富
接口插件</trans></a><trans data-src=". Most of the features
within webpack itself use this plugin interface. This makes webpack very
" data-dst="。大部分的功能
 WebPACK本身在使用这个插件接口。这使得WebPACK非常">。大部分的功能
 WebPACK本身在使用这个插件接口。这使得WebPACK非常</trans><strong><trans data-src="flexible" data-dst="能变形">能变形</trans></strong><trans data-src="." data-dst="。">。</trans></p>

<h2><a id="user-content-performance" class="anchor" href="#performance" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Performance" data-dst="性能">性能</trans></h2>

<p><trans data-src="webpack uses async I/O and has multiple caching levels. This makes webpack fast
and incredibly " data-dst="WebPACK使用异步I/O和多个缓存层次。这使得快速
 WebPACK难以置信">WebPACK使用异步I/O和多个缓存层次。这使得快速
 WebPACK难以置信</trans><strong><trans data-src="fast" data-dst="快">快</trans></strong><trans data-src=" on incremental compilations." data-dst="我们增量编译。">我们增量编译。</trans></p>

<h2><a id="user-content-loaders" class="anchor" href="#loaders" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Loaders" data-dst="装载机">装载机</trans></h2>

<p><trans data-src="webpack enables use of loaders to preprocess files. This allows you to bundle
" data-dst="WebPACK可以使用预处理文件的装载机。这允许你束">WebPACK可以使用预处理文件的装载机。这允许你束</trans><strong><trans data-src="any static resource" data-dst="任何静态资源">任何静态资源</trans></strong><trans data-src=" way beyond JavaScript. You can easily " data-dst="超出JavaScript。你可以很容易的">超出JavaScript。你可以很容易的</trans><a href="https://webpack.github.io/docs/loaders.html"><trans data-src="write your own
loaders" data-dst="自己写的
装载机">自己写的
装载机</trans></a><trans data-src=" using node.js." data-dst="使用Node.js。">使用Node.js。</trans></p>

<p><trans data-src="Loaders are activated by using " data-dst="装载机是激活使用">装载机是激活使用</trans><code><trans data-src="loadername!" data-dst="loadername！">loadername！</trans></code><trans data-src=" prefixes in " data-dst="前缀">前缀</trans><code><trans data-src="require()" data-dst="require()"><trans data-src="require()" data-dst="require()">require()</trans></trans></code><trans data-src=" statements,
or are automatically applied via regex from your webpack configuration." data-dst="报表，
或自动应用正则表达式你WebPACK通过。">报表，
或自动应用正则表达式你WebPACK通过。</trans></p>

<p><trans data-src="Please see " data-dst="请看">请看</trans><a href="https://webpack.github.io/docs/using-loaders.html"><trans data-src="Using Loaders" data-dst="用装载机">用装载机</trans></a><trans data-src=" for more information." data-dst="更多信息。">更多信息。</trans></p>

<p><strong><trans data-src="basic" data-dst="基本">基本</trans></strong></p>

<ul>
<li><a href="https://github.com/webpack/json-loader"><code><trans data-src="json" data-dst="JSON">JSON</trans></code></a><trans data-src=": Loads file as JSON" data-dst="：加载文件作为JSON">：加载文件作为JSON</trans></li>
<li><a href="https://github.com/webpack/raw-loader"><code><trans data-src="raw" data-dst="原">原</trans></code></a><trans data-src=": Loads raw content of a file (as utf-8)" data-dst="一个文件的原始内容：荷载（如UTF-8）">一个文件的原始内容：荷载（如UTF-8）</trans></li>
<li><a href="https://github.com/webpack/val-loader"><code><trans data-src="val" data-dst="瓦尔">瓦尔</trans></code></a><trans data-src=": Executes code as module and consider exports as JavaScript code" data-dst="：执行代码模块，考虑出口的JavaScript代码">：执行代码模块，考虑出口的JavaScript代码</trans></li>
<li><a href="https://github.com/webpack/script-loader"><code><trans data-src="script" data-dst="脚本">脚本</trans></code></a><trans data-src=": Executes a JavaScript file once in global context (like in script tag), requires are not parsed." data-dst="：一个JavaScript文件一旦在全局上下文中执行（如脚本标签），需要不被分析。">：一个JavaScript文件一旦在全局上下文中执行（如脚本标签），需要不被分析。</trans></li>
</ul>

<p><strong><trans data-src="packaging" data-dst="包装">包装</trans></strong></p>

<ul>
<li><a href="https://github.com/webpack/file-loader"><code><trans data-src="file" data-dst="文件">文件</trans></code></a><trans data-src=": Emits the file into the output folder and returns the (relative) url." data-dst="：将文件插入到输出文件夹并返回（相对）的URL。" style="background: transparent;">：将文件插入到输出文件夹并返回（相对）的URL。</trans></li>
<li><a href="https://github.com/webpack/url-loader"><code><trans data-src="url" data-dst="URL">URL</trans></code></a><trans data-src=": The url loader works like the file loader, but can return a Data Url if the file is smaller than a limit." data-dst="：URL装载机类似文件加载，但如果文件小于限制返回的数据的URL。">：URL装载机类似文件加载，但如果文件小于限制返回的数据的URL。</trans></li>
<li><a href="https://github.com/tcoopman/image-webpack-loader"><code><trans data-src="image" data-dst="图片">图片</trans></code></a><trans data-src=": Compresses your images. Ideal to use together with " data-dst="压缩你的图片。理想的配合使用">压缩你的图片。理想的配合使用</trans><code><trans data-src="file" data-dst="文件">文件</trans></code><trans data-src=" or " data-dst="或">或</trans><code><trans data-src="url" data-dst="URL">URL</trans></code><trans data-src="." data-dst="。">。</trans></li>
<li><a href="https://github.com/rpominov/svgo-loader"><code><trans data-src="svgo-loader" data-dst="svgo装载机">svgo装载机</trans></code></a><trans data-src=": Compresses SVG images using " data-dst="：压缩SVG图像使用">：压缩SVG图像使用</trans><a href="https://github.com/svg/svgo"><trans data-src="svgo" data-dst="svgo"><trans data-src="svgo" data-dst="svgo">svgo</trans></trans></a><trans data-src=" library" data-dst="图书馆">图书馆</trans></li>
<li><a href="https://github.com/deepsweet/baggage-loader"><code><trans data-src="baggage" data-dst="行李">行李</trans></code></a><trans data-src=": Automatically require any resources related to the required one" data-dst="：自动要求任何所需的相关资源">：自动要求任何所需的相关资源</trans></li>
<li><a href="https://github.com/JonDum/polymer-loader"><code><trans data-src="polymer-loader" data-dst="聚合物装载机">聚合物装载机</trans></code></a><trans data-src=": Process HTML &amp; CSS with preprocessor of choice and " data-dst="HTML和CSS：过程与预处理器的选择">HTML和CSS：过程与预处理器的选择</trans><code><trans data-src="require()" data-dst="require()"><trans data-src="require()" data-dst="require()">require()</trans></trans></code><trans data-src=" Web Components like first-class modules." data-dst="Web部件一级模块。">Web部件一级模块。</trans></li>
</ul>

<p><strong><trans data-src="dialects" data-dst="方言">方言</trans></strong></p>

<ul>
<li><a href="https://github.com/webpack/coffee-loader"><code><trans data-src="coffee" data-dst="咖啡">咖啡</trans></code></a><trans data-src=": Loads coffee-script like JavaScript" data-dst="咖啡：负载脚本如JavaScript">咖啡：负载脚本如JavaScript</trans></li>
<li><a href="https://github.com/babel/babel-loader"><code><trans data-src="babel" data-dst="巴别塔">巴别塔</trans></code></a><trans data-src=": Turn ES6 code into vanilla ES5 using " data-dst="：将6码到香草ES5使用">：将6码到香草ES5使用</trans><a href="https://github.com/babel/babel"><trans data-src="Babel" data-dst="巴别塔">巴别塔</trans></a><trans data-src="." data-dst="。">。</trans></li>
<li><a href="https://github.com/appedemic/livescript-loader"><code><trans data-src="livescript" data-dst="推荐">推荐</trans></code></a><trans data-src=": Loads LiveScript like JavaScript" data-dst="：负载LiveScript像JavaScript">：负载LiveScript像JavaScript</trans></li>
<li><a href="https://github.com/jlongster/sweetjs-loader"><code><trans data-src="sweetjs" data-dst="sweetjs"><trans data-src="sweetjs" data-dst="sweetjs">sweetjs</trans></trans></code></a><trans data-src=": Use sweetjs macros." data-dst="：使用sweetjs宏。">：使用sweetjs宏。</trans></li>
<li><a href="https://github.com/jupl/traceur-loader"><code><trans data-src="traceur" data-dst="traceur"><trans data-src="traceur" data-dst="traceur">traceur</trans></trans></code></a><trans data-src=": Use future JavaScript features with " data-dst="：用未来的JavaScript功能">：用未来的JavaScript功能</trans><a href="https://github.com/google/traceur-compiler"><trans data-src="Traceur" data-dst="练习者">练习者</trans></a><trans data-src="." data-dst="。">。</trans></li>
<li><a href="https://github.com/andreypopp/typescript-loader"><code><trans data-src="typescript" data-dst="打字稿">打字稿</trans></code></a><trans data-src=": Loads TypeScript like JavaScript." data-dst="他喜欢：加载JavaScript。">他喜欢：加载JavaScript。</trans></li>
</ul>

<p><strong><trans data-src="templating" data-dst="模板">模板</trans></strong></p>

<ul>
<li><a href="https://github.com/webpack/html-loader"><code><trans data-src="html" data-dst="HTML">HTML</trans></code></a><trans data-src=": Exports HTML as string, require references to static resources." data-dst="：出口的HTML字符串，需要引用的静态资源。">：出口的HTML字符串，需要引用的静态资源。</trans></li>
<li><a href="https://github.com/webpack/jade-loader"><code><trans data-src="jade" data-dst="玉">玉</trans></code></a><trans data-src=": Loads jade template and returns a function" data-dst="玉：荷载模板并返回一个函数">玉：荷载模板并返回一个函数</trans></li>
<li><a href="https://github.com/altano/handlebars-loader"><code><trans data-src="handlebars" data-dst="车把">车把</trans></code></a><trans data-src=": Loads handlebars template and returns a function" data-dst="车把：荷载模板并返回一个函数">车把：荷载模板并返回一个函数</trans></li>
<li><a href="https://github.com/rstacruz/ractive-loader"><code><trans data-src="ractive" data-dst="反应">反应</trans></code></a><trans data-src=": Pre-compiles Ractive templates for interactive DOM manipulation" data-dst="事件：预编译模板交互的DOM操作">事件：预编译模板交互的DOM操作</trans></li>
<li><a href="https://github.com/peerigon/markdown-loader"><code><trans data-src="markdown" data-dst="降价">降价</trans></code></a><trans data-src=": Compiles Markdown to HTML" data-dst="compiles markdown to HTML。">compiles markdown to HTML。</trans></li>
<li><a href="https://github.com/teux/ng-cache-loader"><code><trans data-src="ng-cache" data-dst="天然气藏">天然气藏</trans></code></a><trans data-src=": Puts HTML partials in the Angular's $templateCache" data-dst="：把HTML部分在角的templatecache美元">：把HTML部分在角的templatecache美元</trans></li>
</ul>

<p><strong><trans data-src="styling" data-dst="款式">款式</trans></strong></p>

<ul>
<li><a href="https://github.com/webpack/style-loader"><code><trans data-src="style" data-dst="风格">风格</trans></code></a><trans data-src=": Add exports of a module as style to DOM" data-dst="：添加一个模块的出口方式DOM">：添加一个模块的出口方式DOM</trans></li>
<li><a href="https://github.com/webpack/css-loader"><code><trans data-src="css" data-dst="CSS">CSS</trans></code></a><trans data-src=": Loads css file with resolved imports and returns css code" data-dst="：加载CSS文件解决进口和返回的CSS代码">：加载CSS文件解决进口和返回的CSS代码</trans></li>
<li><a href="https://github.com/MoOx/cssnext-loader"><code><trans data-src="cssnext" data-dst="cssnext"><trans data-src="cssnext" data-dst="cssnext">cssnext</trans></trans></code></a><trans data-src=": Loads and compiles a css file using " data-dst="：加载和编译一个CSS文件的使用">：加载和编译一个CSS文件的使用</trans><a href="http://cssnext.io/"><trans data-src="cssnext" data-dst="cssnext"><trans data-src="cssnext" data-dst="cssnext">cssnext</trans></trans></a></li>
<li><a href="https://github.com/webpack/less-loader"><code><trans data-src="less" data-dst="少">少</trans></code></a><trans data-src=": Loads and compiles a less file" data-dst="：加载和编译一个小文件">：加载和编译一个小文件</trans></li>
<li><a href="https://github.com/jtangelder/sass-loader"><code><trans data-src="sass" data-dst="萨斯">萨斯</trans></code></a><trans data-src=": Loads and compiles a scss file" data-dst="：加载和编译一个说明文件">：加载和编译一个说明文件</trans></li>
<li><a href="https://github.com/shama/stylus-loader"><code><trans data-src="stylus" data-dst="触控笔">触控笔</trans></code></a><trans data-src=": Loads and compiles a stylus file" data-dst="：加载和编译一个手写的文件">：加载和编译一个手写的文件</trans></li>
</ul>

<p><strong><trans data-src="misc" data-dst="其他">其他</trans></strong></p>

<ul>
<li><a href="https://github.com/perchlayer/po-loader"><code><trans data-src="po" data-dst="宝">宝</trans></code></a><trans data-src=": Loads a PO gettext file and returns JSON" data-dst="：加载一个PO gettext文件并返回JSON">：加载一个PO gettext文件并返回JSON</trans></li>
<li><a href="https://github.com/webpack/mocha-loader"><code><trans data-src="mocha" data-dst="摩卡">摩卡</trans></code></a><trans data-src=": Do tests with mocha in browser or node.js" data-dst="：在浏览器或Node.js摩卡做试验">：在浏览器或Node.js摩卡做试验</trans></li>
<li><a href="https://github.com/MoOx/eslint-loader"><code><trans data-src="eslint" data-dst="ESLint">ESLint</trans></code></a><trans data-src=": PreLoader for linting code using ESLint." data-dst="落絮ESLint预加载代码使用。">落絮ESLint预加载代码使用。</trans></li>
<li><a href="https://github.com/webpack/jshint-loader"><code><trans data-src="jshint" data-dst="jshint"><trans data-src="jshint" data-dst="jshint">jshint</trans></trans></code></a><trans data-src=": PreLoader for linting code." data-dst="：掉毛的代码加载。">：掉毛的代码加载。</trans></li>
<li><a href="https://github.com/unindented/jscs-loader"><code><trans data-src="jscs" data-dst="股份合作制">股份合作制</trans></code></a><trans data-src=": PreLoader for style checking." data-dst="检查：预载for风格。">检查：预载for风格。</trans></li>
<li><a href="https://github.com/jauco/webpack-injectable"><code><trans data-src="injectable" data-dst="注射">注射</trans></code></a><trans data-src=": Allow to inject dependencies into modules" data-dst="：允许注入依赖的模块">：允许注入依赖的模块</trans></li>
<li><a href="https://github.com/webpack/transform-loader"><code><trans data-src="transform" data-dst="变换">变换</trans></code></a><trans data-src=": Use browserify transforms as loader." data-dst="：使用browserify转化为装载机。">：使用browserify转化为装载机。</trans></li>
</ul>

<p><trans data-src="For the full list of loaders, see " data-dst="装载机的完整列表，参见">装载机的完整列表，参见</trans><a href="https://webpack.github.io/docs/list-of-loaders.html"><trans data-src="list of loaders" data-dst="系列装载机">系列装载机</trans></a><trans data-src="." data-dst="。">。</trans></p>

<h2><a id="user-content-module-format-amdcommonjs" class="anchor" href="#module-format-amdcommonjs" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Module Format (AMD/CommonJS)" data-dst="模块的格式（AMD / CommonJS）">模块的格式（AMD / CommonJS）</trans></h2>

<p><trans data-src="webpack supports " data-dst="WebPACK的支持">WebPACK的支持</trans><strong><trans data-src="both" data-dst="两">两</trans></strong><trans data-src=" AMD and CommonJS module styles. It performs clever static
analysis on the AST of your code. It even has an evaluation engine to evaluate
simple expressions. This allows you to " data-dst="AMD和CommonJS模块样式。它执行你的代码的静态分析
 AST聪明。它甚至有评价
简单表达式评估引擎。这允许你">AMD和CommonJS模块样式。它执行你的代码的静态分析
 AST聪明。它甚至有评价
简单表达式评估引擎。这允许你</trans><strong><trans data-src="support most existing libraries" data-dst="支持大多数现有的图书馆">支持大多数现有的图书馆</trans></strong><trans data-src=" out of the box." data-dst="开箱。">开箱。</trans></p>

<h2><a id="user-content-code-splitting" class="anchor" href="#code-splitting" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Code Splitting" data-dst="代码分裂">代码分裂</trans></h2>

<p><trans data-src="webpack allows you to split your codebase into multiple chunks. Chunks are
loaded asynchronously at runtime. This reduces the initial loading time." data-dst="WebPACK允许你将代码分成多个块。块
时异步加载。这降低了初始加载时间。">WebPACK允许你将代码分成多个块。块
时异步加载。这降低了初始加载时间。</trans></p>

<p><a href="https://webpack.github.io/docs/code-splitting.html"><trans data-src="Code Splitting documentation" data-dst="代码分割文件">代码分割文件</trans></a></p>

<h2><a id="user-content-optimizations" class="anchor" href="#optimizations" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Optimizations" data-dst="优化">优化</trans></h2>

<p><trans data-src="webpack can do many optimizations to " data-dst="WebPACK可以做很多优化">WebPACK可以做很多优化</trans><strong><trans data-src="reduce the output size of your
JavaScript" data-dst="减少你的
 JavaScript输出的大小">减少你的
 JavaScript输出的大小</trans></strong><trans data-src=" by deduplicating frequently used modules, minifying, and giving
you full control of what is loaded initially and what is loaded at runtime
through code splitting. It can also can make your code chunks " data-dst="通过重复数据删除的常用模块，修正，并给出初步的和什么是什么是负载在运行时加载
通过代码分裂
你完全控制。它也可以使你的代码块">通过重复数据删除的常用模块，修正，并给出初步的和什么是什么是负载在运行时加载
通过代码分裂
你完全控制。它也可以使你的代码块</trans><strong><trans data-src="cache
friendly" data-dst="
缓存友好">
缓存友好</trans></strong><trans data-src=" by using hashes." data-dst="通过使用散列。">通过使用散列。</trans></p>

<p><a href="https://webpack.github.io/docs/optimization.html"><trans data-src="Optimization documentation" data-dst="优化文件">优化文件</trans></a></p>

<h1><a id="user-content-a-small-example-of-whats-possible" class="anchor" href="#a-small-example-of-whats-possible" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="A small example of what's possible" data-dst="什么是可能的一个小例子">什么是可能的一个小例子</trans></h1>

<div class="highlight highlight-source-js"><pre><span class="pl-c"><trans data-src="// webpack is a module bundler." data-dst="/ / WebPACK是模块式。">/ / WebPACK是模块式。</trans></span>
<span class="pl-c"><trans data-src="// This means webpack takes modules with dependencies" data-dst="/这意味着WebPACK以模块的依赖关系">/这意味着WebPACK以模块的依赖关系</trans></span>
<span class="pl-c"><trans data-src="// and emits static assets representing those modules." data-dst="/ /发出静态资产代表这些模块。">/ /发出静态资产代表这些模块。</trans></span>

<span class="pl-c"><trans data-src="// Dependencies can be written in CommonJs" data-dst="/ /依赖关系可以用CommonJS">/ /依赖关系可以用CommonJS</trans></span>
<span class="pl-k"><trans data-src="var" data-dst="VaR">VaR</trans></span><trans data-src=" commonjs " data-dst="CommonJS">CommonJS</trans><span class="pl-k">=</span> <span class="pl-c1"><trans data-src="require" data-dst="要求">要求</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="./commonjs" data-dst="CommonJS。/">CommonJS。/</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span><trans data-src=");
" data-dst="）；">）；</trans><span class="pl-c"><trans data-src="// or in AMD" data-dst="AMD和/或">AMD和/或</trans></span>
<span class="pl-en"><trans data-src="define" data-dst="定义">定义</trans></span><trans data-src="([" data-dst="（[">（[</trans><span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="amd-module" data-dst="AMD的模块">AMD的模块</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span><trans data-src=", " data-dst="，">，</trans><span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="../file" data-dst="文件">文件</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span><trans data-src="], " data-dst="]，">]，</trans><span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" (" data-dst="（">（</trans><span class="pl-smi"><trans data-src="amdModule" data-dst="amdmodule">amdmodule</trans></span><trans data-src=", " data-dst="，">，</trans><span class="pl-smi"><trans data-src="file" data-dst="文件">文件</trans></span><trans data-src=") {
    " data-dst="）{">）{</trans><span class="pl-c"><trans data-src="// while previous constructs are sync," data-dst="/虽然以前的构造同步，">/虽然以前的构造同步，</trans></span>
    <span class="pl-c"><trans data-src="// this is async" data-dst="/这是一个异步">/这是一个异步</trans></span>
    <span class="pl-c1"><trans data-src="require" data-dst="要求">要求</trans></span><trans data-src="([" data-dst="（[">（[</trans><span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="big-module/big/file" data-dst="大/大/模文件">大/大/模文件</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span><trans data-src="], " data-dst="]，">]，</trans><span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" (" data-dst="（">（</trans><span class="pl-smi"><trans data-src="big" data-dst="大">大</trans></span><trans data-src=") {
         " data-dst="）{">）{</trans><span class="pl-c"><trans data-src="// For async dependencies, webpack splits" data-dst="/ /异步依赖WebPACK分裂">/ /异步依赖WebPACK分裂</trans></span>
         <span class="pl-c"><trans data-src="// your application into multiple " chunks"."="" data-dst="/ /应用程序分成多个“块”。">/ /应用程序分成多个“块”。</trans></span>
         <span class="pl-c"><trans data-src="// This part of your application is" data-dst="/你的这部分的应用">/你的这部分的应用</trans></span>
         <span class="pl-c"><trans data-src="// loaded on demand (code-splitting)." data-dst="我们需求/加载代码（分）。">我们需求/加载代码（分）。</trans></span>
        <span class="pl-k"><trans data-src="var" data-dst="VaR">VaR</trans></span><trans data-src=" stuff " data-dst="东西">东西</trans><span class="pl-k">=</span> <span class="pl-c1"><trans data-src="require" data-dst="要求">要求</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="../my/stuff" data-dst="我的/我的/。">我的/我的/。</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span><trans data-src=");
        " data-dst="）；">）；</trans><span class="pl-c"><trans data-src="// " ..="" my="" stuff"="" is="" also="" loaded="" on-demand"="" data-dst="/ / /我的/东西”也是按需加载">/ / /我的/东西”也是按需加载</trans></span>
        <span class="pl-c"><trans data-src="//  because it's in the callback function" data-dst="/ /因为它在回调函数">/ /因为它在回调函数</trans></span>
        <span class="pl-c"><trans data-src="//  of the AMD require." data-dst="/ / AMD的要求。">/ / AMD的要求。</trans></span><trans data-src="
    });
});


" data-dst="
 }）}）；">
 }）}）；</trans><span class="pl-c1"><trans data-src="require" data-dst="要求">要求</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="coffee!./cup.coffee" data-dst="咖啡！cup.coffee。/">咖啡！cup.coffee。/</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span><trans data-src=");
" data-dst="）；">）；</trans><span class="pl-c"><trans data-src="// " loaders"="" are="" used="" to="" preprocess="" files."="" data-dst="/“装载机”是用来处理文件。">/“装载机”是用来处理文件。</trans></span>
<span class="pl-c"><trans data-src="// They can be prefixed in the require call" data-dst="/ /他们可以在需要调用前缀">/ /他们可以在需要调用前缀</trans></span>
<span class="pl-c"><trans data-src="// or configured in the configuration." data-dst="/ /或配置中的配置。">/ /或配置中的配置。</trans></span>
<span class="pl-c1"><trans data-src="require" data-dst="要求">要求</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="./cup" data-dst="杯子">杯子</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span><trans data-src=");
" data-dst="）；">）；</trans><span class="pl-c"><trans data-src="// This does the same when you add " .coffee"="" to="" the="" extensions"="" data-dst="//这也是当你添加“咖啡”的扩展">//这也是当你添加“咖啡”的扩展</trans></span>
<span class="pl-c"><trans data-src="// and configure the " coffee"="" loader="" for="" \.coffee$="" "="" data-dst="/ /配置/ \“咖啡”咖啡美元/装载机。">/ /配置/ \“咖啡”咖啡美元/装载机。</trans></span>

<span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span> <span class="pl-en"><trans data-src="loadTemplate" data-dst="LoadTemplate">LoadTemplate</trans></span><trans data-src=" (" data-dst="（">（</trans><span class="pl-smi"><trans data-src="name" data-dst="姓名">姓名</trans></span><trans data-src=") {
    " data-dst="）{">）{</trans><span class="pl-k"><trans data-src="return" data-dst="退货">退货</trans></span> <span class="pl-c1"><trans data-src="require" data-dst="要求">要求</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="./templates/" data-dst="/模板/。">/模板/。</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-k"><trans data-src="+" data-dst=" "> </trans></span><trans data-src=" name " data-dst="姓名">姓名</trans><span class="pl-k"><trans data-src="+" data-dst=" "> </trans></span> <span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src=".jade" data-dst="。玉">。玉</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span><trans data-src=");
    " data-dst="）；">）；</trans><span class="pl-c"><trans data-src="// Many expressions are supported in require calls." data-dst="/ /许多表达支持需要调用。">/ /许多表达支持需要调用。</trans></span>
    <span class="pl-c"><trans data-src="// A clever parser extracts information and concludes" data-dst="/ /聪明的分析器提取信息并得出结论">/ /聪明的分析器提取信息并得出结论</trans></span>
    <span class="pl-c"><trans data-src="// that everything in " .="" templates"="" that="" matches"="" data-dst="/ /一切”。/模板匹配">/ /一切”。/模板匹配</trans></span>
    <span class="pl-c"><trans data-src="// /\.jade$/ should be included in the bundle, as it" data-dst="/ / / \。玉美元/应包括捆绑，它">/ / / \。玉美元/应包括捆绑，它</trans></span>
    <span class="pl-c"><trans data-src="// can be required." data-dst="/ /可以要求。">/ /可以要求。</trans></span><trans data-src="
}


" data-dst="}">}</trans><span class="pl-c"><trans data-src="// ...and you can combine everything." data-dst="//…你可以把一切。">//…你可以把一切。</trans></span>
<span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span> <span class="pl-en"><trans data-src="loadTemplateAsync" data-dst="loadtemplateasync">loadtemplateasync</trans></span><trans data-src=" (" data-dst="（">（</trans><span class="pl-smi"><trans data-src="name" data-dst="姓名">姓名</trans></span><trans data-src=", " data-dst="，">，</trans><span class="pl-smi"><trans data-src="callback" data-dst="回调">回调</trans></span><trans data-src=") {
    " data-dst="）{">）{</trans><span class="pl-c1"><trans data-src="require" data-dst="要求">要求</trans></span><trans data-src="([" data-dst="（[">（[</trans><span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="bundle?lazy!./templates/" data-dst="束懒惰！模板">束懒惰！模板</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-k"><trans data-src="+" data-dst=" "> </trans></span><trans data-src=" name " data-dst="姓名">姓名</trans><span class="pl-k"><trans data-src="+" data-dst=" "> </trans></span> <span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src=".jade" data-dst="。玉">。玉</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span><trans data-src="],
      " data-dst="]，">]，</trans><span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" (" data-dst="（">（</trans><span class="pl-smi"><trans data-src="templateBundle" data-dst="templatebundle">templatebundle</trans></span><trans data-src=") {
              " data-dst="）{">）{</trans><span class="pl-en"><trans data-src="templateBundle" data-dst="templatebundle">templatebundle</trans></span><trans data-src="(callback);
    });
}" data-dst="（回调）；}）；
 
">（回调）；}）；
 
</trans></pre></div>

<h2><a id="user-content-documentation" class="anchor" href="#documentation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Documentation" data-dst="文档">文档</trans></h2>

<p><a href="https://webpack.github.io/docs/?utm_source=github&amp;utm_medium=readme&amp;utm_campaign=documentation"><trans data-src="documentation" data-dst="文档">文档</trans></a></p>

<h2><a id="user-content-changelog" class="anchor" href="#changelog" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Changelog" data-dst="更新日志">更新日志</trans></h2>

<p><a href="https://webpack.github.io/docs/changelog.html"><trans data-src="changelog" data-dst="更新日志">更新日志</trans></a></p>

<h2><a id="user-content-tests" class="anchor" href="#tests" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Tests" data-dst="测试">测试</trans></h2>

<p><trans data-src="You can run the Node tests with " data-dst="你可以运行节点试验">你可以运行节点试验</trans><code><trans data-src="npm test" data-dst="NPM试验">NPM试验</trans></code><trans data-src="." data-dst="。">。</trans></p>

<p><trans data-src="You can run the browser tests:" data-dst="你可以运行浏览器测试：">你可以运行浏览器测试：</trans></p>

<pre><code><trans data-src="cd test/browsertests
node build
" data-dst="测试/ browsertests 
节点建立">测试/ browsertests 
节点建立</trans></code></pre>

<p><trans data-src="and open " data-dst="开放">开放</trans><code><trans data-src="tests.html" data-dst="tests.html"><trans data-src="tests.html" data-dst="tests.html">tests.html</trans></trans></code><trans data-src=" in the browser." data-dst="在浏览器。">在浏览器。</trans></p>

<h2><a id="user-content-contribution" class="anchor" href="#contribution" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Contribution" data-dst="的贡献">的贡献</trans></h2>

<p><trans data-src="Most of the time, if webpack is not working correctly for you it is a simple configuration issue." data-dst="大多数时候，如果WebPACK工作不正常的你这是一个简单的配置问题。">大多数时候，如果WebPACK工作不正常的你这是一个简单的配置问题。</trans></p>

<p><trans data-src="If you are still having difficulty after looking over your configuration carefully, please post
a question to " data-dst="如果你还是在寻找你的配置仔细有困难，请
问题">如果你还是在寻找你的配置仔细有困难，请
问题</trans><a href="http://stackoverflow.com/tags/webpack"><trans data-src="StackOverflow with the webpack tag" data-dst="随着WebPACK标签计算器">随着WebPACK标签计算器</trans></a><trans data-src=". Questions
that include your webpack.config.js and relevant files are more likely to receive responses." data-dst="。问题
，包括你的webpack.config.js和有关文件更容易接收响应。">。问题
，包括你的webpack.config.js和有关文件更容易接收响应。</trans></p>

<p><trans data-src="If you have discovered a bug or have a feature suggestion, feel free to create an issue on Github." data-dst="如果你发现了一个bug或功能的建议，随时创建一个发布在GitHub上。">如果你发现了一个bug或功能的建议，随时创建一个发布在GitHub上。</trans></p>

<p><trans data-src="If you create a loader or plugin, please consider open sourcing it, putting it
on NPM and following the " data-dst="如果你创建一个程序或插件，请考虑开源，把它
 NPM与继">如果你创建一个程序或插件，请考虑开源，把它
 NPM与继</trans><code><trans data-src="x-loader" data-dst="x-loader"><trans data-src="x-loader" data-dst="x-loader">x-loader</trans></trans></code><trans data-src=", " data-dst="，">，</trans><code><trans data-src="x-plugin" data-dst="x-plugin"><trans data-src="x-plugin" data-dst="x-plugin">x-plugin</trans></trans></code><trans data-src=" convention." data-dst="公约">公约</trans></p>

<p><trans data-src="You are also welcome to correct any spelling mistakes or any language issues." data-dst="也欢迎你纠正拼写错误或任何语言问题。">也欢迎你纠正拼写错误或任何语言问题。</trans></p>

<p><trans data-src="If you want to discuss something or just need help, " data-dst="如果你想讨论的东西还是需要帮助，">如果你想讨论的东西还是需要帮助，</trans><a href="https://gitter.im/webpack/webpack"><trans data-src="here is our gitter.im room" data-dst="这是我们的gitter.im室">这是我们的gitter.im室</trans></a><trans data-src="." data-dst="。">。</trans></p>

<h2><a id="user-content-license" class="anchor" href="#license" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="License" data-dst="许可证">许可证</trans></h2>

<p><trans data-src="Copyright (c) 2012-2016 Tobias Koppers" data-dst="版权所有（C）中，2012年至2016年。">版权所有（C）中，2012年至2016年。</trans></p>

<p><trans data-src="MIT (" data-dst="与（">与（</trans><a href="http://opensource.org/licenses/mit-license.php"><trans data-src="http://opensource.org/licenses/mit-license.php" data-dst="opensource.org http：/ / / / mit-license.php许可证">opensource.org http：/ / / / mit-license.php许可证</trans></a><trans data-src=")" data-dst="）">）</trans></p>

<h2><a id="user-content-thanks-to" class="anchor" href="#thanks-to" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Thanks to" data-dst="感谢">感谢</trans></h2>

<p><trans data-src="(In chronological order)" data-dst="（按时间顺序）">（按时间顺序）</trans></p>

<ul>
<li><trans data-src="@google for " data-dst="@谷歌">@谷歌</trans><a href="https://code.google.com/archive/p/google-web-toolkit"><trans data-src="Google Web Toolkit (GWT)" data-dst="谷歌网页工具包（GWT）">谷歌网页工具包（GWT）</trans></a><trans data-src=", which aims to compile Java to JavaScript. It features a similar " data-dst="，其目的是java编译JavaScript。它具有一个类似">，其目的是java编译JavaScript。它具有一个类似</trans><a href="https://code.google.com/archive/p/google-web-toolkit/wikis/CodeSplitting.wiki"><trans data-src="Code Splitting" data-dst="代码分裂">代码分裂</trans></a><trans data-src=" as webpack." data-dst="作为WebPACK。">作为WebPACK。</trans></li>
<li><trans data-src="@medikoo for " data-dst="“medikoo为">“medikoo为</trans><a href="https://github.com/medikoo/modules-webmake"><trans data-src="modules-webmake" data-dst="模块webmake">模块webmake</trans></a><trans data-src=", which is a similar project. webpack was born because I wanted Code Splitting for modules-webpack. Interestingly the " data-dst="这是一个类似的项目。是因为我想在模块WebPACK WebPACK代码分裂出生。有趣的是，">这是一个类似的项目。是因为我想在模块WebPACK WebPACK代码分裂出生。有趣的是，</trans><a href="https://github.com/medikoo/modules-webmake/issues/7"><trans data-src="Code Splitting issue is still open" data-dst="代码分裂的问题仍然是开放的">代码分裂的问题仍然是开放的</trans></a><trans data-src=" (thanks also to @Phoscur for the discussion)." data-dst="（感谢@ phoscur的讨论）。">（感谢@ phoscur的讨论）。</trans></li>
<li><trans data-src="@substack for " data-dst="@方子为">@方子为</trans><a href="http://browserify.org/"><trans data-src="browserify" data-dst="browserify"><trans data-src="browserify" data-dst="browserify">browserify</trans></trans></a><trans data-src=", which is a similar project and source for many ideas." data-dst="这是一个类似的项目，和许多想法的来源。">这是一个类似的项目，和许多想法的来源。</trans></li>
<li><trans data-src="@jrburke for " data-dst="“jrburke为">“jrburke为</trans><a href="http://requirejs.org/"><trans data-src="require.js" data-dst="require.js"><trans data-src="require.js" data-dst="require.js">require.js</trans></trans></a><trans data-src=", which is a similar project and source for many ideas." data-dst="这是一个类似的项目，和许多想法的来源。">这是一个类似的项目，和许多想法的来源。</trans></li>
<li><trans data-src="@defunctzombie for the " data-dst="为defunctzombie @">为defunctzombie @</trans><a href="https://gist.github.com/defunctzombie/4339901"><trans data-src="browser-field spec" data-dst="浏览器领域的规格">浏览器领域的规格</trans></a><trans data-src=", which makes modules available for node.js, browserify and webpack." data-dst="，使模块可用于Node.js，browserify和WebPACK。">，使模块可用于Node.js，browserify和WebPACK。</trans></li>
<li><trans data-src="Every early webpack user, which contributed to webpack by writing issues or PRs. You influenced the direction..." data-dst="每早WebPACK用户，这有助于通过写作问题或PRS WebPACK。你的影响方向…">每早WebPACK用户，这有助于通过写作问题或PRS WebPACK。你的影响方向…</trans></li>
<li><trans data-src="@shama, @jhnns and @sokra for maintaining this project" data-dst="@ @ @莎玛，jhnns和维持项目索克拉">@ @ @莎玛，jhnns和维持项目索克拉</trans></li>
<li><trans data-src="Everyone who has written a loader for webpack. You are the ecosystem..." data-dst="每个人都写了一个装载机WebPACK。你的生态系统…">每个人都写了一个装载机WebPACK。你的生态系统…</trans></li>
<li><trans data-src="Everyone I forgot to mention here, but also influenced webpack." data-dst="我忘了说，还影响WebPACK。">我忘了说，还影响WebPACK。</trans></li>
</ul>

<h2><a id="user-content-sponsor" class="anchor" href="#sponsor" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Sponsor" data-dst="赞助商">赞助商</trans></h2>

<p><trans data-src="This is a free-time project. The time I invest in it fluctuates. If you use webpack for a serious task, and you'd like me to invest more time on it, please donate. This project increases your income/productivity too. It makes development and applications faster and it reduces the required bandwidth." data-dst="这是一个免费的项目。我在这方面投资的时间波动。如果你使用一个严肃WebPACK的任务，你要我投入更多的时间，请捐赠。这个项目可以增加你的收入/生产率。它的发展和应用的速度，减少了所需的带宽。">这是一个免费的项目。我在这方面投资的时间波动。如果你使用一个严肃WebPACK的任务，你要我投入更多的时间，请捐赠。这个项目可以增加你的收入/生产率。它的发展和应用的速度，减少了所需的带宽。</trans></p>

<p><trans data-src="I'm very thankful for every dollar. If you leave your username or email, I may show my thanks by giving you extra support." data-dst="我非常感谢每一个美元。如果你离开你的用户名或电子邮件，我会给你额外的支持表示我的感谢。">我非常感谢每一个美元。如果你离开你的用户名或电子邮件，我会给你额外的支持表示我的感谢。</trans></p>

<h2><a id="user-content-dependencies" class="anchor" href="#dependencies" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Dependencies" data-dst="依赖">依赖</trans></h2>

<ul>
<li><a href="http://esprima.org/"><trans data-src="esprima" data-dst="Esprima">Esprima</trans></a></li>
<li><a href="https://github.com/webpack/enhanced-resolve"><trans data-src="enhanced-resolve" data-dst="增强解决">增强解决</trans></a></li>
<li><a href="https://github.com/mishoo/UglifyJS"><trans data-src="uglify-js" data-dst="JS丑化">JS丑化</trans></a></li>
<li><a href="https://github.com/mochajs/mocha"><trans data-src="mocha" data-dst="摩卡">摩卡</trans></a></li>
<li><a href="https://github.com/tj/should.js"><trans data-src="should" data-dst="应">应</trans></a></li>
<li><a href="https://github.com/substack/node-optimist"><trans data-src="optimist" data-dst="乐观主义者">乐观主义者</trans></a></li>
<li><a href="https://github.com/caolan/async"><trans data-src="async" data-dst="异步">异步</trans></a></li>
<li><a href="https://github.com/substack/node-mkdirp"><trans data-src="mkdirp" data-dst="mkdirp"><trans data-src="mkdirp" data-dst="mkdirp">mkdirp</trans></trans></a></li>
<li><a href="https://github.com/pvorb/node-clone"><trans data-src="clone" data-dst="克隆">克隆</trans></a></li>
</ul>
</article>
##EN
[![webpack](https://webpack.github.io/assets/logo.png)](https://webpack.github.io)


[![NPM version][npm-image]][npm-url] [![Gitter chat][gitter-image]][gitter-url] [![Downloads][downloads-image]][downloads-url]

[![NPM][nodei-image]][nodei-url]

build
[![Build Status][travis-image]][travis-url] [![Appveyor Status][appveyor-image]][appveyor-url]  [![Coverage Status][coveralls-image]][coveralls-url]

dependencies
[![Dependency Status][david-image]][david-url] [![devDependency Status][david-dev-image]][david-dev-url] [![peerDependency Status][david-peer-image]][david-peer-url]

donation
[![gratipay donate button][gratipay-image]][gratipay-url] [![Donate to sokra][donate-image]][donate-url]

[![BADGINATOR][badginator-image]][badginator-url]

[documentation](https://webpack.github.io/docs/?utm_source=github&utm_medium=readme&utm_campaign=top)

# Introduction

webpack is a bundler for modules. The main purpose is to bundle JavaScript
files for usage in a browser, yet it is also capable of transforming, bundling,
or packaging just about any resource or asset.


**TL; DR**

* Bundles both [CommonJs](http://wiki.commonjs.org/) and [AMD](https://github.com/amdjs/amdjs-api/wiki/AMD) modules (even combined).
* Can create a single bundle or multiple chunks that are asynchronously loaded at runtime (to reduce initial loading time).
* Dependencies are resolved during compilation reducing the runtime size.
* Loaders can preprocess files while compiling, e.g. coffeescript to JavaScript, handlebars strings to compiled functions, images to Base64, etc.
* Highly modular plugin system to do whatever else your application requires.

# Getting Started

Check out webpack's [documentation](https://webpack.github.io/docs/?utm_source=github&utm_medium=readme&utm_campaign=trdr) for quick Getting Started guide, in-depth usage,
tutorials and resources.

# Installation

project:
`npm install webpack --save-dev`

global:
`npm install webpack -g`

Usage:
https://webpack.github.io/docs/tutorials/getting-started/

# Examples

Take a look at the [`examples`](https://github.com/webpack/webpack/tree/master/examples) folder.

# Features

## Plugins

webpack has a [rich plugin
interface](https://webpack.github.io/docs/plugins.html). Most of the features
within webpack itself use this plugin interface. This makes webpack very
**flexible**.


## Performance

webpack uses async I/O and has multiple caching levels. This makes webpack fast
and incredibly **fast** on incremental compilations.

## Loaders

webpack enables use of loaders to preprocess files. This allows you to bundle
**any static resource** way beyond JavaScript. You can easily [write your own
loaders](https://webpack.github.io/docs/loaders.html) using node.js.

Loaders are activated by using `loadername!` prefixes in `require()` statements,
or are automatically applied via regex from your webpack configuration.

Please see [Using Loaders](https://webpack.github.io/docs/using-loaders.html) for more information.

**basic**
* [`json`](https://github.com/webpack/json-loader): Loads file as JSON
* [`raw`](https://github.com/webpack/raw-loader): Loads raw content of a file (as utf-8)
* [`val`](https://github.com/webpack/val-loader): Executes code as module and consider exports as JavaScript code
* [`script`](https://github.com/webpack/script-loader): Executes a JavaScript file once in global context (like in script tag), requires are not parsed.

**packaging**
* [`file`](https://github.com/webpack/file-loader): Emits the file into the output folder and returns the (relative) url.
* [`url`](https://github.com/webpack/url-loader): The url loader works like the file loader, but can return a Data Url if the file is smaller than a limit.
* [`image`](https://github.com/tcoopman/image-webpack-loader): Compresses your images. Ideal to use together with `file` or `url`.
* [`svgo-loader`](https://github.com/rpominov/svgo-loader): Compresses SVG images using [svgo](https://github.com/svg/svgo) library
* [`baggage`](https://github.com/deepsweet/baggage-loader): Automatically require any resources related to the required one
* [`polymer-loader`](https://github.com/JonDum/polymer-loader): Process HTML & CSS with preprocessor of choice and `require()` Web Components like first-class modules.

**dialects**
* [`coffee`](https://github.com/webpack/coffee-loader): Loads coffee-script like JavaScript
* [`babel`](https://github.com/babel/babel-loader): Turn ES6 code into vanilla ES5 using [Babel](https://github.com/babel/babel).
* [`livescript`](https://github.com/appedemic/livescript-loader): Loads LiveScript like JavaScript
* [`sweetjs`](https://github.com/jlongster/sweetjs-loader): Use sweetjs macros.
* [`traceur`](https://github.com/jupl/traceur-loader): Use future JavaScript features with [Traceur](https://github.com/google/traceur-compiler).
* [`typescript`](https://github.com/andreypopp/typescript-loader): Loads TypeScript like JavaScript.

**templating**
* [`html`](https://github.com/webpack/html-loader): Exports HTML as string, require references to static resources.
* [`jade`](https://github.com/webpack/jade-loader): Loads jade template and returns a function
* [`handlebars`](https://github.com/altano/handlebars-loader): Loads handlebars template and returns a function
* [`ractive`](https://github.com/rstacruz/ractive-loader): Pre-compiles Ractive templates for interactive DOM manipulation
* [`markdown`](https://github.com/peerigon/markdown-loader): Compiles Markdown to HTML
* [`ng-cache`](https://github.com/teux/ng-cache-loader): Puts HTML partials in the Angular's $templateCache

**styling**
* [`style`](https://github.com/webpack/style-loader): Add exports of a module as style to DOM
* [`css`](https://github.com/webpack/css-loader): Loads css file with resolved imports and returns css code
* [`cssnext`](https://github.com/MoOx/cssnext-loader): Loads and compiles a css file using [cssnext](http://cssnext.io/)
* [`less`](https://github.com/webpack/less-loader): Loads and compiles a less file
* [`sass`](https://github.com/jtangelder/sass-loader): Loads and compiles a scss file
* [`stylus`](https://github.com/shama/stylus-loader): Loads and compiles a stylus file

**misc**
* [`po`](https://github.com/perchlayer/po-loader): Loads a PO gettext file and returns JSON
* [`mocha`](https://github.com/webpack/mocha-loader): Do tests with mocha in browser or node.js
* [`eslint`](https://github.com/MoOx/eslint-loader): PreLoader for linting code using ESLint.
* [`jshint`](https://github.com/webpack/jshint-loader): PreLoader for linting code.
* [`jscs`](https://github.com/unindented/jscs-loader): PreLoader for style checking.
* [`injectable`](https://github.com/jauco/webpack-injectable): Allow to inject dependencies into modules
* [`transform`](https://github.com/webpack/transform-loader): Use browserify transforms as loader.

For the full list of loaders, see [list of loaders](https://webpack.github.io/docs/list-of-loaders.html).

## Module Format (AMD/CommonJS)

webpack supports **both** AMD and CommonJS module styles. It performs clever static
analysis on the AST of your code. It even has an evaluation engine to evaluate
simple expressions. This allows you to **support most existing libraries** out of the box.

## Code Splitting

webpack allows you to split your codebase into multiple chunks. Chunks are
loaded asynchronously at runtime. This reduces the initial loading time.

[Code Splitting documentation](https://webpack.github.io/docs/code-splitting.html)

## Optimizations

webpack can do many optimizations to **reduce the output size of your
JavaScript** by deduplicating frequently used modules, minifying, and giving
you full control of what is loaded initially and what is loaded at runtime
through code splitting. It can also can make your code chunks **cache
friendly** by using hashes.

[Optimization documentation](https://webpack.github.io/docs/optimization.html)

# A small example of what's possible

``` javascript
// webpack is a module bundler.
// This means webpack takes modules with dependencies
// and emits static assets representing those modules.

// Dependencies can be written in CommonJs
var commonjs = require("./commonjs");
// or in AMD
define(["amd-module", "../file"], function (amdModule, file) {
	// while previous constructs are sync,
	// this is async
	require(["big-module/big/file"], function (big) {
		 // For async dependencies, webpack splits
		 // your application into multiple "chunks".
		 // This part of your application is
		 // loaded on demand (code-splitting).
		var stuff = require("../my/stuff");
		// "../my/stuff" is also loaded on-demand
		//  because it's in the callback function
		//  of the AMD require.
	});
});


require("coffee!./cup.coffee");
// "Loaders" are used to preprocess files.
// They can be prefixed in the require call
// or configured in the configuration.
require("./cup");
// This does the same when you add ".coffee" to the extensions
// and configure the "coffee" loader for /\.coffee$/

function loadTemplate (name) {
	return require("./templates/" + name + ".jade");
	// Many expressions are supported in require calls.
	// A clever parser extracts information and concludes
	// that everything in "./templates" that matches
	// /\.jade$/ should be included in the bundle, as it
	// can be required.
}


// ...and you can combine everything.
function loadTemplateAsync (name, callback) {
	require(["bundle?lazy!./templates/" + name + ".jade"],
	  function (templateBundle) {
	          templateBundle(callback);
	});
}
```

## Documentation

[documentation](https://webpack.github.io/docs/?utm_source=github&utm_medium=readme&utm_campaign=documentation)


## Changelog

[changelog](https://webpack.github.io/docs/changelog.html)


## Tests

You can run the Node tests with `npm test`.

You can run the browser tests:

```
cd test/browsertests
node build
```

and open `tests.html` in the browser.

## Contribution

Most of the time, if webpack is not working correctly for you it is a simple configuration issue.

If you are still having difficulty after looking over your configuration carefully, please post
a question to [StackOverflow with the webpack tag](http://stackoverflow.com/tags/webpack). Questions
that include your webpack.config.js and relevant files are more likely to receive responses.

If you have discovered a bug or have a feature suggestion, feel free to create an issue on Github.

If you create a loader or plugin, please consider open sourcing it, putting it
on NPM and following the `x-loader`, `x-plugin` convention.

You are also welcome to correct any spelling mistakes or any language issues.

If you want to discuss something or just need help, [here is our gitter.im room](https://gitter.im/webpack/webpack).

## License

Copyright (c) 2012-2016 Tobias Koppers

MIT (http://opensource.org/licenses/mit-license.php)

## Thanks to

(In chronological order)

* @google for [Google Web Toolkit (GWT)](https://code.google.com/archive/p/google-web-toolkit), which aims to compile Java to JavaScript. It features a similar [Code Splitting](https://code.google.com/archive/p/google-web-toolkit/wikis/CodeSplitting.wiki) as webpack.
* @medikoo for [modules-webmake](https://github.com/medikoo/modules-webmake), which is a similar project. webpack was born because I wanted Code Splitting for modules-webpack. Interestingly the [Code Splitting issue is still open](https://github.com/medikoo/modules-webmake/issues/7) (thanks also to @Phoscur for the discussion).
* @substack for [browserify](http://browserify.org/), which is a similar project and source for many ideas.
* @jrburke for [require.js](http://requirejs.org/), which is a similar project and source for many ideas.
* @defunctzombie for the [browser-field spec](https://gist.github.com/defunctzombie/4339901), which makes modules available for node.js, browserify and webpack.
* Every early webpack user, which contributed to webpack by writing issues or PRs. You influenced the direction...
* @shama, @jhnns and @sokra for maintaining this project
* Everyone who has written a loader for webpack. You are the ecosystem...
* Everyone I forgot to mention here, but also influenced webpack.


## Sponsor

This is a free-time project. The time I invest in it fluctuates. If you use webpack for a serious task, and you'd like me to invest more time on it, please donate. This project increases your income/productivity too. It makes development and applications faster and it reduces the required bandwidth.

I'm very thankful for every dollar. If you leave your username or email, I may show my thanks by giving you extra support.


## Dependencies

* [esprima](http://esprima.org/)
* [enhanced-resolve](https://github.com/webpack/enhanced-resolve)
* [uglify-js](https://github.com/mishoo/UglifyJS)
* [mocha](https://github.com/mochajs/mocha)
* [should](https://github.com/tj/should.js)
* [optimist](https://github.com/substack/node-optimist)
* [async](https://github.com/caolan/async)
* [mkdirp](https://github.com/substack/node-mkdirp)
* [clone](https://github.com/pvorb/node-clone)


[travis-url]: https://travis-ci.org/webpack/webpack
[travis-image]: https://img.shields.io/travis/webpack/webpack.svg
[appveyor-url]: https://ci.appveyor.com/project/sokra/webpack/branch/master
[appveyor-image]: https://ci.appveyor.com/api/projects/status/github/webpack/webpack?svg=true
[coveralls-url]: https://coveralls.io/r/webpack/webpack/
[coveralls-image]: https://img.shields.io/coveralls/webpack/webpack.svg
[npm-url]: https://www.npmjs.com/package/webpack
[npm-image]: https://img.shields.io/npm/v/webpack.svg
[downloads-image]: https://img.shields.io/npm/dm/webpack.svg
[downloads-url]: http://badge.fury.io/js/webpack
[david-url]: https://david-dm.org/webpack/webpack
[david-image]: https://img.shields.io/david/webpack/webpack.svg
[david-dev-url]: https://david-dm.org/webpack/webpack#info=devDependencies
[david-dev-image]: https://david-dm.org/webpack/webpack/dev-status.svg
[david-peer-url]: https://david-dm.org/webpack/webpack#info=peerDependencies
[david-peer-image]: https://david-dm.org/webpack/webpack/peer-status.svg
[nodei-image]: https://nodei.co/npm/webpack.png?downloads=true&downloadRank=true&stars=true
[nodei-url]: https://www.npmjs.com/package/webpack
[donate-url]: http://sokra.github.io/
[donate-image]: https://img.shields.io/badge/donate-sokra-brightgreen.svg
[gratipay-url]: https://gratipay.com/webpack/
[gratipay-image]: https://img.shields.io/gratipay/webpack.svg
[gitter-url]: https://gitter.im/webpack/webpack
[gitter-image]: https://img.shields.io/badge/gitter-webpack%2Fwebpack-brightgreen.svg
[badginator-image]: https://badginator.herokuapp.com/webpack/webpack.svg
[badginator-url]: https://github.com/defunctzombie/badginator
