<template>

<div class="relative h-[800px] mt-0 z-10 header-img">
   <div>
    <img src="https://i.ibb.co/MGXRBFt/FORSIDE-h-nd.png" class="left-[325px] h-[500px] scale-[2.0] absolute -translate-y-16 z-20" alt="">
   </div>
   <div class="w-full h-[400px] bg-[#256c2b] absolute bottom-0 ">
    <div class=" bg-[#000000] w-[10%] h-[600px] top-0 absolute z-30 opacity-20 clip">
   </div>
   <img src="https://i.ibb.co/q9Jd6px/Jesper-cropped.png" alt="" class="h-96 absolute bottom-0 z-50 right-0">
   <div class=" bg-gradient-header w-[100%] h-[60px] absolute bottom-0 z-30"></div>
   
</div>
   <div class="flex justify-end">
    <div class="bg-[#3a5246] h-[500px] w-[90%] absolute bottom-0 z-10 rounded-sm ">
        <article class="flex flex-col gap-10 justify-center ml-28 mt-36 text-white">
        <h1 class="text-5xl font-semibold tracking-wider">Dialog er nøgleordet...</h1>
        <p class="text-xl max-w-[700px]">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean ut malesuada nulla, at eleifend nulla. Donec luctus rutrum turpis malesuada condimentum. Donec suscipit elit a nisl laoreet consectetur. Integer sed blandit ipsum. Pellentesque porttitor ligula arcu, eget suscipit mauris consectetur ut.</p>
        </article>
        <article class="flex flex-col items-end w-[80%] -translate-y-5 gap-3 font-semibold italic text-[#151414]">
            <p>Jesper Zangenberg<br> Stifter & CEO </p>
            <p>Ring til Jesper: <a class="not-italic underline underline-offset-4" href="telto: +45 12 34 56 78 ">+45 12 34 56 78 </a></p>
        </article>
    </div>
   </div>
</div>
</template>

<script>
export default {

}
</script>

<style>
.clip {
    clip-path: polygon(1% 0, 100% 0, 100% 87%, 0% 100%);
}
.header-img {
    background-image: url('https://i.ibb.co/f0Fg0Xw/FORSIDE-BILLEDE-2.jpg');
    background-size: contain;
    background-position: top;
}

.bg-gradient-header {
    background: linear-gradient(to bottom, rgba(37, 108, 43, 1), rgba(255, 255, 255, 0.1));
}
</style>