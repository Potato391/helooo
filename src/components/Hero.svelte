<script>
    import Wrapper from "./Wrapper.svelte";
    import Header from "./Header.svelte";
    import Cta from "./CTA.svelte";

</script>

<Wrapper> 
<Header/>

<div class="flex flex-col gap-10 sm:flex-1 items-center justify-center pb:10 mt-44 sm:mt-0">
    <h2 class="text-5xl sm:text-6xl md:text-7xl lg:8xl max-w-[1200px] mx-auto w-full text-center font-semibold">
        Unlock <span class="text-indigo-400">Limitless</span> Access with Your own Proxy
    </h2>
    <p class="text-xl sm:text-2xl md:text-3xl lg:text-4xl text-center max-w-[1000px] mx-auto w-full">Discover the power of proxies. 
        <span class="italic"> Bypass restrictions, protect your privacy</span>
    </p>
    <Cta />
    <!-- <div class="flex items-center justify-center gap-2 text-base">
        <p>4.6</p>
        {#each [0,1,2,3,4] as index}
    <div class="grid place-items-center relative">
        <i class="fa-solid fa-star opacity-0"></i>
        <div class={"absolute top-0 left-0 grid place-items-center " + (index === 4 ? 'w-[60%] overflow-hidden' : "")}>
            <i class="fa-solid fa-star text-amber-400"></i>
        </div>
    </div>
{/each}

    </div>-->
</div>


</Wrapper>