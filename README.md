<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="Dillinger_0"></a>Dillinger</h1>
<h2 class="code-line" data-line-start=1 data-line-end=2 ><a id="_The_Last_Markdown_Editor_Ever__1"></a><em>The Last Markdown Editor, Ever</em></h2>
<p class="has-line-data" data-line-start="3" data-line-end="4"><a href="https://nodesource.com/products/nsolid"><img src="https://cldup.com/dTxpPi9lDf.thumb.png" alt="N|Solid"></a></p>
<p class="has-line-data" data-line-start="5" data-line-end="6"><a href="https://travis-ci.org/joemccann/dillinger"><img src="https://travis-ci.org/joemccann/dillinger.svg?branch=master" alt="Build Status"></a></p>
<p class="has-line-data" data-line-start="7" data-line-end="9">Dillinger is a cloud-enabled, mobile-ready, offline-storage compatible,<br>
AngularJS-powered HTML5 Markdown editor.</p>
<ul>
<li class="has-line-data" data-line-start="10" data-line-end="11">Type some Markdown on the left</li>
<li class="has-line-data" data-line-start="11" data-line-end="12">See HTML in the right</li>
<li class="has-line-data" data-line-start="12" data-line-end="14">✨Magic ✨</li>
</ul>
<h2 class="code-line" data-line-start=14 data-line-end=15 ><a id="Features_14"></a>Features</h2>
<ul>
<li class="has-line-data" data-line-start="16" data-line-end="17">Import a HTML file and watch it magically convert to Markdown</li>
<li class="has-line-data" data-line-start="17" data-line-end="18">Drag and drop images (requires your Dropbox account be linked)</li>
<li class="has-line-data" data-line-start="18" data-line-end="19">Import and save files from GitHub, Dropbox, Google Drive and One Drive</li>
<li class="has-line-data" data-line-start="19" data-line-end="20">Drag and drop markdown and HTML files into Dillinger</li>
<li class="has-line-data" data-line-start="20" data-line-end="22">Export documents as Markdown, HTML and PDF</li>
</ul>
<p class="has-line-data" data-line-start="22" data-line-end="25">Markdown is a lightweight markup language based on the formatting conventions<br>
that people naturally use in email.<br>
As <a href="http://daringfireball.net">John Gruber</a> writes on the <a href="http://daringfireball.net/projects/markdown/">Markdown site</a></p>
<blockquote>
<p class="has-line-data" data-line-start="26" data-line-end="33">The overriding design goal for Markdown’s<br>
formatting syntax is to make it as readable<br>
as possible. The idea is that a<br>
Markdown-formatted document should be<br>
publishable as-is, as plain text, without<br>
looking like it’s been marked up with tags<br>
or formatting instructions.</p>
</blockquote>
<p class="has-line-data" data-line-start="34" data-line-end="37">This text you see here is *actually- written in Markdown! To get a feel<br>
for Markdown’s syntax, type some text into the left window and<br>
watch the results in the right.</p>
<h2 class="code-line" data-line-start=38 data-line-end=39 ><a id="Tech_38"></a>Tech</h2>
<p class="has-line-data" data-line-start="40" data-line-end="41">Dillinger uses a number of open source projects to work properly:</p>
<ul>
<li class="has-line-data" data-line-start="42" data-line-end="43"><a href="http://angularjs.org">AngularJS</a> - HTML enhanced for web apps!</li>
<li class="has-line-data" data-line-start="43" data-line-end="44"><a href="http://ace.ajax.org">Ace Editor</a> - awesome web-based text editor</li>
<li class="has-line-data" data-line-start="44" data-line-end="45"><a href="https://github.com/markdown-it/markdown-it">markdown-it</a> - Markdown parser done right. Fast and easy to extend.</li>
<li class="has-line-data" data-line-start="45" data-line-end="46"><a href="http://twitter.github.com/bootstrap/">Twitter Bootstrap</a> - great UI boilerplate for modern web apps</li>
<li class="has-line-data" data-line-start="46" data-line-end="47"><a href="http://nodejs.org">node.js</a> - evented I/O for the backend</li>
<li class="has-line-data" data-line-start="47" data-line-end="48"><a href="http://expressjs.com">Express</a> - fast node.js network app framework <a href="http://twitter.com/tjholowaychuk">@tjholowaychuk</a></li>
<li class="has-line-data" data-line-start="48" data-line-end="49"><a href="http://gulpjs.com">Gulp</a> - the streaming build system</li>
<li class="has-line-data" data-line-start="49" data-line-end="51"><a href="https://breakdance.github.io/breakdance/">Breakdance</a> - HTML<br>
to Markdown converter</li>
<li class="has-line-data" data-line-start="51" data-line-end="53"><a href="http://jquery.com">jQuery</a> - duh</li>
</ul>
<p class="has-line-data" data-line-start="53" data-line-end="55">And of course Dillinger itself is open source with a <a href="https://github.com/joemccann/dillinger">public repository</a><br>
on GitHub.</p>
<h2 class="code-line" data-line-start=56 data-line-end=57 ><a id="Installation_56"></a>Installation</h2>
<p class="has-line-data" data-line-start="58" data-line-end="59">Dillinger requires <a href="https://nodejs.org/">Node.js</a> v10+ to run.</p>
<p class="has-line-data" data-line-start="60" data-line-end="61">Install the dependencies and devDependencies and start the server.</p>
<pre><code class="has-line-data" data-line-start="63" data-line-end="67" class="language-sh"><span class="hljs-built_in">cd</span> dillinger
npm i
node app
</code></pre>
<p class="has-line-data" data-line-start="68" data-line-end="69">For production environments…</p>
<pre><code class="has-line-data" data-line-start="71" data-line-end="74" class="language-sh">npm install --production
NODE_ENV=production node app
</code></pre>
<h2 class="code-line" data-line-start=75 data-line-end=76 ><a id="Plugins_75"></a>Plugins</h2>
<p class="has-line-data" data-line-start="77" data-line-end="79">Dillinger is currently extended with the following plugins.<br>
Instructions on how to use them in your own application are linked below.</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th>Plugin</th>
<th>README</th>
</tr>
</thead>
<tbody>
<tr>
<td>Dropbox</td>
<td><a href="https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md">plugins/dropbox/README.md</a></td>
</tr>
<tr>
<td>GitHub</td>
<td><a href="https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md">plugins/github/README.md</a></td>
</tr>
<tr>
<td>Google Drive</td>
<td><a href="https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md">plugins/googledrive/README.md</a></td>
</tr>
<tr>
<td>OneDrive</td>
<td><a href="https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md">plugins/onedrive/README.md</a></td>
</tr>
<tr>
<td>Medium</td>
<td><a href="https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md">plugins/medium/README.md</a></td>
</tr>
<tr>
<td>Google Analytics</td>
<td><a href="https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md">plugins/googleanalytics/README.md</a></td>
</tr>
</tbody>
</table>
<h2 class="code-line" data-line-start=89 data-line-end=90 ><a id="Development_89"></a>Development</h2>
<p class="has-line-data" data-line-start="91" data-line-end="92">Want to contribute? Great!</p>
<p class="has-line-data" data-line-start="93" data-line-end="95">Dillinger uses Gulp + Webpack for fast developing.<br>
Make a change in your file and instantaneously see your updates!</p>
<p class="has-line-data" data-line-start="96" data-line-end="97">Open your favorite Terminal and run these commands.</p>
<p class="has-line-data" data-line-start="98" data-line-end="99">First Tab:</p>
<pre><code class="has-line-data" data-line-start="101" data-line-end="103" class="language-sh">node app
</code></pre>
<p class="has-line-data" data-line-start="104" data-line-end="105">Second Tab:</p>
<pre><code class="has-line-data" data-line-start="107" data-line-end="109" class="language-sh">gulp watch
</code></pre>
<p class="has-line-data" data-line-start="110" data-line-end="111">(optional) Third:</p>
<pre><code class="has-line-data" data-line-start="113" data-line-end="115" class="language-sh">karma <span class="hljs-built_in">test</span>
</code></pre>
<h4 class="code-line" data-line-start=116 data-line-end=117 ><a id="Building_for_source_116"></a>Building for source</h4>
<p class="has-line-data" data-line-start="118" data-line-end="119">For production release:</p>
<pre><code class="has-line-data" data-line-start="121" data-line-end="123" class="language-sh">gulp build --prod
</code></pre>
<p class="has-line-data" data-line-start="124" data-line-end="125">Generating pre-built zip archives for distribution:</p>
<pre><code class="has-line-data" data-line-start="127" data-line-end="129" class="language-sh">gulp build dist --prod
</code></pre>
<h2 class="code-line" data-line-start=130 data-line-end=131 ><a id="Docker_130"></a>Docker</h2>
<p class="has-line-data" data-line-start="132" data-line-end="133">Dillinger is very easy to install and deploy in a Docker container.</p>
<p class="has-line-data" data-line-start="134" data-line-end="137">By default, the Docker will expose port 8080, so change this within the<br>
Dockerfile if necessary. When ready, simply use the Dockerfile to<br>
build the image.</p>
<pre><code class="has-line-data" data-line-start="139" data-line-end="142" class="language-sh"><span class="hljs-built_in">cd</span> dillinger
docker build -t &lt;youruser&gt;/dillinger:<span class="hljs-variable">${package.json.version}</span> .
</code></pre>
<p class="has-line-data" data-line-start="143" data-line-end="146">This will create the dillinger image and pull in the necessary dependencies.<br>
Be sure to swap out <code>${package.json.version}</code> with the actual<br>
version of Dillinger.</p>
<p class="has-line-data" data-line-start="147" data-line-end="150">Once done, run the Docker image and map the port to whatever you wish on<br>
your host. In this example, we simply map port 8000 of the host to<br>
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):</p>
<pre><code class="has-line-data" data-line-start="152" data-line-end="154" class="language-sh">docker run <span class="hljs-operator">-d</span> -p <span class="hljs-number">8000</span>:<span class="hljs-number">8080</span> --restart=always --cap-add=SYS_ADMIN --name=dillinger &lt;youruser&gt;/dillinger:<span class="hljs-variable">${package.json.version}</span>
</code></pre>
<blockquote>
<p class="has-line-data" data-line-start="155" data-line-end="156">Note: <code>--capt-add=SYS-ADMIN</code> is required for PDF rendering.</p>
</blockquote>
<p class="has-line-data" data-line-start="157" data-line-end="159">Verify the deployment by navigating to your server address in<br>
your preferred browser.</p>
<pre><code class="has-line-data" data-line-start="161" data-line-end="163" class="language-sh"><span class="hljs-number">127.0</span>.<span class="hljs-number">0.1</span>:<span class="hljs-number">8000</span>
</code></pre>
<h2 class="code-line" data-line-start=164 data-line-end=165 ><a id="License_164"></a>License</h2>
<p class="has-line-data" data-line-start="166" data-line-end="167">MIT</p>
<p class="has-line-data" data-line-start="168" data-line-end="169"><strong>Free Software, Hell Yeah!</strong></p>
