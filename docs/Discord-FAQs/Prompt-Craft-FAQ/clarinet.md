<details>
<summary>07/13/2022 - Instructions for Avast users to add Midjourney as a "safe" destination:</summary>
<br>
Open Avast > go to Menu > Settings > General > Exceptions > [Add Exception] button > enter "www.midjourney.com"
</details>
---
<details>
<summary>07/15/2022 - How do I find my ‘random seed’ value/number?</summary>
<br>
There are two ways to find the seed number. 
<br>

<p><strong>[1]</strong> If you are working with a current composition and it&#39;s on the screen in front of you, you can react to it with an envelope and wait. A moment later the bot will send you a display that includes the seed.
<br>
<strong>[2]</strong> If you are trying to find the seed from a prior creation, you will need to copy the <code>job ID</code> from the website details <code>[...]</code> menu, then use the <code>/show</code> command with that ID, and then react to that display with the envelope.</p>
</details>
---
<details>
<summary>07/15/2022 -What does a ‘start’ or ‘seed’ image really do? </summary>
<br>

When you provide a start image (URL) to MJ, it runs its AI *image recognition process* against the image, and produces a language prompt (just like ours), which it then prepends to whatever language prompt YOU give it. 

<br>
MJ then uses the default weight, or the weight you provided with ``---iw``, to process both its MJ-created language prompt AND your human-created language prompt *together*. 

<br>
This translation of image-to-language-prompt is why feeding MJ seed images behaves nothing like a Photoshop filter: MJ picks up the subject matter and concepts, i.e. nouns - verbs - adjectives - anything that might surface as a word in a language prompt.
<br>
</details>
---
<details>
<summary>07/16/2022 - Is there any way to make MJ interpret my prompt with complete accuracy?</summary>
<br>
We have found only one 100% accurate prompt: <br>
 <img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/997864542115737640/IMG_1362.png">
 <br>
 No but seriously: Natural language is your best bet, we’ve found, Midjourney is striving to understand “correctly written English.” Since it does not quite understand it, you’ll have luck with strings of comma-separated values with little or no grammar. But since it unpredictably and weakly understands grammar, you often increase your chances by including it.
<br>
</details>
---

<details>
<summary>07/16/2022 - The Three Basket Problem:</summary>
<br>
“There are three baskets. The first one is filled with blueberries, the second one is filled with apples, the last one is filled with strawberries.” <br>


▫️ MJ can’t currently compose this collage. <br>
▫️ MJ does not currently support grammatical notions of direct objects or prepositional phrases with much reliability. <br>
▫️ MJ does not at this time support addressable objects, so pronouns and grammatical references (like “the first basket” or “it is”)  are also unreliable.<br>

Bottom line: You might be able to get three baskets, but the current version of MJ does not support sorting the fruits.
<br>
</details>
---

<details>
<summary>07/16/2022 - Why is it so hard to get specific compositional arrangements?
 </summary>
<br>
Conjecture: MJ relies on the "art direction" of its sources to decide how to arrange things for you. How does that play out? It means there are the places in your prompt where the sourcing is noticeably influencing your composition: <br>

Direct objects: The dog barks at the ball.<br>
Prepositional phrases: A cat climbs up a curtain.<br>
Pronouns:  It glows in his hand.<br>
Subject References: The second  basket is full of apples.<br>

MJ will source "dog, barks, ball" and find the most common compositions that meet these criteria. It might not be 'barking at' (your language) but ONE of the grid selections may eventually land there or near there. <br>
<br>
ACTION: To improve your chances, your job is to [1] select words with maximum specificity ('lounging' is more specific than 'lying down', 'dalmation' is more specific than 'white dog with black spots'), [2] use grammatically correct language, and then [3] work with MJ through grid selections to bring it incrementally closer to your vision. 

<br>
</details>
---

<details>
<summary>07/17/2022 - Variation, Upscale, Uplight, Stop? What’s the difference? </summary>
<br>
What we call  a ”veeroll” creates a variation on the selected composition. <br>


