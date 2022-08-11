# From User [2hanssen4u](https://discord.com/users/531253427519488010)
<details>
<summary>08/08/2022 - Weighting Prompts</summary>
<br>
I've figured something out - I don't know if it's common knowledge or not, but... when you are weighting prompts, if you want to eliminate some terms as completely as possible it's best to give them a negative weight that is numerically equal to 1/2 of your total positive weight.<br>

For example:<br>
[image prompt url] text prompt ::3 text prompt two :: do-not-want text prompt ::-3 --iw 2<br>

The first text prompt (3) + second text prompt (1) + image prompt weight (2) = 6<br>

So I weight the prompt that I DO NOT want to see as half of that, negative. -3<br>

The closer you get to "zero" from there, the less your term will be 'eliminated'. But the farther you get to your negative weight balancing out your positive weight (-6 in the above example), the more weird and unpredictable your results will be. And if you have total balance between the two (+6/-6) you will completely 'break' MJ and it results in the weirdest stuff possible, that will have only a passing relevance to your prompt terms. (Personally, I have really enjoyed exploiting this on purpose!)<br>

 I think this is why --no has a default value of -0.5 ...if you haven't weighted any terms in your prompt, you would have a default positive weight value of 1. So, -0.5 follows the approach above.<br>
<br>
</details>
---
