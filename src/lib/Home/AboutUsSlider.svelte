<script lang="ts">
    import { Splide, SplideSlide } from '@splidejs/svelte-splide';
    import '@splidejs/svelte-splide/css';

    import sliderImage1 from "$lib/assets/IMG-20240323-WA0014.jpg"
</script>

<div>
    <Splide aria-label="..." options={{
        type: "slide",
        speed: 500,
        rewindByDrag: true,
        autoplay: true,
        interval: 3000,
        pauseOnHover: true,
        rewind: true
    }}>
        <SplideSlide>
            <img src={sliderImage1} alt="Image 1" class="m-auto rounded-lg drop-shadow-lg w-full h-96 object-cover object-center"/>
        </SplideSlide>
        <SplideSlide>
            <img src="https://fakeimg.pl/400x200" alt="Image 2" class="m-auto rounded-lg drop-shadow-lg w-full h-96 object-cover object-center"/>
        </SplideSlide>
        <SplideSlide>
            <img src="https://fakeimg.pl/500x300" alt="Image 2" class="m-auto rounded-lg drop-shadow-lg w-full h-96 object-cover object-center"/>
        </SplideSlide>
    </Splide>
</div>