▫️An upScale (“yooroll”)  pursues the same composition but pushes it a little further along in its rendering, which is typically increasing the “richness” of details.<br>


▫️—upLight also works on the same composition but uses a finessed “lighter touch” on the rendering, so simplifies the details. <br>


▫️ —stop N is like manually pulling the handbrake on the render process at N%, no finesse.<br>

This is something else that you’ll get a sense of after experimenting a few times. You can experiment endlessly in relax mode without using your valuable fast minutes.
<br>
</details>
---

<details>
<summary>07/17/2022 - HOW TO GET A FULL BODY PORTRAIT</summary>
<br>
You need three things to get a full body portrait:<br>
1. an aspect ratio tall enough to account for a full body, which means something like  1152x2048, 9:16, 5:9, 1:2<br>
2. A source of poses that includes full body examples, which means adding "stock photography" to the prompt for example<br>
3. details for MJ to add to the whole figure.  If you mention just her shirt, she might not have pants or shoes. It is best to drag the camera from head to toe touching with a detail  every part you want MJ to render.  e.g, As soon as you mention shoes, MJ knows he has to show you the whole figure.
<br>
</details>
---

<details>
<summary>07/22/2022 - SUMMARY</summary>
<br>
<p><strong>A start image</strong> is an image URL as the first element in your prompt. It is like giving MJ a hint about what to create for you.  MJ does not apply itself to that image like a filter, but rather creates another language prompt from it to add to yours.</p>
<p><strong>In order to get a full body portrait,</strong> you need an aspect ratio that is tall enough to account for the whole figure, a source of poses that includes full body examples (such as <code>stock photography</code>), and details for MJ to include for the entire figure.</p>
<p><strong>Reroll</strong> 🔄  renders a fresh grid for your prompt ...plus adds another iteration of details, <strong>Variation</strong> [V1] renders a  similar grid  from your prompt ...plus adds another iteration of detail, <strong>Upscale</strong> [U1] increases the size from thumbnail to full ...plus adds another iteration of detail, but <strong>--Uplight</strong> uses a light touch to simplify details, and <strong>--Stop</strong> halts the whole render process like a handbrake.</p>
<p>It can be difficult to get MJ to generate <strong>specific compositional arrangements</strong> because the algorithm relies on the &quot;art direction&quot; of its sources. To improve your chances of getting the composition you want, use specific words, grammatically correct language, and work with MJ through grid selections.</p>
<p><strong>To find the seed</strong> for a current composition, react to it with an envelope. To find the seed for a past composition, copy the job ID from the website details menu and use the <code>/show</code> command with that ID, then react to the display that appears with an envelope.</p>
<p><strong>Multi-prompts</strong> are two or more independent prompts about a single subject or setting. They are helpful to  ``clearly establish a setting:: then embellish upon subjects in that setting</p>
<br>
</details>
---

<details>
<summary>07/23/2022 - TO EVOLVE YOUR CREATION, ROLL MORE </summary>
<br>
<ul>
<li><p><strong>/imagine</strong> renders a grid of possible compositions from your prompt</p>
</li>
<li><p><strong>Reroll</strong> 🔄 <em>also</em> renders a grid of possible compositions from your prompt ...<em>plus</em> adds another iteration of detail</p>
</li>
<li><p><strong>Variation</strong> [V1] renders a grid similar to your selection ...<em>plus</em> adds another iteration of detail</p>
</li>
<li><p><strong>Upscale</strong> [U1] increases the size of your selection from thumbnail to full ...<em>plus</em> adds another iteration of detail</p>
</li>
<li><p>So, all these interactions evolve your composition... BUT! <code>--uplight</code> at the end of your prompt uses a light touch to simplify details when it is rolled, and <code>--stop 90</code> halts the whole render process like a handbrake at whatever percentage you specify (replace 90 with your own number).</p>
</li>
</ul>
</details>
---

