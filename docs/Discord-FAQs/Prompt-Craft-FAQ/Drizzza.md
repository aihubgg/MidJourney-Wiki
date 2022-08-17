---
title:  Drizzza Discord Guides
description: All of Drizzza Discord guides, without the scrolling!
---
# From User [Drizzza.eth](https://discord.com/users/271409877283373056)

<details>
<summary>08/15/2022 - Short list of good prompt parameters</summary>
<br>
<p>These utilize weighting with <code>::</code>. A positive number indicates <code>more of this</code>, a negative number indicates <code>less of this</code>. <strong>You want to have a higher number than 0</strong> when you add all the numbers up, <strong>basically,</strong> or you&#39;ll get a strange blurry image if the total equals 0. <strong>A parameter with just <code>::</code> and no number after indicates a value of 1.</strong> (You may need to change the weighted values for each of these dependent upon your prompt complexity. Try <code>--no</code> instead of <code>::</code> if you just need one of these to remove something like <code>--no glasses</code>)</p>
<p>If you find parameters you&#39;ve separated with <code>::</code> end up with the same weight and don&#39;t need to be <strong>&quot;separated&quot;</strong> for your composition, then group them under a single <code>::</code> with commas instead. </p>
<p>EX: Instead of <code>low-key lighting::1 DSLR::1 defocus::-1</code> try instead <code>low-key lighting, DSLR::1.5 defocus::-1</code>.</p>
<p><strong>Only add negative parameters after running the most simple prompt you can to see results</strong>. If you notice something appears, like your character having three arms but you only want two, then re-create the same prompt with the new parameter <code>three arms::-1</code>.</p>
<p><strong>Help reduce &quot;painting style&quot;</strong></p>
<blockquote>
<p>digital painting::-1</p>
<p>DSLR::1</p>
<p>8k post-processing::1</p>
<p>Photograph::1</p>
<p>40mm lens::1</p>
<p>sharp details::1</p>
<p>imax lens::1</p>
</blockquote>
<p>(Basically describe something like a camera make and model, lens type, or render engine)</p>
<p><strong>Remove or add depth of field blur: </strong></p>
<blockquote>
<p>defocus::-1</p>
<p>blur::-1 </p>
<p>bokeh::-1</p>
<p>dof::1</p>
</blockquote>
<p><strong>Helps with faces: </strong></p>
<blockquote>
<p>glasses::-1 </p>
<p>extra faces::-1</p>
<p>three eyes::-1</p>
<p>one eye::-1</p>
<p>teeth::-1</p>
<p>symmetric face::2</p>
<p>symmetric eyes::2</p>
</blockquote>
<p>(<code>glassess::-1</code> fixes <strong>&quot;rings&quot;</strong> in eyes)</p>
<p><strong>Helps with character positioning: </strong></p>
<blockquote>
<p>two people::-1</p>
<p>back of head, back of body::-1</p>
<p>three arms, three legs::-1 </p>
<p>one leg, one arm::-1</p>
<p>full-body portrait::1</p>
<p>half-body portrait::1</p>
<p>full length portrait::1 </p>
<p>dynamic pose::1</p>
<p>action scene::1</p>
<p>combat scene::1</p>
</blockquote>
<p>(To get full body portraits it also helps to change to a vertical aspect ratio. EX: --ar 9:16)</p>
<p><strong>Cool lighting effects: </strong></p>
<blockquote>
<p>crepuscular rays::1</p>
<p>global illumination::1</p>
<p>low-key lighting::1</p>
<p>high-key lighting::1</p>
<p>hard lighting::1</p>
<p>soft lighting::1</p>
<p>muted tones with soft lighting::1</p>
<p>volumetric fog::1</p>
</blockquote>
<p><strong>Helps with buildings: </strong></p>
<blockquote>
<p>impossible angles::-1 </p>
<p>non-Euclidean geometry::-1</p>
</blockquote>
<p><strong>Sometimes helps with multi-subject prompts: </strong></p>
<blockquote>
<p>two subjects::1</p>
<p>three subjects::1</p>
<p>ballroom dancing::1</p>
</blockquote>
<p>(Describing an <code>action</code> or <code>pose</code> can help with making your characters come to life, reduce --s below 2500 for better results here, --s 1250 can be very good for poses and getting characters to interact.)</p>
<p><strong>Add style type to your art: </strong></p>
<blockquote>
<p>in the style of (artist/ movie/ anime/ studio name)::2</p>
<p>art by (artist/ movie/ anime/ studio name)::2</p>
<p>2D vector::1</p>
<p>3D model::1</p>
<p>Unreal Engine::1</p>
<p>Octane Render::1</p>
<p>Unity Engine::1</p>
<p>Pencil Illustration::1</p>
<p>Hand drawn::1</p>
<p>Clay sculpture::1</p>
<p>Carved from (material name)::1</p>
</blockquote>
<p>(Get creative with this and consider mashing up a few together for new styles of art!)</p>
<p><strong>Get That 2D Children Style Cartoon Drawing Look: </strong></p>
<blockquote>
<p>textures::-1</p>
<p>color gradients::-1</p>
<p>simple colors::1</p>
<p>solid colors::1</p>
<p>cel shading::1</p>
<p><strong>MidJourney Docs to check if MJ knows the artist: </strong></p>
<p><a href="https://docs.google.com/spreadsheets/d/10i9Ip8tVSERAuMWbc6-H6BUFCoUGOQ91YzDvX--c4bk">https://docs.google.com/spreadsheets/d/10i9Ip8tVSERAuMWbc6-H6BUFCoUGOQ91YzDvX--c4bk</a></p>
<p><a href="https://docs.google.com/spreadsheets/d/1VsKv6DlSLFfFpOYUXed8Z4yHomS1R-uKfIYJD93Bt84">https://docs.google.com/spreadsheets/d/1VsKv6DlSLFfFpOYUXed8Z4yHomS1R-uKfIYJD93Bt84</a></p>
</blockquote>
<p>I might add more to this in the future, who knows... hope it helps anyone confused with this stuff that&#39;s new.</p>
<br>
</details>