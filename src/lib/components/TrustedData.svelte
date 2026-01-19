<script>
    const partners = [
        { name: "Your ERP Data", icon: "🏢" },
        { name: "SAP", icon: "S", color: "bg-blue-700" },
        { name: "Oracle", icon: "O", color: "bg-red-700" },
        { name: "Totvs", icon: "T", color: "bg-pink-600" },
        { name: "Microsoft Dynamics", icon: "M", color: "bg-blue-500" },
        { name: "Sefaz (National)", icon: "🏛️" },
        { name: "2,800+ Municipalities", icon: "🏙️" },
        { name: "Receita Federal", icon: "🇧🇷" },
        { name: "Inbound NF-e", icon: "📄" },
        { name: "Inbound CT-e", icon: "🚚" },
        { name: "Inbound NFS-e", icon: "🛠️" },
        { name: "Supplier Data", icon: "🤝" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">Trusted Integrations</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                We integrate with your existing ERP and connect directly to Brazilian tax authorities. Camu acts as a secure layer, ensuring every document is validated against the latest national and municipal regulations.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            {#each partners as partner}
                <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg hover:bg-gray-100 transition-colors cursor-default">
                    <div class={`h-8 w-8 rounded flex items-center justify-center text-white text-xs font-bold ${partner.color ? partner.color : 'bg-gray-200 text-gray-600'}`}>
                        {partner.icon}
                    </div>
                    <span class="text-sm font-medium text-gray-900">{partner.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>
