<script>
    import { Check, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Automate Every Step of<br />Fiscal Receiving
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: AI Validation -->
            <div class="group">
                <div class="mb-6 bg-black rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                    <!-- Mock Interface -->
                    <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3 border-b pb-2">
                            <div class="h-2 w-2 rounded-full bg-green-500"></div>
                            <span class="text-[10px] font-mono text-gray-500">NF-e Validation Engine</span>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center gap-2 text-xs text-green-700">
                                <Check size={12} /> <span class="text-gray-600">Validating tax rates...</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Checking PIS/COFINS</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Verifying CFOP codes</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Matching Purchase Order</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">AI Validation Engine</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Instantly validate incoming fiscal documents against your ERP data and tens of millions of Brazilian tax rules. Identify errors before they enter your system.
                </p>
            </div>

            <!-- Card 2: Supplier Portal -->
            <div class="group">
                <div class="mb-6 bg-black rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="text-[10px] text-gray-500 mb-2">Supplier Collaboration Hub</div>
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-black rounded flex items-center justify-center text-white text-[8px]">C</div>
                            <span class="text-[10px] text-gray-400">3 Pending Corrections</span>
                        </div>
                        <div class="space-y-2 border-t pt-2">
                            <div class="grid grid-cols-3 gap-2 text-[8px] text-gray-400 font-medium">
                                <div>Supplier</div>
                                <div class="col-span-2 text-right">Status</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> TechLog Ltda</div>
                                <div class="col-span-2 h-1.5 bg-green-100 rounded"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> Prime Goods</div>
                                <div class="col-span-2 h-1.5 bg-yellow-100 rounded w-2/3 ml-auto"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> Global Parts</div>
                                <div class="col-span-2 h-1.5 bg-red-100 rounded w-1/2 ml-auto"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Supplier Portal</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Centralize interactions with suppliers. Handle document submissions, mirrored documents, accounts-payable status, and messaging in one dedicated platform.
                </p>
            </div>

            <!-- Card 3: ERP Integration -->
            <div class="group">
                <div class="mb-6 bg-black rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-black rounded flex items-center justify-center text-white text-[8px]">ERP</div>
                            <span class="text-[10px] text-gray-500">Writing to SAP/Oracle...</span>
                        </div>
                        <div class="text-[9px] text-gray-600 mb-3 leading-relaxed">
                            Validation complete. Posting corrected fiscal data to your ERP system.
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-blue-500 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Fiscal_Entry_772.xml</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-blue-600 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">ERP_Posting_Log.txt</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">ERP Integration</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Seamlessly write corrected information back into your ERP. Compatible with major systems like SAP, Oracle, and Totvs, ensuring your records are always accurate.
                </p>
            </div>
        </div>
    </div>
</section>
