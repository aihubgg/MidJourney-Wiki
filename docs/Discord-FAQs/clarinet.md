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

**[2]** If you are trying to find the seed from a prior creation, you will need to copy the ``job ID`` from the website details ``[...]`` menu, then use the ``/show`` command with that ID, and then react to that display with the envelope.
</details>
---
<details>
<summary>07/15/2022 -What does a ‘start’ or ‘seed’ image really do? </summary>
<br>

When you provide a start image (URL) to MJ, it runs its AI *image recognition process* against the image, and produces a language prompt (just like ours), which it then prepends to whatever language prompt YOU give it. 


MJ then uses the default weight, or the weight you provided with ``---iw``, to process both its MJ-created language prompt AND your human-created language prompt *together*. 


This translation of image-to-language-prompt is why feeding MJ seed images behaves nothing like a Photoshop filter: MJ picks up the subject matter and concepts, i.e. nouns - verbs - adjectives - anything that might surface as a word in a language prompt.
</details>
---