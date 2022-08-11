# From User [Saukko](https://discord.com/users/211381663423266483826852155480572929)

<details>
<summary>07/27/2022 - Grids</summary>
<br>
<p>Yeah so this picture happened while I were looking for ways to remove the <em>orange and teal color grading</em>. Apparently that is a really common palette that is used for example, to emphasize skin tone, create depth and to replicate the golden hour. Initially this was supposed to be a grid showing comparison of different <code>--no xyz</code> alternatives for removing or lessening the orange &amp; teal look, especially in the higher <code>--stylize</code> values.</p>
<p>But... While playing around with prompts that could be a good examples/base images, I found that when you have large <code>--stylize</code>, for example, <code>--s 12500</code>, <strong>you need bigger negative weight to get rid of unwanted elements with high stylize value.</strong> I don&#39;t know how this plays out with multi prompts or really complex stuff, but at least it&#39;s something. The <code>--no golden hour</code> was producing most consistent results in my tests, so I didn&#39;t bother to do bigger research on this.</p>
<p>The base prompt was <code>body shot of a beautiful person, long red hair, large eyes, stylish clothing, smiling, waterfall background, professional photograph, natural lighting, golden ratio, rule of thirds --sameseed 123 --ar 3:2</code></p>
<p>X axis has the different negative weights: none, -0.25, -0.5 (same as --no) and -0.75</p>
<p>Y axis demonstrates the <code>--stylize</code> values: 2500, 5000, 7500, 12500, 20000, 32500</p>
<p>The grid can be found here: <a href="https://saukkko.gitbook.io/grids/stylize">https://saukkko.gitbook.io/grids/stylize</a></p>
<p>Couple of external articles about the orange &amp; teal look</p>
<p><a href="https://www.diyphotography.net/reasons-orange-teal-look-popular-movies/">https://www.diyphotography.net/reasons-orange-teal-look-popular-movies/</a></p>
<p><a href="https://petapixel.com/2017/02/23/orange-teal-look-popular-hollywood/">https://petapixel.com/2017/02/23/orange-teal-look-popular-hollywood/</a></p>
<p><a href="https://www.adobe.com/creativecloud/video/hub/features/why-use-orange-teal-grading">https://www.adobe.com/creativecloud/video/hub/features/why-use-orange-teal-grading</a></p>
<br>
</details>
---
<details>
<summary>08/07/2022 - <p>What is this new parameter <code>--chaos</code> all about? (equivalent to <code>--c</code>)</p> </summary>
<br>
<p>As of writing this, no one outside the team knows for sure. Yet. But I did two grids with prompt <code>a bottle of water --sameseed 32768</code> and the only thing I can say so far is that <code>--chaos</code> <em>seems to be</em> more consistent with values 70..100 and more random with lower values.</p>
<ul>
<li><p>First grid is simply with <code>a bottle of water --sameseed 32768 --s 625 --c X</code> as an attempt to visualize what it does.</p>
</li>
<li><p>Second grid is 5x5 with <code>a bottle of water --sameseed 32768 --s X --c Y</code> to see how <code>--chaos</code> correlates with <code>--stylize</code></p>
</li>
</ul>
<p>Grid #1: <a href="https://saukkko.gitbook.io/grids/chaos/effects">https://saukkko.gitbook.io/grids/chaos/effects</a></p>
<p>Grid #2: <a href="https://saukkko.gitbook.io/grids/chaos/correlation-with-stylize">https://saukkko.gitbook.io/grids/chaos/correlation-with-stylize</a></p>
<p>Not sure what to make of from all of this, but I guess we&#39;ll hear more about it later.</p>
<p>Enjoy.</p>

<br>
</details>
---