<details>
<summary>07/23/2022 - re: how commas and ::'s effect  weights </summary>
<br>
 <img alt="Midjourney Discord Picture" src="https://media.discordapp.net/attachments/996170079102312468/1000424208389656656/IMG_1456.jpg?width=923&height=493">
<br>
</details>
---
<details>
<summary>07/31/2022 - Images </summary>
<br>
<img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/992207085146222713/1003321791760048158/unknown.png"><br>
<img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/1003325317953376316/unknown-4.png"><br>
<img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/1003325317953376316/unknown-4.png"><br>
<br>
</details>
---
<details>
<summary>07/31/2022 - HANDS DRAGONS WHALES BIRDS AND OTHER CHAOSBLOBS</summary>
<br>
The data source contains 100,000+ pictures of whales, no two alike, so it's really hard for MJ to settle on a single whale. He is superimposing and averaging together all the whale cues he's picking up from his data set. The same will happen to birds, dragons, hands, anything that has a lot of motion and unique representations in the data set. The best you could do is try to reduce the subset of pictures MJ is sourcing from. Start talking about whales next to divers, alongside boats, breaching, photographed by famous nature photographers who do whales, artists who do whales, movies with whales, etc. That specificity will narrow the range of images MJ is sourcing from. It will increase the coherence of the output.
<br>
</details>
---
<details>
<summary>08/02/2022 - Discord Settings</summary>
<br>
 <img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/1004187503898673152/IMG_1513.jpg">
<br>
</details>
---

<details>
<summary>08/02/2022 - </summary>
<br>
<p><strong>START IMAGES / IMAGE PROMPTS</strong></p>
<p>Image prompts INFLUENCE outcomes, but images are not &quot;ingested, processed, and returned to you&quot; as you might expect.</p>
<p>When you provide an image URL as the first element of your text prompt, MJ will, in a way, use it to write its own text prompt and run its prompt and your prompt together.</p>
<p>To increase the chance of getting the composition you&#39;re chasing, the prompt you write to include with the image must <em>describe the entire final output you want to see.</em></p>
<p>Play with <code>--iw</code> (image weight) values and reroll. <strong>USE 1:1 ASPECT RATIO IMAGES AS PROMPTS</strong></p>
<br>
<img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/1004202097371267153/image-prompts-and-you-2022-08-02_20-37-29.jpg">
<br>
</details>
---

<details>
<summary>08/03/2022 -  Is there a good guide to camera control lingo I can use in MJ? </summary>
<br>
We don't know which of these terms MJ understands but we think you should experiment and report back!<br>

<a href="https://www.studiobinder.com/blog/ultimate-guide-to-camera-shots/">Click here for some help!</a>
<br>
</details>
---

<details>
<summary>08/04/2022 - How can I add legible text to my composition?</summary>
<br>
Your mileage may vary, but here are the four elements to rendering text that we think might be necessary. <br>
<img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/1004909243532574850/midjourney-text-placement-suggestion-shambibble.jpg">
<br>
</details>
---

<details>
<summary>08/04/2022 - WEIGHTS = <strong>WEIGHTED AVERAGES</strong></summary>
<br>
<p>So here&#39;s how it works (excuse some simplification):</p>
<p><code>dog:: cat::</code> = is dog (once), cat (once), averaged</p>
<p><code>dog::2 cat::2</code> = is dog dog (twice now) cat cat (twice now), averaged</p>
<p><code>dog::4 cat:1</code> = dog dog dog dog cat, averaged</p>
<p><code>dog::1 cat:3</code> = dog cat cat cat, averaged</p>
<p>You can play with these values to influence how they render:</p>
<p><code>Something::1</code></p>
<p><code>Lightly Something::0.5</code></p>
<p>``Eliminate Something::-1</p>
<br>
</details>
---

