<template>
  <div class="flex-column content-center justify-center align-middle">
    <video-background class="z-0 fixed"
    src="desktop.mp4"
    poster="desktop.png"
    :sources="[
        {src: 'desktop.mp4', res: 900, autoplay: true,  poster: 'mobile_vert_poster_1.png'}, 
        {src: 'mobile_vert_1.mp4', res: 638, autoplay: true, poster: 'mobile_vert_poster_1.png'}
    ]"
    style=" height: 100vh;"
    overlay="linear-gradient(45deg, rgba(38,66,71,0.577468487394958) 0%, rgba(19,37,50,0.9360119047619048) 100%)" 
>
    <h1 class="text-5xl text-white text-center">Hero headline goes here</h1>
</video-background>
  </div>
</template>

<script>


export default {

}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

</style>
