<h1 id="office">office</h1>

<p>A vim theme inspired by classic office beige.</p>

<h2 id="screenshots">screenshots</h2>

<table>
<tr><td align="center"><strong>office-dark</strong></td><td align="center"><strong>office-light</strong></td></tr>
<tr>
<td><img src="/img/screenshot-office-dark.png" alt="screenshot of the office-dark vim theme" width="288" /></td>
<td align="center"><img src="/img/screenshot-office-light.png" alt="screenshot of the office-light vim theme" width="288" /></td>
</tr>
</table>

<blockquote>
  <p>pictured font: <a href="http://input.fontbureau.com/">Input Mono Narrow</a> (1.2x line spacing)</p>
</blockquote>

<h2 id="setup">setup</h2>

<h3 id="installation">installation</h3>

<p>While vim themes can be installed manually (place <a href="https://github.com/nightsense/office/tree/master/colors">theme file</a> in <code class="highlighter-rouge">~/.vim/colors/</code>), a <strong>plugin helper</strong> is recommended.</p>

<p>If you don’t have a preferred helper, consider trying <a href="https://github.com/junegunn/vim-plug">vim-plug</a>, which can be installed with:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
</code></pre>
</div>

<p>To install office via vim-plug, add the following to the top of your <code class="highlighter-rouge">vimrc</code>:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>call plug#begin('~/.vim/plugged')
Plug 'nightsense/office'
call plug#end()
</code></pre>
</div>

<p>Then restart vim and run <code class="highlighter-rouge">PlugUpdate</code> (from the vim command line).</p>

<h3 id="activation">activation</h3>

<p>To activate the office theme, add one of the following lines to your <code class="highlighter-rouge">vimrc</code>:</p>

<ul>
  <li><code class="highlighter-rouge">colorscheme office-light</code></li>
  <li><code class="highlighter-rouge">colorscheme office-dark</code></li>
</ul>

<blockquote>
  <p>To assign themes to specific intervals of the day, try the <a href="https://github.com/nightsense/night-and-day">night-and-day</a> plugin.</p>
</blockquote>

<h2 id="terminal-vim">terminal vim</h2>

<p>See the <a href="https://github.com/nightsense/nightshell">nightshell</a> repository, which allows office to be used in a variety of terminal applications.</p>

<h2 id="palette">palette</h2>

<p>office consists of 8 theme-distinct <strong>base colours</strong>, which are used for most interface elements, and 8 standard <strong>accent colours</strong> (common to the “nightsense theme family”) used for syntax highlighting.</p>

<blockquote>
  <ul>
    <li>accent colour hues were selected at the scale of 1/12 (30°) colour wheel intervals
      <ul>
        <li>6 of these hues were fine-tuned with 1/6 subinterval adjustments</li>
      </ul>
    </li>
    <li>base colour hue was selected from among:
      <ul>
        <li>the 24 hues available at the scale of 1/24 (15°) colour wheel intervals</li>
        <li>the additional 6 aforementioned fine-tuned hues</li>
      </ul>
    </li>
    <li>discrete intervals were also used for tuning colour saturations (1/24) and values (1/12)</li>
    <li>the <a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html#visual-audio-contrast-contrast-73-head">ISO 3:1 contrast standard</a> is met by nearly all text/background combinations, exceptions being made for some transient-highlighted backgrounds (e.g. cursorcolumn, cursorline)</li>
  </ul>
</blockquote>

