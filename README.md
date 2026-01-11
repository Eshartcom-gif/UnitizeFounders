
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unitize | Perpetual Real Estate Ecosystem</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
        .nav-blur { backdrop-filter: blur(12px); background: rgba(15, 23, 42, 0.9); }
        .emerald-glow { box-shadow: 0 0 40px rgba(16, 185, 129, 0.2); }
        .glass-card { background: rgba(255, 255, 255, 0.03); border: 1px solid rgba(255, 255, 255, 0.1); backdrop-filter: blur(10px); }
        .bg-grid { background-image: radial-gradient(circle at 2px 2px, rgba(16, 185, 129, 0.05) 1px, transparent 0); background-size: 40px 40px; }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 bg-grid">

    <nav id="navbar" class="fixed w-full z-50 transition-all duration-300 text-white">
        <div class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center">
            <a href="#home" class="flex items-center group">
                <img src="https://i.ibb.co/Y4WHZtLz/1768162855762.png" alt="Unitize Logo" class="h-8 w-auto mr-3">
                <span class="text-2xl font-bold tracking-tighter">Unitize</span>
            </a>
            <div class="hidden lg:flex space-x-6 items-center font-medium text-slate-300">
                <a href="#loop" class="hover:text-emerald-400 transition text-xs uppercase tracking-widest">The Loop</a>
                <a href="#legal" class="hover:text-emerald-400 transition text-xs uppercase tracking-widest">Legal</a>
                <a href="#tech" class="hover:text-emerald-400 transition text-xs uppercase tracking-widest">Technology</a>
                <a href="#faq" class="hover:text-emerald-400 transition text-xs uppercase tracking-widest">FAQ</a>
                <a href="https://eshartcom-gif.github.io/Unitize-Whitepaper/" class="bg-slate-800 border border-slate-700 px-4 py-2 rounded-lg hover:bg-slate-700 transition text-xs">Full Whitepaper</a>
                <button onclick="connectWallet()" class="bg-emerald-500 hover:bg-emerald-600 text-slate-950 px-6 py-2 rounded-full font-bold transition emerald-glow shadow-lg shadow-emerald-500/20">Join Squad</button>
            </div>
        </div>
    </nav>

    <section id="home" class="relative bg-slate-900 pt-40 pb-32 lg:pt-52 lg:pb-48 overflow-hidden">
        <div class="absolute top-0 left-1/4 w-[500px] h-[500px] bg-emerald-500/10 blur-[150px] rounded-full"></div>
        <div class="max-w-7xl mx-auto px-6 relative z-10 grid lg:grid-cols-2 gap-16 items-center">
            <div>
                <div class="inline-block px-4 py-1.5 rounded-full bg-emerald-500/10 border border-emerald-500/20 text-emerald-400 text-xs font-bold uppercase tracking-widest mb-8">
                    Perpetual Real Estate Development
                </div>
                <h1 class="text-6xl lg:text-8xl font-bold text-white leading-[1.1] mb-8 tracking-tighter">
                    Wealth, <br><span class="text-emerald-500 italic">Built to Last.</span>
                </h1>
                <p class="text-xl text-slate-400 mb-12 leading-relaxed max-w-xl font-light">
                    The Unitize Squad NFT is more than a digital asset—it is a stake in a self-funding real estate development engine that buys land and builds homes in a perpetual loop.
                </p>
                <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-6">
                    <button class="bg-emerald-500 text-slate-950 px-10 py-5 rounded-2xl font-bold text-xl hover:bg-emerald-600 transition shadow-2xl shadow-emerald-500/20">Mint Your NFT</button>
                    <a href="#loop" class="border border-slate-700 text-white px-10 py-5 rounded-2xl font-bold text-xl hover:bg-slate-800 transition text-center flex items-center justify-center">Explore Ecosystem</a>
                </div>
            </div>
            
            <div class="relative">
                <div class="absolute -inset-4 bg-emerald-500/20 blur-3xl opacity-50"></div>
                <div class="relative glass-card p-10 rounded-[3rem] border border-white/10 shadow-2xl">
                    <div class="aspect-square rounded-3xl bg-slate-950 mb-8 border border-white/5 flex items-center justify-center">
                         <img src="https://i.ibb.co/Y4WHZtLz/1768162855762.png" alt="Squad Asset" class="w-32 h-auto grayscale brightness-200 opacity-80">
                    </div>
                    <div class="flex justify-between items-end">
                        <div>
                            <p class="text-emerald-500 font-mono text-sm tracking-widest mb-1">UNITIZE_SQUAD_001</p>
                            <h3 class="text-3xl font-bold text-white tracking-tight">Genesis Lot</h3>
                        </div>
                        <div class="text-right">
                            <p class="text-slate-500 text-xs font-bold uppercase tracking-widest mb-1">Est. Build Yield</p>
                            <p class="text-3xl font-bold text-emerald-400">22.4%</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-24 bg-white border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-6 grid lg:grid-cols-2 gap-20">
            <div>
                <h2 class="text-4xl font-bold mb-6 text-slate-900 tracking-tight">Breaking the Real Estate Monopoly</h2>
                <p class="text-slate-600 text-lg leading-relaxed mb-8">
                    Traditional property investment is designed for the elite. High capital barriers, extreme illiquidity, and crushing administrative management make it impossible for most to build real-world wealth. 
                </p>
                <div class="grid grid-cols-2 gap-6">
                    <div class="p-6 bg-slate-50 rounded-2xl border border-slate-100">
                        <p class="text-2xl font-bold text-slate-900 mb-2">92%</p>
                        <p class="text-sm text-slate-500">Retail investors priced out of luxury development</p>
                    </div>
                    <div class="p-6 bg-slate-50 rounded-2xl border border-slate-100">
                        <p class="text-2xl font-bold text-slate-900 mb-2">120 Days</p>
                        <p class="text-sm text-slate-500">Average liquidity period for traditional real estate</p>
                    </div>
                </div>
            </div>
            <div class="bg-slate-900 rounded-[2.5rem] p-12 text-white flex flex-col justify-center">
                <h3 class="text-2xl font-bold mb-6 italic">"The Unitize Solution"</h3>
                <p class="text-slate-400 mb-8 text-lg">We use the power of the Squad to purchase raw land at scale, eliminating the middleman and returning the profit of the 'build' directly to you through the blockchain.</p>
                <ul class="space-y-4">
                    <li class="flex items-center text-emerald-400"><span class="mr-3">✓</span> Instant Liquidity via NFT Marketplace</li>
                    <li class="flex items-center text-emerald-400"><span class="mr-3">✓</span> Fully Managed On-Site Construction</li>
                    <li class="flex items-center text-emerald-400"><span class="mr-3">✓</span> Direct Stablecoin Yield Distributions</li>
                </ul>
            </div>
        </div>
    </section>

    <section id="loop" class="py-24 bg-slate-50 relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-20">
                <h2 class="text-5xl font-bold mb-4 tracking-tighter">The Flywheel Effect</h2>
                <p class="text-slate-500 max-w-2xl mx-auto text-lg leading-relaxed">Most projects have an exit. Unitize has an engine. Every sale fuels the next construction, indefinitely.</p>
            </div>
            
            <div class="grid lg:grid-cols-4 gap-8">
                <div class="p-8 bg-white rounded-3xl border border-slate-200 hover:shadow-xl transition-all group">
                    <div class="w-14 h-14 bg-slate-900 text-emerald-400 rounded-2xl flex items-center justify-center font-bold text-2xl mb-6 shadow-lg">01</div>
                    <h4 class="text-xl font-bold mb-4">Capital Injection</h4>
                    <p class="text-slate-500 text-sm leading-relaxed">Mint funds are used to secure raw land titles in the Unitize Series LLC. No debt, pure equity.</p>
                </div>
                <div class="p-8 bg-white rounded-3xl border border-slate-200 hover:shadow-xl transition-all group">
                    <div class="w-14 h-14 bg-slate-900 text-emerald-400 rounded-2xl flex items-center justify-center font-bold text-2xl mb-6 shadow-lg">02</div>
                    <h4 class="text-xl font-bold mb-4">Modular Scaling</h4>
                    <p class="text-slate-500 text-sm leading-relaxed">Standardized mobile home blueprints allow us to build 3x faster than traditional developers.</p>
                </div>
                <div class="p-8 bg-white rounded-3xl border border-slate-200 hover:shadow-xl transition-all group">
                    <div class="w-14 h-14 bg-slate-900 text-emerald-400 rounded-2xl flex items-center justify-center font-bold text-2xl mb-6 shadow-lg">03</div>
                    <h4 class="text-xl font-bold mb-4">Market Liquidation</h4>
                    <p class="text-slate-500 text-sm leading-relaxed">Homes are sold on the retail market. Profits are split between the Build Fund and the Squad.</p>
                </div>
                <div class="p-8 bg-emerald-500 rounded-3xl border border-emerald-400 hover:shadow-xl transition-all group shadow-[0_20px_40px_-15px_rgba(16,185,129,0.3)]">
                    <div class="w-14 h-14 bg-white text-emerald-600 rounded-2xl flex items-center justify-center font-bold text-2xl mb-6 shadow-sm">04</div>
                    <h4 class="text-xl font-bold mb-4 text-slate-900">Perpetual Re-Mint</h4>
                    <p class="text-slate-900 text-sm leading-relaxed opacity-80">70% of sale proceeds automatically initiate the next build. Compounding begins.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="tech" class="py-24 bg-slate-900 text-white relative">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid lg:grid-cols-2 gap-20 items-center">
                <div class="relative">
                    <div class="p-8 bg-slate-800 rounded-3xl border border-slate-700">
                        <h4 class="text-emerald-400 font-mono text-xs uppercase tracking-widest mb-4">Smart Contract Logic</h4>
                        <div class="space-y-4 font-mono text-sm">
                            <div class="flex items-start text-slate-300">
                                <span class="text-emerald-500 mr-2">>>></span>
                                <span>function distributeRent(uint256 amount) external {</span>
                            </div>
                            <div class="pl-8 text-slate-500 italic">// Split 70/20/10 Automating Trust</div>
                            <div class="pl-8 text-slate-400">
                                transferToBuildFund(amount * 0.70); <br>
                                transferToSquadDividends(amount * 0.20); <br>
                                transferToTaxEscrow(amount * 0.10);
                            </div>
                            <div class="text-slate-300">}</div>
                        </div>
                    </div>
                    <div class="absolute -bottom-6 -right-6 w-48 h-48 bg-emerald-500/20 rounded-full blur-3xl"></div>
                </div>
                <div>
                    <h2 class="text-4xl font-bold mb-8 tracking-tight">Built on the ERC-3643 Standard</h2>
                    <p class="text-slate-400 mb-8 text-lg">Unitize uses institutional-grade permissioned tokens. This ensures that every Squad member is KYC-compliant, allowing for legal property ownership and distribution.</p>
                    <div class="grid grid-cols-2 gap-8">
                        <div>
                            <h5 class="font-bold text-white mb-2 underline decoration-emerald-500">Asset Vault</h5>
                            <p class="text-xs text-slate-500">Metadata linked to IPFS containing physical land deeds and insurance policies.</p>
                        </div>
                        <div>
                            <h5 class="font-bold text-white mb-2 underline decoration-emerald-500">Yield Oracle</h5>
                            <p class="text-xs text-slate-500">Chainlink-integrated real-time appraisal of mobile home inventory.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="legal" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="bg-slate-50 rounded-[3rem] p-12 lg:p-20 border border-slate-200">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <h2 class="text-4xl font-bold mb-6 tracking-tight text-slate-900">Institutional Compliance</h2>
                    <p class="text-slate-600">We don't operate in a legal gray area. Unitize is built on top of a battle-tested legal framework.</p>
                </div>
                <div class="grid md:grid-cols-3 gap-12">
                    <div class="text-center">
                        <div class="text-4xl mb-4 text-emerald-500">⚖️</div>
                        <h4 class="font-bold text-lg mb-2">Series LLC Wrapper</h4>
                        <p class="text-sm text-slate-500">Each land lot is its own Series LLC, isolating liability and protecting the Master Treasury.</p>
                    </div>
                    <div class="text-center">
                        <div class="text-4xl mb-4 text-emerald-500">📑</div>
                        <h4 class="font-bold text-lg mb-2">Reg D / Reg S Filing</h4>
                        <p class="text-sm text-slate-500">Compliant securities frameworks for both domestic and international investors.</p>
                    </div>
                    <div class="text-center">
                        <div class="text-4xl mb-4 text-emerald-500">🔐</div>
                        <h4 class="font-bold text-lg mb-2">Asset Custodianship</h4>
                        <p class="text-sm text-slate-500">Physical titles are held by licensed escrow agents, cryptographically linked to the Squad NFT.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="faq" class="py-24 bg-
