<section class="max-w-[1200px] mx-auto px-4 py-20 grid md:grid-cols-2 gap-8">
    <!-- Left Column -->
    <div class="flex flex-col gap-6">
        <div class="bg-[#F7F7F5] rounded-xl p-8 h-[400px] relative overflow-hidden flex items-center justify-center">
            <!-- Review Card -->
            <div class="bg-white rounded-lg shadow-lg border border-gray-200 w-[320px] p-6 text-sm">
                <div class="text-center mb-6">
                    <div class="text-xs text-gray-500 mb-2">Review Session</div>
                    <div class="text-2xl font-bold text-notion-black mb-1">¿Qué te gustaría tomar?</div>
                    <button class="text-primary-600 text-xs hover:underline">Play audio</button>
                </div>
                
                <div class="space-y-3 mb-6">
                    <button class="w-full text-left p-3 rounded-lg border border-gray-200 hover:border-primary-400 hover:bg-primary-50 transition-colors">
                        What would you like to take?
                    </button>
                    <button class="w-full text-left p-3 rounded-lg border-2 border-primary-400 bg-primary-50">
                        What would you like to have?
                    </button>
                    <button class="w-full text-left p-3 rounded-lg border border-gray-200 hover:border-primary-400 hover:bg-primary-50 transition-colors">
                        What do you want to drink?
                    </button>
                </div>

                <div class="flex items-center justify-between text-xs text-gray-500">
                    <span>Due: Today</span>
                    <span>Confidence: 🟢 High</span>
                </div>
            </div>
        </div>
        <p class="text-lg text-notion-black">
            Smart reviews show exactly what you need, when you need it. No wasted time on words you already know.
        </p>
    </div>

    <!-- Right Column -->
    <div class="flex flex-col gap-6">
        <div class="bg-[#F7F7F5] rounded-xl p-8 h-[400px] relative overflow-hidden flex flex-col items-center justify-center gap-6">
             <div class="text-center max-w-xs">
                <div class="text-4xl font-bold text-notion-black mb-2">487</div>
                <div class="text-gray-500 mb-4">Words in Active Memory</div>
                
                <div class="grid grid-cols-3 gap-3 text-sm">
                    <div class="bg-white rounded-lg p-3 border border-gray-200">
                        <div class="font-bold text-green-600">234</div>
                        <div class="text-gray-500 text-xs">Mastered</div>
                    </div>
                    <div class="bg-white rounded-lg p-3 border border-gray-200">
                        <div class="font-bold text-blue-600">189</div>
                        <div class="text-gray-500 text-xs">Learning</div>
                    </div>
                    <div class="bg-white rounded-lg p-3 border border-gray-200">
                        <div class="font-bold text-orange-600">64</div>
                        <div class="text-gray-500 text-xs">Review</div>
                    </div>
                </div>
             </div>

             <div class="bg-white rounded-lg p-4 border border-gray-200 text-center max-w-xs w-full">
                <div class="text-xs text-gray-500 mb-1">Next Review</div>
                <div class="font-semibold text-notion-black">12 cards in 2 hours</div>
             </div>
        </div>
        <p class="text-lg text-notion-black">
            Built-in spaced repetition tracks your progress. The system adapts to how well you're learning.
        </p>
    </div>
</section>
