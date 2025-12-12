<script lang="ts">
	const links = {
		Product: ["How it works", "Methodology", "Founder Program", "Roadmap"],
		Resources: ["Blog", "Origin Story", "Weekly Updates", "FAQ"],
		Community: ["Twitter/X", "Founder Community", "Contact Maxi"],
		Legal: ["Terms & Privacy", "Refund Policy"]
	};
</script>

<footer class="border-t border-notion-border py-16 px-4 md:px-8 lg:px-16 bg-white text-[14px]">
	<div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-6 gap-8">
		<div class="lg:col-span-2 flex flex-col gap-6">
			<div class="flex items-center gap-2">
				<span class="font-bold text-2xl tracking-tight text-notion-black">Formula 100</span>
			</div>
			
			<p class="text-notion-gray text-sm leading-relaxed">
				Learn conversational Spanish through story-driven dialogues and proven spaced repetition. Built by Maxi, a native speaker who mastered Swedish and German the same way.
			</p>
			
			<div class="flex gap-4 text-notion-gray">
				<!-- Social Icons -->
				<a href="https://twitter.com/_onmax" target="_blank" aria-label="Twitter"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 4s-.7 2.1-2 3.4c1.6 10-9.4 17.3-18 11.6 2.2.1 4.4-.6 6-2C3 15.5.5 9.6 3 5c2.2 2.6 5.6 4.1 9 4-.9-4.2 4-6.6 7-3.8 1.1 0 3-1.2 3-1.2z"></path></svg></a>
			</div>

            <div class="mt-auto pt-8 text-gray-500 text-xs">
                <p class="mt-4">© 2025 Formula 100. Built by @_onmax</p>
            </div>
		</div>

		{#each Object.entries(links) as [category, items]}
			<div class="flex flex-col gap-3">
				<h3 class="font-semibold text-notion-black mb-1">{category}</h3>
				{#each items as item}
					<a href="#" class="text-notion-gray hover:text-primary-600 hover:underline transition-colors">{item}</a>
				{/each}
			</div>
		{/each}
	</div>
</footer>