<table>
  <thead>
    <tr>
      <th style="text-align: right">base</th>
      <th style="text-align: center">light-background accents</th>
      <th style="text-align: left">dark-background accents</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/2b2b28.png" height="24" width="42" /> <code class="highlighter-rouge">2b2b28</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/f53d3d.png" height="24" width="42" /> <code class="highlighter-rouge">f53d3d</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/e07070.png" height="24" width="42" /> <code class="highlighter-rouge">e07070</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/40403b.png" height="24" width="42" /> <code class="highlighter-rouge">40403b</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/eb6200.png" height="24" width="42" /> <code class="highlighter-rouge">eb6200</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/d48c59.png" height="24" width="42" /> <code class="highlighter-rouge">d48c59</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/54544d.png" height="24" width="42" /> <code class="highlighter-rouge">54544d</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/ebca28.png" height="24" width="42" /> <code class="highlighter-rouge">ebca28</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/bfad51.png" height="24" width="42" /> <code class="highlighter-rouge">bfad51</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/75756c.png" height="24" width="42" /> <code class="highlighter-rouge">75756c</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/009e00.png" height="24" width="42" /> <code class="highlighter-rouge">009e00</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/6a9e6a.png" height="24" width="42" /> <code class="highlighter-rouge">6a9e6a</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/949488.png" height="24" width="42" /> <code class="highlighter-rouge">949488</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/70e0cd.png" height="24" width="42" /> <code class="highlighter-rouge">70e0cd</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/4f9e91.png" height="24" width="42" /> <code class="highlighter-rouge">4f9e91</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/bfbfb0.png" height="24" width="42" /> <code class="highlighter-rouge">bfbfb0</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/0083e0.png" height="24" width="42" /> <code class="highlighter-rouge">0083e0</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/659fc9.png" height="24" width="42" /> <code class="highlighter-rouge">659fc9</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/e0e0ce.png" height="24" width="42" /> <code class="highlighter-rouge">e0e0ce</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/964be0.png" height="24" width="42" /> <code class="highlighter-rouge">964be0</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/9f80bf.png" height="24" width="42" /> <code class="highlighter-rouge">9f80bf</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/fffff5.png" height="24" width="42" /> <code class="highlighter-rouge">fffff5</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/eb4d9c.png" height="24" width="42" /> <code class="highlighter-rouge">eb4d9c</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/c9759f.png" height="24" width="42" /> <code class="highlighter-rouge">c9759f</code></td>
    </tr>
  </tbody>
</table>

<p><img src="http://www.colorhexa.com/f53d3d.png" height="24" width="42" />
<strong>Red</strong>, the colour of alarm, is used for <strong>warning elements</strong>, including error messages, misspellings, and diff deletions.</p>

<p><img src="http://www.colorhexa.com/eb6200.png" height="24" width="42" />
<strong>Orange</strong>, the colour of fire, can be associated with the preliminary “warmup” phase of some activity; literally, this could be the heating-up of a hearth for forging, or a stove for cooking. Orange is therefore used for <strong>preliminary elements</strong>, such as preprocessor commands (which prepare data to be handled by another program), incremental searching (that is, a search term in the process of being typed), titles, and miscapitalized words.</p>

<p><img src="http://www.colorhexa.com/ebca28.png" height="24" width="42" />
<strong>Yellow</strong>, the classic highlighting colour, is applied to elements that are not warnings, yet should draw attention with high visibility. These <strong>highlighted elements</strong> include search results, task tags (<code class="highlighter-rouge">TODO</code>, <code class="highlighter-rouge">FIXME</code>…), and diff changes.</p>

<p><img src="http://www.colorhexa.com/009e00.png" height="24" width="42" />
<strong>Green</strong>, the colour that says “go ahead, proceed with the task at hand”, is used for <strong>action elements</strong>, such as statements (if/then, while/do, case…), mode indicators (insert, visual…), vim user prompts, and diff additions.</p>

<p><img src="http://www.colorhexa.com/70e0cd.png" height="24" width="42" />
<strong>Teal</strong> is named after the “common teal”, a kind of duck, thus connecting this colour with the concept of “species”, which is a means of classifying life into very specific types. Teal is therefore used for specifying <strong>object types</strong>, such as data type (boolean, integer, string…) or storage class (static, volatile…), as well as marking mislocalized words (that is, words that are not misspelled but of the wrong type, namely a foreign locale type).</p>

<p><img src="http://www.colorhexa.com/0083e0.png" height="24" width="42" />
<strong>Blue</strong>, a colour of calm stability, is used for <strong>constants</strong>, which come in the form of boolean values, integers, floating-point numbers, characters, and strings.</p>

<p><img src="http://www.colorhexa.com/964be0.png" height="24" width="42" />
<strong>Purple</strong>, often associated with (historically) rare purple dyes produced for special works of art, is used for <strong>special text</strong>, including special characters (standalone or within syntax units), vim tags, and debugging statements. Rarely-used words are also marked, allowing the writer to consider whether such a specially uncommon word is appropriate.</p>

<p><img src="http://www.colorhexa.com/eb4d9c.png" height="24" width="42" />
<strong>Pink</strong>, the colour of spring blossoms, is used for <strong>object names</strong>, including the names of variables and functions. To code is to bring countless objects blossoming into life as one types their names.</p>