<details>
<summary>08/04/2022 - The best chance of creating a full weapon:</summary>
<br>
<p>1. Use an aspect ratio that suits the most common orientation of the weapon. Swords are vertical, rifles are horizontal.</p>
<p>2. Google the weapon in question and find its specific terms. Don&#39;t say &quot;bow&quot; - say &quot;recurve bow&quot;. Don&#39;t say &quot;sword in a lake&quot; - say &quot;Excalibur&quot;.</p>
<p>3. Find artists and other style cues that correspond to the weapon you&#39;re after. What media, games, movies, comics, artists, genres, etc represent your weapon well? Include these in your prompt. <em>Some</em> of them might work. Others will be dead weight.</p>
<p>4. Finally, if you want an action pose, then VERB  your weapon. Do not say &quot;an orc with a sword&quot; - say &quot;a Warhammer 40k orc fighting the wind with a broadsword&quot; or &quot;a 16th century samurai warrior striking a wooden dummy with Excalibur&quot;</p>
<br>
</details>
---

<details>
<summary>08/04/2022 - TO EVOLVE YOUR CREATION, ROLL MORE
 </summary>
<br>
<p>🔹 <strong>/imagine</strong> renders a grid of possible compositions from your prompt inside a cached session</p>
<p>🔹  <strong>Reroll</strong> 🔄 <em>also</em> renders a grid of possible compositions from your prompt ...<em>plus</em> adds another iteration of detail</p>
<p>🔹 <strong>Variation</strong> [V1] renders a grid similar to your selection ...<em>plus</em> adds another iteration of detail</p>
<p>🔹<strong>Upscale</strong> [U1] increases the size of your selection from thumbnail to full ...<em>plus</em> adds another iteration of detail</p>
<p>🔷  So, all these interactions evolve your composition... BUT! </p>
<p><code>--uplight</code>  at the end of your prompt uses a light touch to simplify details when it is rolled, and</p>
<p> <code>--stop 90</code> halts the whole render process like a handbrake at whatever percentage you specify (replace 90 with your own number)</p>
<p>➡️  These iterations of detail are good for one session of <code>/imagine</code>. When you manually use <code>/imagine</code> again, it starts a 🆕 new session and evolutionary progress resets.</p>
<br>
</details>
---

<details>
<summary>08/05/2022 - SEED AND SAMESEED</summary>
<br>
<img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/1004963574352969779/how-do-seeds-work-gdi.jpg">
<br>
</details>
---

<details>
<summary>08/05/2022 - QUEUE TROUBLE? </summary>
<br>
<img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/1005149494515613777/788CF709-7640-43F0-B9C9-313B382D37E3.png">
<br>
</details>
---

<details>
<summary>08/05/2022 - COMMON STORE FRAMING SIZES</summary>
<br>
<p><strong>COMMON STORE FRAMING SIZES</strong> </p>
<p>(in inches):: = </p>
<p>--ar 4:5 (8x10 &amp; 16x20) </p>
<p> --ar 1:3 (11.75x36) ... its really 1:3.06 = 47:144</p>
<p> --ar 11:4 (16.5x6)</p>
<p> --ar 11:14 (11:14 &amp; 22x28)</p>
<p> --ar 3:4 (12x16)</p>
<p> --ar 13:19 (13x19)</p>
<p> --ar 7:9 (14x18)</p>
<p> --ar 3:8 (18x24)</p>
<p> --ar 5:6 (20x24)</p>
<p> --ar 2:3 (24x36 &amp; 20x30)</p>
<hr>
<p>with thanks to &lt;@Jonh2o#5670&gt; </p>
<hr>

<br>
</details>
---

