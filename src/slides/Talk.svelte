<!--
<script>
 import Notes from '../lib/Notes.svelte';
 import Youtube from '../lib/Youtube.svelte';

</script>

<section data-background="assets/talk_background.png">
    <h2>Getting Started</h2>
    <ul>
        <li class="fragment fade-up">Configure your Presentation in <code>config.js</code></li>
        <li class="fragment fade-up">Create your Slides in <code>src/slides</code></li>
        <li class="fragment fade-up">Add your Slides in <code>Presentation.svelte</code></li>
    </ul>
		<div class="grid place-items-center">
				<Youtube url="https://www.youtube.com/watch?v=xcDUpe1NfCQ"/>
		</div>
		<Notes>This is an example of slide notes</Notes>
</section>
//-->

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Open Source</h2>
    <div class="r-hstack">
        <p style="padding: 30px;">🚀</p>
        <p style="padding: 30px;">❤️</p>
        <p style="padding: 30px;">♻️</p>
    </div>
    
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>2013</h2>
    <div class="r-stack">
        <img src="assets/adobeflash.png" alt="Adobe Flash" width="1200" height="1000">
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <div class="r-stack">
        <img src="assets/book.jpeg" alt="3D in Flash" width="480" height="604">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <div class="r-stack">
        <img src="assets/ReleaseBanner4_1.jpg" alt="3D in Flash" width="740" height="400">
    </div>
</section>

<section data-background-iframe="assets/awayfl-an-emulators-journey-demos/bin/flashisdead.html">
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <div class="r-stack">
        <img src="assets/courage.jpeg" alt="Courage" width="750" height="1000">
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-transition="convex">
    <div class="r-stack">
        <img src="assets/away3d_logo_black_large.png" alt="Away3D" width="300" height="300">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-transition="convex">
    <div class="r-stack">
        <img src="assets/awayjslogo-5276.png" alt="AwayJS" width="300" height="300">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-transition="convex">
    <div class="r-stack">
        <img src="assets/awayfl-logo_large_black.png" alt="AwayFL" width="300" height="300">
    </div>
</section>


<section data-watermark="true" data-background="assets/talk_background.png" data-transition-speed="slow" data-autoslide="1000">
    <div class="fragment fragment-slow fade-in" data-autoslide="0">
        <h2>Gandal</h2>
        <div class="r-stack">
            <img src="assets/what-was-gandalf-smoking-the-lord-of-the-rings.jpg" alt="Gandalf" width="2000" height="1000">
            <div class="r-hstack fragment" data-autoslide="0">
                <img src="assets/money-falling.png" alt="Money Falling" width="300" height="1000" style="position: absolute; left: 20px;">
                <div class="r-stretch"></div>
                <img src="assets/open-source.png" alt="Open Source" width="200" height="1000" style="position: absolute; right: 40px;">
            </div>
        </div>
    </div>
    <div class="r-stack">
        <h2 class="fragment fade-in-then-out" style="padding: 30px;" data-autoslide="0">b2b > dev</h2>
        <h2 class="fragment fade-in-then-out" style="padding: 30px;" data-autoslide="0">support > patreon</h2>
    </div>
    
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Icycle</h2>
    <div class="r-stack">
        <img src="assets/Icycle1_Wireframe.png" alt="Icycle" width="800" height="1000">
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Sunflower Learning</h2>
    <div class="r-stack">
        <img src="assets/Sunflower_Learning.png" alt="Icycle" width="700" height="1000">
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Maths-Whizz</h2>
    <div class="r-stack">
        <img src="assets/Maths-Whizz.png" alt="Icycle" width="700" height="1000">
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Poki</h2>
    <div class="r-stack">
        <iframe data-src="assets/awayfl-an-emulators-journey-demos/bin/escaping_the_prison.html" width="750" height="519"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <div class="r-stack" style="margin: 0px 0px 20px 0px;">
        <img src="assets/gandalf_vs_balrog_sd.jpg" alt="Icycle" width="900" height="1000">
        <div class="r-vstack">
            <h1 style="margin: 0px 0px 80px 0px;color: #000;font-size: 340px !important;">as3</h1>
            <h2 style="margin: 0px 0px 0px 0px;font-size: 30px !important;">as2</h2>
        </div>
    </div>
    <h3 class="fragment">Interpreted vs Compiled</h3>
</section>

<section data-watermark="true" data-background="assets/talk_background.png" data-auto-animate>
    <div>
        <table width="100%">
            <thead>
                <tr>
                    <th><h3>interpreted</h3></th>
                    <th><h3 class="fragment" data-fragment-index="7">jit</h3></th>
                    <th><h3>compiled</h3></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td class="fragment" data-fragment-index="1">Python</td>
                    <td class="fragment" data-fragment-index="8">Java</td>
                    <td class="fragment" data-fragment-index="4">C / C++</td>
                </tr>
                <tr>
                    <td class="fragment" data-fragment-index="2">Lua</td>
                    <td class="fragment" data-fragment-index="9">C#</td>
                    <td class="fragment" data-fragment-index="5">Rust</td>
                </tr>
                <tr>
                    <td class="fragment" data-fragment-index="3">AS2</td>
                    <td class="fragment" data-fragment-index="10">AS3</td>
                    <td class="fragment" data-fragment-index="6">Zig</td>
                </tr>
            </tbody>
        </table>
        <p style="margin:20px 0px 0px 80px;text-shadow: #FC0 1px 0 10px !important;" class="fragment" data-fragment-index="11">Javascript</p>
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <div style="margin:0px 180px 0px 180px;">
        <p style="text-align: justify;">"Javascript should not be the last programming language. Think of the children!"</p>
        <p style="text-align: right;">- Douglas Crockford</p>
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>awayfl jit</h2>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">SWF</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">↓</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">Actionscript Byte Code</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">↓</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">Javascript</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">↓</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">JIT</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;" data-autoslide="50">↓</p>
    <p class="fragment" style="margin:0px 0px 0px 0px;">x86 / ARM</p>
    <div class="r-stretch">
        
    </div>
</section>

<section data-watermark="true" data-background="assets/talk_background.png">
    <h2>Bad Ice Cream</h2>
    <div class="r-stack">
        <iframe data-src="assets/awayfl-an-emulators-journey-demos/bin/assets/bad-ice-cream/index.html" width="550" height="550"></iframe>
    </div>
    <div class="r-stretch">
    </div>
</section>