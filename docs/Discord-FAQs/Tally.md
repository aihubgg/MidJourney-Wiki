<details>
<summary>7/11/2022 - General</summary>
<br>
1. Try synonyms or alternate phrases. Trash can not working? Try waste basket, etc.. <br> 2. Playing with multiprompts and weights can help ensure a certain aspect of the image appears, and can help color specific objects (see: `/help`)<br> 3. You're not limited to only referencing one arist, see who's styles you can combine! <br>4. Emoji's are valid and make fantastic results.
</details>
---
<details>
<summary>7/11/2022 - Can I edit an existing prompt?</summary>
<br>
If you want to change he prompt, aspect ratio, etc.. you'll need to start over. There's no current way to change the --ar, --stop, text, image prompt, etc.. after an image has been generated.
</details>
---
<details>
<summary>07/11/2022 - I put an image in and it's not what I expected</summary>
<br>
Image prompts are for inspiration only and will not apply a style filter to the image. You can try to influence the final image more with input images by adjusting the `--iw X` image weight. 
</details>
---
<details>
<summary>7/11/2022 - My face has weird rings around the eyes</summary>
<br>
It's possible MJ is attempting to add glasses, you can try using `--no glasses` (or `glasses::-.5`) to reduce the chance MJ creates them. Tired of creepy grins? Try `--no teeth`.This is useful in many other situations as well, such as when you have birds in your landscapes that come out all wonky, just add `--no birds`. 
</details>
---
<details>
<summary>7/11/2022 - My faces are weird</summary>
<br>
Eyes and faces are hard! Don't give up! In addition to some of the previous tips, try out `symmetric eyes` or `airbrushed`  
</details>
---
<details>
<summary>7/11/2022 - I have too many heads</summary>
<br>
Check your aspect ratio! Try out 2:3 or 4:5, you can also try `--no double faces`!
</details>
---
<details>
<summary>7/11/2022 - Why do people put artstation, 8k, 4k, etc...</summary>
<br>
MidJourney (MJ) is currently trained on hundreds of millions (soon to be billions) of images. These images are scraped from the internet and the text used to describe them are also pulled from that same page. When someone puts artstation, or octane render, they're trying to push MJ to use styles similar to images found with those tags or descriptions. Try it out with other websites such as pixiv, deviantart, quixel, etsy, etc.. and see how it changes the result!
</details>
---
<details>
<summary>7/11/2022 - Tips for anime  </summary>
<br>
1\. Reference an artist if you can, MJ is great at picking up styles<br>2. Using `--uplight` and `--stop x` can help reduce noise and smooth out an image<br>3. Fluff words such as pretty, cute, beautiful, etc.. make a drastic difference.
</details>
---
<details>
<summary>7/11/2022 - Fast and Relax</summary>
<br>
Standard members have the option to switch to a slower mode using `relax` This wont eat up your fast hours, but will take 2-10 minutes to generate the image, you can have 3 concurrently running jobs, and 10 items in your queue. It's a fantastic way to preserve those fast hours (Note: fast hours reset every month and do not roll over- make sure you do take advantage of them! They're great for max upscales!)
</details>
---
<details>
<summary>7/11/2022 - What do the +'s between prompts on the website mean?</summary>
<br>
Those are multiprompts, the `::` operator.  
</details>
---
<details>
<summary>7/14/2022 - How can weights affect prompts?</summary>
<br>
Note: This is a very simple example, but should help your understanding. (Iterating through Sphere::1 Teapot::.1 down and up by .1 steps, using sameseed)<br>![](https://cdn.discordapp.com/attachments/996170079102312468/997180845276286986/TeapotWeights.png)<br>![](https://cdn.discordapp.com/attachments/996170079102312468/997180845276286986/TeapotWeights.png))   
</details>
---
<details>
<summary> Photorealism vs Photograph</summary>
<br>
Stolen from a (prompt-craft member)<br>Photorealism is what painters use to describe their works<br>Photographs are what photographers take :)<br>photoreal will inherently lend towards more painterly, or art brush, etc.. styles     
</details>
---
<details>
<summary>7/21/2022 - Does stop affect upscale?  </summary>
<br>
No! The upscale process will generate all of its detail as it normally does, \_but\_ if stopping early causes the base grid to look different, the upscale will still rely on what was produce by the grid and create a very different upscale:<br>![](https://cdn.discordapp.com/attachments/996170079102312468/999879557819670538/Tallath_teapot_34e8b04f-ac1b-4b10-b4b7-97180634909d.png)<br>
![](https://cdn.discordapp.com/attachments/996170079102312468/999879558041964594/Tallath_teapot_95912add-9063-4627-897a-6d295f7fe74e.png)<br>
![](https://cdn.discordapp.com/attachments/996170079102312468/999879558343966760/Tallath_teapot_8c884060-4e65-4056-a5b8-6acb276a6eef.png)<br>
![](https://cdn.discordapp.com/attachments/996170079102312468/999879558675304488/Tallath_teapot_e5e6a90c-1991-4621-94b8-311ea3ea119b.png)<br>
![](https://cdn.discordapp.com/attachments/996170079102312468/999879558998274118/Tallath_teapot_b11d91c6-61bd-48bc-ae18-976d7651714c.png)<br>
![](https://cdn.discordapp.com/attachments/996170079102312468/999879559228956712/Tallath_teapot_a8fc71ae-62f8-42fd-960e-d9cf3e0fba30.png)<br>
</details>
---
<details>
<summary>7/25/2022 - Quality vs Style  </summary>
<br>
Please note: quality settings will get rounded to the closest available setting (so .25, .5, 1, 2, and 5 are the only options available, others will be rounded)<br>![](https://cdn.discordapp.com/attachments/996170079102312468/1001168218553073755/TEAPOTSTYLES.png)
---
<details>
<summary>7/26/2022 - Condensed version with only allowable --q values </summary>
<br>
![](https://cdn.discordapp.com/attachments/996170079102312468/1001174568100180038/TeapotStylesSmall.png)
</details>
---
<details>
<summary>7/27/2022 - How quality affects various prompts </summary>
<br>
(Scrub through the timeline for easy comparison) [Click for Video](https://cdn.discordapp.com/attachments/996170079102312468/1001451942423314442/MJQualities.mp4
</details>
