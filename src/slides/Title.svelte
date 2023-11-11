<!-- <script>
    import { onMount } from 'svelte';
 import Slide from '../lib/Slide.svelte';
 import Code from '../lib/Code.svelte';

    let title;
    onMount(() => {
        let timeout;
        title = new Promise(resolve => {
            timeout = setTimeout(() => resolve('Whats nice together?'), 1000);
        });
        () => clearTimeout(timeout);
    });
</script>

<Slide bgImage="assets/title_background.gif">
    <h2>
        {#await title}
            Wait a sec...
        {:then result}
            {result}
        {/await}
    </h2>

		<Code lineNumbers trim noescape>
    {
    `const name = "hello world";
    if(name === 'hello') {
      console.log('world');
    }
    `
    }
		</Code>
</Slide> -->
<section data-banner="default" data-watermark="true" data-background-image="assets/title_background_noloop.gif" data-background-opacity="0.6" style="filter: brightness(1.6);">
    <img src="assets/title_an_emulators_journey.png" alt="An Emulator's Journey" height="600" width="1200">
    <div class="r-stretch">
    </div>
</section>