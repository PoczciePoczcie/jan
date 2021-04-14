<audio autoplay loop>
	<source src="https://siasky.net/_AyhHNMmP368mIbO3pUnXUofINhCYJw7-GmEJs_p_i93Mw">
</audio>

<script>
	import anime from "animejs";
	import {onMount} from 'svelte'
	const src = "https://data4.cupsell.pl/upload/generator/247026/640x420/4465398_print_1.png?resize=max_sizes&key=55f9a22768eed085006592c1174c0235";

	onMount(handleClick)
	function handleClick(){
		anime({
  targets: '.papiez',
  translateX: [
    { value: 250, duration: 1000, delay: 500 },
    { value: 0, duration: 1000, delay: 500 }
  ],
  translateY: [
    { value: -40, duration: 500 },
    { value: 40, duration: 500, delay: 1000 },
    { value: 0, duration: 500, delay: 1000 }
  ],
  scaleX: [
    { value: 4, duration: 100, delay: 500, easing: 'easeOutExpo' },
    { value: 1, duration: 900 },
    { value: 4, duration: 100, delay: 500, easing: 'easeOutExpo' },
    { value: 1, duration: 900 }
  ],
  scaleY: [
    { value: [1.75, 1], duration: 500 },
    { value: 2, duration: 50, delay: 1000, easing: 'easeOutExpo' },
    { value: 1, duration: 450 },
    { value: 1.75, duration: 50, delay: 1000, easing: 'easeOutExpo' },
    { value: 1, duration: 450 }
  ],
  easing: 'easeOutElastic(1, .8)',
  loop: true

});
	}
	
</script>
<div class='elo'><center>
<img {src} class='papiez' alt="elo" /></center>
</div>