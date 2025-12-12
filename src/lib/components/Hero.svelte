<script>
    // Hero Component
</script>

<section class="pt-20 pb-16 px-4 flex flex-col items-center text-center max-w-[1200px] mx-auto">
    <!-- Spanish Learning Icon -->
    <div class="mb-8 relative">
        <svg width="64" height="64" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="text-notion-black w-20 h-20">
            <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
            <path d="M2 17l10 5 10-5"></path>
            <path d="M2 12l10 5 10-5"></path>
        </svg>
    </div>

    <h1 class="text-5xl md:text-6xl lg:text-7xl font-bold tracking-tight text-notion-black mb-6 max-w-4xl text-balance leading-[1.1]">
        Learn Spanish through <br class="hidden md:block" /> stories, not drills
    </h1>

    <p class="text-xl text-notion-gray max-w-2xl mb-10 text-balance leading-relaxed">
        Master conversational Spanish in 100 days with story-driven dialogues and proven spaced repetition. Built by a native speaker who learned Swedish and German the same way.
    </p>

    <button class="bg-notion-black text-white text-lg font-medium px-6 py-3 rounded-[6px] hover:bg-notion-gray transition-colors mb-20">
        Join Founder Program - $10
    </button>

    <!-- Learning Journey Visual -->
    <div class="w-full bg-[#F7F7F5] rounded-xl shadow-2xl border border-gray-200 overflow-hidden p-8 md:p-12">
        <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
            <!-- Story-Driven -->
            <div class="bg-white rounded-lg p-6 shadow-sm border border-gray-100">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-4">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600">
                        <path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"></path>
                        <path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"></path>
                    </svg>
                </div>
                <h3 class="font-semibold text-lg text-notion-black mb-2">86 Connected Stories</h3>
                <p class="text-sm text-notion-gray">Follow branching narratives from coffee shops to anime festivals. Real conversations, not random phrases.</p>
            </div>

            <!-- Spaced Repetition -->
            <div class="bg-white rounded-lg p-6 shadow-sm border border-gray-100">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-4">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600">
                        <circle cx="12" cy="12" r="10"></circle>
                        <polyline points="12 6 12 12 16 14"></polyline>
                    </svg>
                </div>
                <h3 class="font-semibold text-lg text-notion-black mb-2">Smart Spaced Repetition</h3>
                <p class="text-sm text-notion-gray">Review exactly what you need, when you need it. Built-in system that adapts to your progress.</p>
            </div>

            <!-- Audio-First -->
            <div class="bg-white rounded-lg p-6 shadow-sm border border-gray-100">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-4">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600">
                        <polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5"></polygon>
                        <path d="M19.07 4.93a10 10 0 0 1 0 14.14"></path>
                        <path d="M15.54 8.46a5 5 0 0 1 0 7.07"></path>
                    </svg>
                </div>
                <h3 class="font-semibold text-lg text-notion-black mb-2">Audio-First Method</h3>
                <p class="text-sm text-notion-gray">Listen first, speak sooner. The same method Maxi used to master Swedish and German.</p>
            </div>
        </div>

        <!-- Progress Bar Example -->
        <div class="mt-12 max-w-3xl mx-auto bg-white rounded-lg p-6 shadow-sm border border-gray-100">
            <div class="flex items-center justify-between mb-3">
                <span class="text-sm font-medium text-notion-black">Your 100-Day Journey</span>
                <span class="text-sm text-notion-gray">Day 23 of 100</span>
            </div>
            <div class="w-full bg-gray-200 rounded-full h-3 mb-4">
                <div class="bg-primary-600 h-3 rounded-full" style="width: 23%"></div>
            </div>
            <div class="grid grid-cols-3 gap-4 text-center text-sm">
                <div>
                    <div class="font-bold text-2xl text-notion-black">23</div>
                    <div class="text-gray-500">Episodes</div>
                </div>
                <div>
                    <div class="font-bold text-2xl text-notion-black">487</div>
                    <div class="text-gray-500">Words Learned</div>
                </div>
                <div>
                    <div class="font-bold text-2xl text-notion-black">A1</div>
                    <div class="text-gray-500">Current Level</div>
                </div>
            </div>
        </div>
    </div>
</section>
