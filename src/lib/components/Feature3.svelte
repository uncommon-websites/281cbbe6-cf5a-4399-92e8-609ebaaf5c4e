<section class="max-w-[1200px] mx-auto px-4 py-20">
    <div class="grid md:grid-cols-2 gap-12 items-center">
        <!-- Left Content -->
        <div>
            <!-- Audio Icons -->
            <div class="relative w-24 h-24 mb-8">
                <svg width="60" height="60" viewBox="0 0 24 24" fill="none" class="absolute left-0 top-0 transform -rotate-6">
                     <polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5" stroke="#EF4444" stroke-width="1.5" fill="none"></polygon>
                     <rect x="1" y="1" width="22" height="22" rx="2" stroke="#EF4444" stroke-width="1" stroke-dasharray="2 2"></rect>
                </svg>
                 <svg width="60" height="60" viewBox="0 0 24 24" fill="none" class="absolute left-10 top-0 transform rotate-12">
                     <circle cx="12" cy="12" r="10" stroke="#3B82F6" stroke-width="1.5"></circle>
                     <path d="M9 9h6v6H9z" stroke="#3B82F6" stroke-width="1.5" fill="none"></path>
                     <circle cx="12" cy="12" r="11" stroke="#3B82F6" stroke-width="1" stroke-dasharray="2 2"></circle>
                </svg>
            </div>

            <h2 class="text-4xl md:text-5xl font-bold tracking-tight text-notion-black mb-12 text-balance leading-[1.1]">
                Listen first. Speak sooner.
            </h2>

            <div class="space-y-8">
                <div class="flex gap-4">
                    <div class="w-6 h-6 flex items-center justify-center text-primary-600">
                        <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5"></polygon>
                            <path d="M19.07 4.93a10 10 0 0 1 0 14.14"></path>
                        </svg>
                    </div>
                    <div>
                        <h3 class="font-semibold text-notion-black text-lg">Audio-first approach</h3>
                        <p class="text-notion-gray mt-1 leading-relaxed">Train your ear before your eyes. The same method Maxi used to master Swedish and German.</p>
                    </div>
                </div>
                 <div class="flex gap-4">
                    <div class="w-6 h-6 flex items-center justify-center text-primary-600">
                        <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path>
                        </svg>
                    </div>
                    <div>
                        <h3 class="font-semibold text-notion-black text-lg">Native speaker recordings</h3>
                        <p class="text-notion-gray mt-1 leading-relaxed">Every dialogue recorded by native Spanish speakers. Learn the rhythm and flow of real conversations.</p>
                    </div>
                </div>
                 <div class="flex gap-4">
                    <div class="w-6 h-6 flex items-center justify-center text-primary-600">
                        <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline>
                        </svg>
                    </div>
                    <div>
                        <h3 class="font-semibold text-notion-black text-lg">Pronunciation practice</h3>
                        <p class="text-notion-gray mt-1 leading-relaxed">Repeat after native speakers. Build muscle memory for authentic pronunciation.</p>
                    </div>
                </div>
                 <div class="flex gap-4">
                    <div class="w-6 h-6 flex items-center justify-center text-primary-600">
                        <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path>
                            <polyline points="14 2 14 8 20 8"></polyline>
                        </svg>
                    </div>
                    <div>
                        <h3 class="font-semibold text-notion-black text-lg">Transcripts & notes</h3>
                        <p class="text-notion-gray mt-1 leading-relaxed">Full transcripts with cultural context and grammar notes when you need them.</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Right Visual -->
        <div class="bg-[#F7F7F5] rounded-xl p-8 h-[600px] flex items-center justify-center overflow-hidden">
            <div class="bg-white rounded-lg shadow-xl border border-gray-200 w-full max-w-md p-6">
                <!-- Audio Player -->
                <div class="mb-6">
                    <div class="flex items-center justify-between mb-3">
                        <div class="text-sm font-medium text-notion-black">Chapter 7: Coffee Shop</div>
                        <div class="text-xs text-gray-500">0:45 / 2:30</div>
                    </div>
                    
                    <!-- Waveform visualization -->
                    <div class="flex items-center gap-1 h-16 mb-4">
                        {#each Array(40) as _, i}
                            <div class="flex-1 bg-primary-200 rounded-full" style="height: {Math.random() * 100}%"></div>
                        {/each}
                    </div>
                    
                    <!-- Playback controls -->
                    <div class="flex items-center justify-center gap-4">
                        <button class="w-10 h-10 rounded-full border border-gray-300 flex items-center justify-center hover:bg-gray-50">
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <polygon points="19 20 9 12 19 4 19 20"></polygon>
                                <line x1="5" y1="19" x2="5" y2="5"></line>
                            </svg>
                        </button>
                        <button class="w-14 h-14 rounded-full bg-primary-600 flex items-center justify-center hover:bg-primary-700 text-white">
                            <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor">
                                <polygon points="5 3 19 12 5 21 5 3"></polygon>
                            </svg>
                        </button>
                        <button class="w-10 h-10 rounded-full border border-gray-300 flex items-center justify-center hover:bg-gray-50">
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <polygon points="5 4 15 12 5 20 5 4"></polygon>
                                <line x1="19" y1="5" x2="19" y2="19"></line>
                            </svg>
                        </button>
                    </div>
                </div>

                <!-- Transcript -->
                <div class="border-t border-gray-100 pt-6">
                    <div class="text-xs font-medium text-gray-500 mb-3">TRANSCRIPT</div>
                    <div class="space-y-3 text-sm">
                        <div class="p-3 bg-gray-50 rounded-lg">
                            <div class="font-medium text-notion-black mb-1">Ana:</div>
                            <div class="text-notion-gray">"Buenos días. ¿Qué te gustaría tomar?"</div>
                            <div class="text-xs text-gray-500 italic mt-1">Good morning. What would you like to have?</div>
                        </div>
                        <div class="p-3 bg-primary-50 rounded-lg">
                            <div class="font-medium text-notion-black mb-1">You:</div>
                            <div class="text-notion-gray">"Un café con leche, por favor."</div>
                            <div class="text-xs text-gray-500 italic mt-1">A coffee with milk, please.</div>
                        </div>
                    </div>
                </div>

                <!-- Speed controls -->
                <div class="mt-6 flex items-center justify-between text-xs">
                    <button class="px-3 py-1 rounded-full border border-gray-300 hover:bg-gray-50">0.75x</button>
                    <button class="px-3 py-1 rounded-full bg-primary-100 text-primary-700 font-medium">1.0x</button>
                    <button class="px-3 py-1 rounded-full border border-gray-300 hover:bg-gray-50">1.25x</button>
                    <button class="px-3 py-1 rounded-full border border-gray-300 hover:bg-gray-50">1.5x</button>
                </div>
            </div>
        </div>
    </div>
</section>
