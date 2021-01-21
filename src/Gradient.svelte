<script>
  export let gradient = 'linear-gradient(90deg, rgb(255, 167, 69) -45%, rgb(254, 134, 159) 10%, rgb(239, 122, 200) 25%, rgb(160, 131, 237) 60%, rgb(67, 174, 255) 80%)';
  export let size = '7.5rem';
  export let style = '';
</script>

<p 
  class="gradient text" 
  style="background-image:{gradient}; opacity:1; font-size:{size}; {style}">
  <slot />
</p>

<style>
 .gradient {
  background:linear-gradient(0deg, #ffa745 15%, #fe869f 50%, #ef7ac8 75%, #a083ed 90%, #43aeff 110%);
  -webkit-text-fill-color: transparent;
  text-fill-color: transparent;
  -webkit-background-clip: text;
  background-clip: text
 }

 .text {
   font-weight: 700;
   letter-spacing: -.018em;
   line-height: 1;
   font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
 }
</style>