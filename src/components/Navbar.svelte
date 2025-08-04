<script lang="ts">
	import BrandLogo from '../icons/BrandLogo.svelte';

	// Navbar component
</script>

<nav class="bg-[#010101 md:mt-[81px] mt-[76px] z-10">
	<div class="mx-auto flex justify-between items-center md:items-start h-[76px] md:h-[76px] px-7 md:px-[211px]">
		<div class='md:hidden'></div>

        <div class="flex items-center h-[46px] md:h-[74px]">
			<div class="scale-[0.62] md:scale-100">
				<BrandLogo />
			</div>
		</div>
        <div class="hidden md:flex items-start gap-6">
            <a href="#" class="h-[22px] flex items-center justify-center hover:text-white transition-colors" style="font-family: 'Figtree', sans-serif; font-weight: 600; font-size: 18px; line-height: 100%; letter-spacing: 0%; color: #A9A9A9 !important; white-space: nowrap;">About us</a>
            <a href="#" class="h-[22px] flex items-center justify-center hover:text-white transition-colors" style="font-family: 'Figtree', sans-serif; font-weight: 600; font-size: 18px; line-height: 100%; letter-spacing: 0%; color: #A9A9A9 !important; white-space: nowrap;">Contact</a>
        </div>
        <button class="md:hidden text-white" aria-label="Menu">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M3 12H21" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                <path d="M3 6H21" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                <path d="M3 18H21" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
        </button>
	</div>
</nav>