<details>
<summary>08/05/2022 - PUNCTUATION MEANS WHAT?</summary>
<br>
<p>So <code>::</code> is the only &#39;official&#39; break in a prompt, but comma, plus, pipes all have some (minor) effects as well.  Nothing consistent, but in some cases one may be better than another.</p>
<p>Here&#39;s a test I ran a while back:</p>
<p><code>Red panda</code> clearly shows the animal of that name.</p>
<p><code>Red, panda</code> separates them a little bit (a red-haired red panda)</p>
<p><code>Red:: panda</code> gives a panda that is red</p>
<p><code>Red:: panda:: ---no red panda</code> is even more clearly a panda which is red (and not a red panda)</p>
<br>
<img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/992207085146222713/996970513865908345/F2C250B0-73AA-4828-9D2B-8C50C51E8804.jpg">
<br>
</details>
---

<details>
<summary>08/06/2022 - <strong>How to check first if Midjourney even understands your sourcing reference:</strong> </summary>
<br>
<p>➡️  TLDR: /imagine something you&#39;ll recognize as being in that style.</p>
<p>1. 🤔  You want to say <code>in the style of Ren &amp; Stimpy</code> (for example) but you don&#39;t know if Midjourney will understand that.</p>
<p>2. 🤔 You think about something that appears commonly in that style. For example, something that appears often in Ren &amp; Stimpy is a <strong>cartoon chihuahua</strong> (that&#39;s Ren himself).</p>
<p>3. 💻 You do this simple test: <code>/imagine a cartoon chihuahua in the style of Ren &amp; Stimpy</code></p>
<p>4. 👍  If output looks like it&#39;s adopted the style you named, you&#39;re golden.</p>
<pre><code> 👎  If it appears generic <span class="hljs-keyword">with</span> lots of orange <span class="hljs-keyword">and</span> teal colors, yo<span class="hljs-string">u're looking at Midjourney '</span>defaults<span class="hljs-string">' which is an error message meaning NOT FOUND.</span>
</code></pre>
<br>
</details>
---

<details>
<summary>08/06/2022 - HOW DO I RECREATE ONE OF MY IMAGES WITH A SMALL CHANGE?</summary>
<br>
<p>For those of you who know the term PRIMARY KEY from relational databases...</p>
<p><code>$string of your prompt + the $integer of your seed = primary key for the image output</code></p>
<p>If you&#39;ve made an image of a red bird on a <strong>white</strong> background and want to make it a red bird on a <strong>black</strong> background, and you change just that <em>one word</em> and roll the prompt again with its $seed again, you will <em>almost</em> get the same picture but with the new color. If you change the aspect ratio, watch for MJ to possibly completely reinterpret the prompt for the new canvas size.</p>
<p>✅ TLDR: If you use <code>EXACT $string + $seed</code> again, you&#39;ve used a primary key to recreate a close approximation of your original composition. But NEVER pixel-to-pixel exactly the same. </p>
<hr>
<p><strong>FAQ: How do I know the seed value?</strong></p>
<p>➡️ <a href="https://discord.com/channels/662267976984297473/996170079102312468/997635192116219904">https://discord.com/channels/662267976984297473/996170079102312468/997635192116219904</a></p>

<br>
</details>
---

<details>
<summary>08/09/2022 - How can I reuse the same consistent character like an actor in a scene?</summary>
<br>
Clarinet's Method - Directing Characters in a Scene
https://bit.ly/Clarinet-MJ-Puppets
<br>
</details>
---

<details>
<summary>08/09/2022 - How can I render the same consistent character in multiple visual styles?
</summary>
<br>
Shambibble's  Method - Rendering Characters in Different Visual Styles
https://docs.google.com/document/d/13c8Ci-8kU2PVZu6DKghlhOOrbf4kmtc9xxCJAnPqvC0/edit

<br>
</details>
---

<details>
<summary>08/11/2022 - WEIGHTED AVERAGES
</summary>
<br>
<p><em>crappy video explaining math - extrapolate to weights in MJ</em></p><br>
<video controls>
      <source id="mp4" src="https://cdn.discordapp.com/attachments/996170079102312468/1007325569840578570/Whiteboard-Math-Lesson-Sample-v0.03-DRAFT.mp4" type="video/mp4">
</videos>
<br>
</details>
---