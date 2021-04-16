<audio autoplay loop>
	<source src="https://siasky.net/_AyhHNMmP368mIbO3pUnXUofINhCYJw7-GmEJs_p_i93Mw">
</audio>

<script>
	import anime from "animejs";
	import {onMount} from 'svelte'
	const src = "https://data4.cupsell.pl/upload/generator/247026/640x420/4465398_print_1.png?resize=max_sizes&key=55f9a22768eed085006592c1174c0235";

// 	onMount(()=>{anime({
//   targets: '.papiez',
//   keyframes: [
//     {translateY: -40},
//     {translateX: 250},
//     {translateY: 40},
//     {translateX: 0},
//     {translateY: 0}
//   ],
//   duration: 4000,
//   easing: 'easeOutElastic(1, .8)',
//   loop: true


// });})

const spierdalaj =()=>{

  anime({
    targets:'.papiez',
    rotate:[0,360], 
    duration: 3000

  })
}

</script>
<div class='elo'><center>
<img {src} class='papiez' alt="elo" on:mouseover={spierdalaj} on:mouseleave={spierdalaj.pause}/></center>
</div>