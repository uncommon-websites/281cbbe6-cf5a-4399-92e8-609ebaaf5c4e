<script>
    // Testimonials Component
    const testimonials = [
        {
            name: "Sarah Chen",
            handle: "Early Founder",
            text: "Finally, a Spanish course that doesn't feel like homework. The stories actually make me want to keep going every day."
        },
        {
            name: "Marcus Rodriguez",
            handle: "Language Learner",
            text: "I tried Duolingo for 6 months and barely progressed. Formula 100's story approach clicked immediately."
        },
        {
            name: "Emma Thompson",
            handle: "Founder Program",
            text: "The spaced repetition is genius. I'm actually remembering conversations, not just memorizing random words."
        },
        {
            name: "David Kim",
            handle: "Beta Tester",
            text: "Built by someone who actually learned languages this way. You can tell Maxi knows what works."
        }
    ];
</script>

<section class="py-16 overflow-hidden">
    <div class="flex gap-6 overflow-x-auto px-4 pb-8 md:justify-center no-scrollbar snap-x">
        {#each testimonials as t}
            <div class="flex-none w-[300px] md:w-[350px] p-6 bg-white border border-gray-100 rounded-xl shadow-sm snap-center">
                <div class="flex flex-col gap-4 h-full">
                    <div>
                        <div class="font-medium text-notion-black">{t.name}</div>
                        <div class="text-gray-400 text-sm">{t.handle}</div>
                    </div>
                    <p class="text-notion-gray text-[15px] leading-relaxed">
                        {t.text}
                    </p>
                </div>
            </div>
        {/each}
        <!-- Add a fade effect or just let it scroll. The screenshot shows them cut off on the right, implying scroll or just a grid. -->
    </div>
</section>

<style>
    .no-scrollbar::-webkit-scrollbar {
        display: none;
    }
    .no-scrollbar {
        -ms-overflow-style: none;
        scrollbar-width: none;
    }
</style>
