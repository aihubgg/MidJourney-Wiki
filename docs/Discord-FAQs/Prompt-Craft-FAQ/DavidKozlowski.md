---
title: David Kozlowski Discord Guides
description: All of David Kozlowski Discord guides, without the scrolling!
---

# From User [David Kozlowski](https://discord.com/users/795739975463075851)

<details>
<summary>08/16/2022 - Generating a new MJ image from an image URL</summary>
<br>
<p>I think I cracked the code (a bit) regarding how to maximize image URLs in a prompt. Feels like a breakthrough, I can finally force MJ to produce what I want with more accuracy.</p>
<p><strong>Steps:</strong></p>
<p>1. Find an online image of a car (ideally, take a photo of your own car -- copyright laws are no joke!) and upload to a website or Discord</p>
<p>2. Grab the entire URL for this image (<em>note: some URLs contain extra characters after .png or .jpg, do not include these or Discord will choke</em>)</p>
<p>3. Place the image URL at the start of your prompt (weighted at roughly 0.75), and MJ will build from the uploaded image. </p>
<p>4. *.png images with transparent backgrounds are best -- in other words, only provide MJ what you want it to see.</p>
<p><a href="https://www.pinpng.com/pngs/m/86-868188_ford-mustang-ford-mustang-1969-png-transparent-png.png">https://www.pinpng.com/pngs/m/86-868188_ford-mustang-ford-mustang-1969-png-transparent-png.png</a></p>
<p><code>/imagine prompt: https://www.pinpng.com/pngs/m/86-868188_ford-mustang-ford-mustang-1969-png-transparent-png.png --iw 0.75 :: Digital painting of a 1969 Ford Mustang from hell :: flames, lightning, smoke :: epic composition, aerial view, symmetrical, chaotic, detailed, evil, vacuum fluorescent display, x-ray, cinematic lighting, unreal engine, photorealistic, digital art --s 1250 --q 2 --ar 16:9 --sameseed 22081620</code></p>
<p><a href="https://cdn.discordapp.com/attachments/996170079102312468/1009248414082535454/David_Kozlowski_1969_Ford_Mustang_from_hell_baec28e1-802a-44a3-b5b0-eadec9b8b303.png"><img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/1009248414082535454/David_Kozlowski_1969_Ford_Mustang_from_hell_baec28e1-802a-44a3-b5b0-eadec9b8b303.png"></a>
</p>
<br>
</details>
---
<details>
<summary>08/16/2022 - More fun with image URL and --iw parameter! </summary>
<br>
<p>I&#39;m my previous two posts, I used the URL of a 1969 Ford Mustang that I found online (<em>suggestion: seek images with transparent backgrounds to keep MJ from freaking out</em>). I used this URL in my prompt to create some amazing images of bad-ass automobiles. Essentially, MJ used the image URL (weighted at 0.75) as a baseline for the generated image. In a way, I supplied the reference and MJ supplied the effects.</p>
<p>In this experiment, I used a photo of my wife to create a fun but realistic image. MJ struggled a bit with the eyes, even though I used &quot;symmetry&quot; &quot;symmetrical&quot; or &quot;symmetrical face&quot; in the prompt.</p>
<p><strong>Steps:</strong></p>
<p>1. Upload a photo of someone you know (to avoid copyright problems) and grab the URL</p>
<p>2. Create a new prompt with the URL as the first element</p>
<p>3. Include the param: --iw 1.25 (I&#39;ve gone as high as 2, your mileage may vary)</p>
<p>4. Create the rest of your prompt</p>
<p>5. Re-roll and upscale as necessary</p>
<p><em>NOTE: There is a 6,000 character limit for MJ prompts, and image URLs can be loooooong. Keep this in mind!</em></p>
<p><code>https://images.squarespace-cdn.com/content/v1/60f49b1c72db40740f8f503e/51919330-a3bd-40fc-82bb-123223dd42a4/jennifer_lying_in_bed.jpg --iw 1.25 :: Portrait of a half-woman half-cat :: woman is wearing a large overcoat that looks like cat fur :: confetti, butterflies, and flowers are scattered around the scene:: third-person, beautiful face, furry, symmetrical,  symmetry Disney, chaotic, detailed, dreamy, happy, euphoric, organic, volumetric lighting, unreal engine, DeviantArt, photorealistic, digital art --s 2500 --q 2</code></p>
<p><a href="https://cdn.discordapp.com/attachments/996170079102312468/1009250459208388699/David_Kozlowski_Digital_painting_of_a_1969_Ford_Mustang_from_he_0413ef2f-8d5d-4b7b-bd5c-806de1f7cd36.png"><img alt="Midjourney Discord Picture" src="https://cdn.discordapp.com/attachments/996170079102312468/1009250459208388699/David_Kozlowski_Digital_painting_of_a_1969_Ford_Mustang_from_he_0413ef2f-8d5d-4b7b-bd5c-806de1f7cd36.png"></a></p>
<br>
</details>
