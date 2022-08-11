# From User [shambibble](https://discord.com/users/174164654111588352)

<details>
<summary>07/16/2022 - Can you direct complex concepts with specific composition and multiple subjects?</summary>
<br>
<p>Well, you&#39;re in for a lot of dice-rolling... but one way to slightly shorten it may be an image prompt mockup, fed alongside your text, adjusting the image weights as necessary; with this you can try to align midjourney&#39;s classifiers with its generators and &quot;push through&quot; a concept</p>
<p>midjourney parses images at a max of 256x256, so you don&#39;t need to be a photoshop wizard or anything, a crude collage of the things you want can be sufficient, whether they&#39;re previous midjourney renders (the penguin) or even just stock clip art you grabbed online (the lander)</p>
<p>prompt with mockup image:</p>
<p>Two subjects: a spacesuited penguin placing a flag next to a landing module with mechanical legs, the gray surface of the lunar horizon, matte painting, trending on artstation, professional digital art, hd --iw 1 --ar 5:3</p>
<a href="https://s.mj.run/93Fr29HHXS8"><img alt="Midjourney Discord Picture" src="https://s.mj.run/93Fr29HHXS8"></a>
<p>Where i was after 30 minutes of relax re-rolling; it pulled through a blue flag and tried to put the southern cross on it on its own initiative (edited)</p>
<p><a href="https://cdn.discordapp.com/attachments/996170079102312468/997941178752311316/unknown.png"><img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/997941178752311316/unknown.png"></a></p>
<br>
</details>
---

<details>
<summary>07/19/2022 - MULTIPROMPTING AND YOU</summary>
<br>
<p><strong>What is a multiprompt?</strong></p>
<p>a multiprompt :: the answer to your question</p>
<p><strong>Very funny, but really.</strong></p>
<p>Multiprompts (called weighting in the official docs) set two <em>independent</em> targets for the diffuser to match. Every time it renders a scene, the AI is constantly looking back and forth between what it has and what (it thinks) you want. This just means that when it decides which direction to go in, it will take all of those prompts into account. (You can weight each prompt with a number after the :: see the official FAQ for details)</p>
<p><strong>Okay, but how is that different from just putting two things in a prompt?</strong></p>
<p>Single prompts, no matter how many things you add with commas, are going to point the AI in a single direction that&#39;s roughly an average of all of the stuff you specified and you can&#39;t focus it on any one thing. So it&#39;ll get your awesome character concept &quot;trending on artstation&quot; and &quot;detailed and realistic&quot; and then forget to draw an arm.</p>
<p>Then it will notice it forgot to draw an arm, look at your prompt again, realize that &quot;trending on artstation&quot; and &quot;detailed and realistic&quot; are six words, while &quot;man&quot; is one word and its only missing one little piece anyway, how important can that be? and happily go on dotting your armless character with finely textured skin pores.</p>
<p><strong>So if I want two specific things, I should multiprompt each of them?</strong></p>
<p>Not necessarily! Many people think this, and you sometimes get lucky, but doing &quot;one red cube :: one blue cube&quot; is not any more efficient because as long as there is at least one (or more) cubes on screen, and parts of them are red and blue, the diffuser will look at each side and go &quot;hell yeah, think I nailed it.&quot; It&#39;s more likely to <em>merge</em> the multiprompted concepts than separate them.</p>
<p>Instead, prompt with something like this &quot;two segregated cubes :: a red cube and a blue cube&quot;. Now you&#39;ve given a second direction that essentially tells the AI to double-check both the quantity and the arrangement. You&#39;ve reinforced at least one concept in both prompts (&quot;cube&quot;) so both diffuser directions can start with common ground. And most importantly, we WANT it to merge those two concepts, because merging &quot;segregated&quot; with &quot;red and blue&quot; cashes out to &quot;I should group those red and blue pixels&quot; <a href="https://www.midjourney.com/app/jobs/c41b22db-5352-4acd-9fb6-2b7ddbf042bf/">https://www.midjourney.com/app/jobs/c41b22db-5352-4acd-9fb6-2b7ddbf042bf/</a></p>
<p>You should not think of multi-prompts as discrete subjects in your composition. Think of them more like overlays, or emphasis. If you want two subjects, go for &quot;two [subjects] :: information about them&quot; and that way when it merges the subject with the details it will hopefully at least get you over the hump of vrolling for something that isn&#39;t a Tuvix. I generally have one &quot;subject&quot; prompt with minimal, key information, and then one &quot;style&quot; prompt that has all of the style, details, framing, etc.</p>
<p>And keep in mind, once you start going past more than 2-3 multiprompts, you&#39;ll just re-create the same issues you have with single prompts.</p>
<p><strong>Okay, so you can make red, green, and blue fruit baskets. What else?</strong></p>
<p>Text! If you want to shorten your time vrolling for legible text, don&#39;t put &quot;legible text&quot; in your prompt like a chump. Instead, do something like this:</p>
<p>&quot;TEXT&quot; :: details about your scene or logo or poster or whatever with &quot;TEXT&quot;</p>
<p>Reinforcing the text itself on both sides of a multi-prompt has two advantages: it gives the AI a &quot;guide&quot; to help steer it through vrolls and hopefully load the dice for you, and it also lets you say things ABOUT the text (like its on a credit card held by a particular woman you image prompted) while reducing the chance that those instructions get rendered AS text (which will often happen in single prompts) since you&#39;ve now told it where the emphasis goes. <a href="https://www.midjourney.com/app/jobs/80d33ba8-cf46-48c7-b129-9098778a6cba/">https://www.midjourney.com/app/jobs/80d33ba8-cf46-48c7-b129-9098778a6cba/</a></p>
<p><strong>Wow, cool! Anything more?</strong></p>
<p>I dunno man I figured all this out in the last week or so get back to me.</p>
<br>
</details>
