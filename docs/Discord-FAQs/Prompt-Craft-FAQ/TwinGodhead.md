# From User [TwinGodhead](https://discord.com/users/211381665480572929)

<details>
<summary>07/22/2022 - Remove Digital Painting Influence Experiement</summary>
<br>
<p>I did experiments for the optimal pattern to remove  the digital painting influence and found that it works best when the negative weight is somewhere between -40 and -60 and ensuring all positive weight prompts have a weight at least 1 higher than the digital painting is negative. Example:</p>
<p>doctor::50.0 digital painting::-49.0</p>
<p>-50 seems about perfect, but I have trouble telling if -45 is better.</p>
<p>See example in this thread: <a href="https://discord.com/channels/662267976984297473/1000229361078784020">https://discord.com/channels/662267976984297473/1000229361078784020</a></p>
<p>The positive weight doesn&#39;t seem to make a difference so long as it&#39;s at least 1 more in magnitude to the negative weight.</p>
<p><code>doctor::75.0 digital painting::-50.00</code></p>
<p>Appears identical to</p>
<p><code>doctor::51.0 digital painting::-50.00</code></p>
<p>I tested everything with the same seed to reduce extraneous variation. I&#39;ll test multi-prompts another time</p>
<br>
</details>
---
<details>
<summary>07/28/2022 - Description Testing </summary>
<br>
<p>A fair description. The initial noise would look something like this image</p>
<p><a href="https://cdn.discordapp.com/attachments/996170079102312468/1002330694984405083/name.png"><img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/1002330694984405083/name.png"></a></p>
<p>With --hd, it would be close to this. That&#39;s the difference. A larger starting images giving more variation per image patch in terms of the visible size for each squared cm on the image. That lets it create denser details.</p>
<p><a href="https://media.discordapp.net/attachments/996170079102312468/1002331106609217586/name_hd.png?width=539&amp;height=539"><img alt="Midjourney Discord Picture" src="https://media.discordapp.net/attachments/996170079102312468/1002331106609217586/name_hd.png?width=539&amp;height=539""></a></p>
<ol>
<li><p>They would not give images higher weight in the training data to achieve that effect. That would cause too many side effects. They&#39;re either adding words to the prompt or adding vectors to the output of certain neural network layers based on what they want to inject.</p>
</li>
<li><p>Additionally, to achieve the &quot;variations&quot; feature, it appears they take a partially done frame from the source image, maybe at 80% finished, and add a layer of noise on top then have it finish from there to produce something different yet close to the source. (edited)</p>
</li>
</ol>
<br>
</details>
