<script>
    // Icons replaced with CSS shapes for pixel-perfect custom visuals
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                AI Built for the Complexity<br />of Brazilian Tax
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Integrations -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">ERP Connectivity</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-4">
                        {#each [1, 2, 3, 4, 5, 6] as i}
                            <div class="h-10 w-10 bg-white rounded-full shadow-sm flex items-center justify-center text-gray-400">
                                <div class="h-4 w-4 bg-gray-200 rounded-sm"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Connect seamlessly with SAP, Oracle, Totvs, and other major ERPs. Camu reads and writes data directly to your system of record.
                </p>
            </div>

            <!-- Validation Rules -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">10M+ Tax Rules</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px] space-y-2">
                        <div class="h-2 bg-gray-100 rounded w-1/3 mb-4"></div>
                        {#each [1, 2, 3, 4, 5] as i}
                            <div class="flex items-center gap-2">
                                <div class="h-2 w-2 rounded-full bg-green-500"></div>
                                <div class="h-1.5 bg-gray-100 rounded w-3/4"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Our AI engine validates every document against national and municipal rules across 2,800+ cities in Brazil.
                </p>
            </div>

            <!-- Supplier Collaboration -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Supplier Portal</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="flex -space-x-2">
                        <div class="h-10 w-10 rounded-full bg-blue-100 border-2 border-white flex items-center justify-center text-blue-600 text-xs">S1</div>
                        <div class="h-10 w-10 rounded-full bg-green-100 border-2 border-white flex items-center justify-center text-green-600 text-xs">S2</div>
                        <div class="h-10 w-10 rounded-full bg-purple-100 border-2 border-white flex items-center justify-center text-purple-600 text-xs">S3</div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Centralize all supplier interactions. Reduce email back-and-forth by allowing suppliers to track status and fix errors directly.
                </p>
            </div>

            <!-- AI-Powered Corrections -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Auto-Corrections</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="relative">
                        <div class="flex justify-center gap-4 mb-4">
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                        </div>
                        <div class="flex justify-center mb-4">
                            <div class="h-8 w-px bg-gray-300"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-8 w-8 bg-black rounded flex items-center justify-center text-white text-xs">AI</div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Camu doesn't just find errors; it proposes and executes corrections for common issues like incorrect tax rates or missing lot info.
                </p>
            </div>

            <!-- Governance & Audit -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Governance & Audit</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px]">
                        <div class="flex justify-between mb-4">
                            <div class="text-[10px] font-bold">LOG</div>
                            <div class="text-[10px] font-bold">100%</div>
                        </div>
                        <div class="space-y-2">
                            <div class="h-px bg-gray-100 w-full"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-1/2"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-3/4"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-2/3"></div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Full activity histories and configurable approval workflows give your tax and finance teams complete control and visibility.
                </p>
            </div>

            <!-- Analytics & Insights -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Fiscal Analytics</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-1">
                        {#each [1, 2, 3, 4, 5, 6, 7, 8, 9] as i}
                            <div class={`h-8 w-8 border border-gray-200 ${i === 5 ? 'bg-black flex items-center justify-center' : 'bg-white'}`}>
                                {#if i === 5}
                                    <div class="h-2 w-2 bg-white rounded-full"></div>
                                {/if}
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Surface recurring error patterns and identify fiscal optimization opportunities with our built-in analytics dashboard.
                </p>
            </div>
        </div>
    </div>
</section>
