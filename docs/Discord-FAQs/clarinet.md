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

**[1]** If you are working with a current composition and it's on the screen in front of you, you can react to it with an envelope and wait. A moment later the bot will send you a display that includes the seed.
<br>
**[2]** If you are trying to find the seed from a prior creation, you will need to copy the ``job ID`` from the website details ``[...]`` menu, then use the ``/show`` command with that ID, and then react to that display with the envelope.
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
<summary>07/1/2022 - Is there any way to make MJ interpret my prompt with complete accuracy?</summary>
<br>
We have found only one 100% accurate prompt: <br>
 <img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/997864542115737640/IMG_1362.png">
 <br>
 No but seriously: Natural language is your best bet, we’ve found, Midjourney is striving to understand “correctly written English.” Since it does not quite understand it, you’ll have luck with strings of comma-separated values with little or no grammar. But since it unpredictably and weakly understands grammar, you often increase your chances by including it.
<br>
</details>
---

<details>
<summary>07/16/2022 - </summary>
<br>
The Three Basket Problem:<br> 

“There are three baskets. The first one is filled with blueberries, the second one is filled with apples, the last one is filled with strawberries.” <br>


▫️ MJ can’t currently compose this collage. <br>
▫️ MJ does not currently support grammatical notions of direct objects or prepositional phrases with much reliability. <br>
▫️ MJ does not at this time support addressable objects, so pronouns and grammatical references (like “the first basket” or “it is”)  are also unreliable.<br>

Bottom line: You might be able to get three baskets, but the current version of MJ does not support sorting the fruits.
<br>
</details>
---

<details>
<summary>07/16/2022 - </summary>
<br>
Why is it so hard to get specific compositional arrangements?
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
How do I find my 'random seed' value/number?<br>

There are two ways to find the seed number. <br>

.A start image** is an image URL as the first element in your prompt. It is like giving MJ a hint about what to create for you.  MJ does not apply itself to that image like a filter, but rather creates another language prompt from it to add to yours.<br>

**In order to get a full body portrait,** you need an aspect ratio that is tall enough to account for the whole figure, a source of poses that includes full body examples (such as ``stock photography``), and details for MJ to include for the entire figure.<br>

**Reroll** 🔄  renders a fresh grid for your prompt ...plus adds another iteration of details, **Variation** [V1] renders a  similar grid  from your prompt ...plus adds another iteration of detail, **Upscale** [U1] increases the size from thumbnail to full ...plus adds another iteration of detail, but **--Uplight** uses a light touch to simplify details, and **--Stop** halts the whole render process like a handbrake.<br>

It can be difficult to get MJ to generate **specific compositional arrangements** because the algorithm relies on the "art direction" of its sources. To improve your chances of getting the composition you want, use specific words, grammatically correct language, and work with MJ through grid selections.<br>

**To find the seed** for a current composition, react to it with an envelope. To find the seed for a past composition, copy the job ID from the website details menu and use the ``/show`` command with that ID, then react to the display that appears with an envelope.<br>

**Multi-prompts** are two or more independent prompts about a single subject or setting. They are helpful to  ``clearly establish a setting:: then embellish upon subjects in that setting<br>

[1] If you are working with a current composition and it's on the screen in front of you, you can react to it with an envelope and wait. A moment later the bot will send you a display that includes the seed.<br>



[2] If you are trying to find the seed from a prior creation, you will need to copy the ``job ID`` from the website details ``[...]`` menu, then use the ``/show`` command with that ID, and then react to that display with the envelope..<br>



**What does a 'start' or 'seed' image really do?**<br>

When you provide a start image (URL) to MJ, it runs its AI *image recognition process* against the image, and produces a language prompt (just like ours), which it then prepends to whatever language prompt YOU give it. <br>



MJ then uses the default weight, or the weight you provided with ``---iw``, to process both its MJ-created language prompt AND your human-created language prompt *together*. <br>



This translation of image-to-language-prompt is why feeding MJ seed images behaves nothing like a Photoshop filter: MJ picks up the subject matter and concepts, i.e. nouns - verbs - adjectives - anything that might surface as a word in a language prompt.
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
---

<details>
<summary>07/1/2022 - </summary>
<br>
Drop
<br>
</details>
---
