<h1>Stylelint Setup</h1>

<p>You might like them - or you might not. Don't worry you can always change them.</p>

<h2>Local / Per Project Install</h2>
<ol>
<li>
<p>If you don't already have a <code>package.json</code> file, create one with <code>npm init</code>.</p>
</li>
<li>
<p>Then we need to install everything needed by the config:</p>
</li>
</ol>
<pre><code>npx install-peerdeps --dev stylelint-config-halolab
</code></pre>
<ol start="3">
<li>
<p>You can see in your package.json there are now a big list of devDependencies.</p>
</li>
<li>
<p>Create a <code>.stylelintrc</code> file in the root of your project's directory.
 Your <code>.stylelintrc</code> file should look like this:</p>
</li>
</ol>
<div class="highlight highlight-source-json"><pre>{
  <span class="pl-s"><span class="pl-pds">"</span>extends<span class="pl-pds">"</span></span>: [
    <span class="pl-s"><span class="pl-pds">"</span>stylelint-config-halolab<span class="pl-pds">"</span></span>
  ]
}</pre></div>
