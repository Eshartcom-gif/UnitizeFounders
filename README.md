
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unitize | Institutional Grade Real Estate NFTs</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
        .glass-nav { background: rgba(15, 23, 42, 0.9); backdrop-filter: blur(12px); }
        .emerald-glow { box-shadow: 0 0 20px rgba(16, 185, 129, 0.2); }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <nav class="fixed w-full z-50 glass-nav border-b border-slate-800 text-white">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold tracking-tighter flex items-center">
                <div class="w-8 h-8 bg-emerald-500 rounded-lg mr-2 flex items-center justify-center">
                    <span class="text-slate-900 text-sm">U</span>
                </div>
                Unitize
            </div>
            
            <div class="hidden md:flex space-x-8 items-center font-medium text-slate-300">
                <a href="#home" class="hover:text-emerald-400 transition text-sm uppercase tracking-widest">Marketplace</a>
                <a href="#how-it-works" class="hover:text-emerald-400 transition text-sm uppercase tracking-widest">How It Works</a>
                <a href="#governance" class="hover:text-emerald-400 transition text-sm uppercase tracking-widest">Governance</a>
                <button onclick="connectWallet()" class="bg-emerald-500 hover:bg-emerald-600 text-slate-950 px-6 py-2 rounded-full font-bold transition emerald-glow">
                    Mint Founders Pass
                </button>
            </div>
        </div>
    </nav>

    <section id="home" class="relative bg-slate-900 pt-32 pb-24 lg:pt-52 lg:pb-40 overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 relative z-10 grid lg:grid-cols-2 gap-12 items-center">
            <div>
                <div class="inline-block px-4 py-1.5 rounded-full bg-emerald-500/10 border border-emerald-500/20 text-emerald-400 text-xs font-bold uppercase tracking-widest mb-6">
                    Live on Mainnet
                </div>
                <h1 class="text-5xl lg:text-7xl font-bold text-white leading-tight mb-6 tracking-tight">
                    Own the Future with <span class="text-emerald-500">Unitize Founders.</span>
                </h1>
                <p class="text-xl text-slate-400 mb-10 leading-relaxed max-w-xl">
                    Unlock fractional ownership of premier properties. The Unitize Founders NFT represents your stake in real-world assets, generating automated rental yields.
                </p>
                <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                    <button class="bg-emerald-500 text-center text-slate-950 px-8 py-4 rounded-xl font-bold text-lg hover:bg-emerald-600 transition shadow-xl shadow-emerald-500/10">Explore Properties</button>
                    <button class="border border-slate-700 text-center text-white px-8 py-4 rounded-xl font-bold text-lg hover:bg-slate-800 transition">View Whitepaper</button>
                </div>
            </div>
            <div class="relative group">
                <div class="absolute -inset-1 bg-gradient-to-r from-emerald-500 to-blue-600 rounded-3xl blur opacity-25 group-hover:opacity-50 transition duration-1000 group-hover:duration-200"></div>
                <div class="relative bg-slate-800 border border-slate-700 p-8 rounded-3xl shadow-2xl">
                    <div class="aspect-square rounded-2xl bg-gradient-to-br from-slate-700 to-slate-900 mb-6 flex items-center justify-center overflow-hidden">
                        <div class="text-center">
                            <div class="text-6xl mb-4">🏠</div>
                            <p class="text-emerald-500 font-mono text-sm tracking-tighter">UNITIZE_FOUNDERS_#001</p>
                        </div>
                    </div>
                    <div class="flex justify-between items-center">
                        <div>
                            <p class="text-slate-400 text-xs uppercase font-bold mb-1">Floor Price</p>
                            <p class="text-2xl font-bold text-white">0.85 ETH</p>
                        </div>
                        <div class="text-right">
                            <p class="text-slate-400 text-xs uppercase font-bold mb-1">Global Yield</p>
                            <p class="text-2xl font-bold text-emerald-500">9.2% APR</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="governance" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center max-w-3xl mx-auto mb-20">
                <h2 class="text-4xl font-bold mb-6">Unitize Revenue Distribution</h2>
                <p class="text-slate-600 text-lg">Our smart contracts ensure that rental income is distributed with 100% transparency. Here is how every dollar of rent is handled.</p>
            </div>
            
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div class="space-y-4">
                    <div class="p-6 rounded-2xl bg-slate-50 flex items-center justify-between border-l-4 border-emerald-500 shadow-sm">
                        <span class="font-bold text-slate-700">Unitize Founders Holders</span>
                        <span class="text-2xl font-bold text-emerald-600">80%</span>
                    </div>
                    <div class="p-6 rounded-2xl bg-slate-50 flex items-center justify-between border-l-4 border-slate-300">
                        <span class="font-medium text-slate-600">Property Maintenance & Tax</span>
                        <span class="text-xl font-bold text-slate-800">15%</span>
                    </div>
                    <div class="p-6 rounded-2xl bg-slate-50 flex items-center justify-between border-l-4 border-slate-300">
                        <span class="font-medium text-slate-600">Platform & Audit Fees</span>
                        <span class="text-xl font-bold text-slate-800">5%</span>
                    </div>
                </div>

                <div class="bg-slate-900 p-10 rounded-3xl text-white">
                    <h3 class="text-2xl font-bold mb-4 italic">"Institutional Grade Compliance"</h3>
                    <p class="text-slate-400 mb-6">
                        Unlike traditional real estate funds, Unitize utilizes the <strong>Unitize Founders NFT</strong> to bypass middlemen. Rental profits are converted to USDC and pushed to the dividend pool every 30 days.
                    </p>
                    <ul class="space-y-4">
                        <li class="flex items-start">
                            <svg class="w-6 h-6 text-emerald-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                            <span>Audited Smart Contracts</span>
                        </li>
                        <li class="flex items-start">
                            <svg class="w-6 h-6 text-emerald-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                            <span>Legal Custodianship of Physical Titles</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-slate-900 text-white pt-20 pb-10 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid md:grid-cols-2 gap-12 mb-16">
                <div>
                    <div class="text-2xl font-bold tracking-tighter mb-6">Unitize</div>
                    <p class="text-slate-400 max-w-md">The premier platform for fractionalizing world-class real estate. Invest alongside the best, with the transparency of the blockchain.</p>
                </div>
                <div class="flex flex-col md:items-end">
                    <h4 class="font-bold mb-4 uppercase text-xs tracking-widest text-emerald-500">Legal & Compliance</h4>
                    <p class="text-xs text-slate-500 text-right leading-relaxed max-w-sm">
                        Real estate investing involves risk. The Unitize Founders NFT is a digital representation of beneficial interest. Please read our full Risk Disclosure before participating in the Unitize ecosystem.
                    </p>
                </div>
            </div>
            <div class="text-center text-slate-600 text-sm border-t border-slate-800 pt-8">
                &copy; 2026 Unitize Platform. All rights reserved.
            </div>
        </div>
    </footer>

    <script>
        function connectWallet() {
            console.log("Unitize: Initiating wallet connection...");
            alert("Connecting to Wallet to mint Unitize Founders NFT...");
        }
    </script>
</body>
</html>
