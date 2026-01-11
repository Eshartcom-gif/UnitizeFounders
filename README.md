
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unitize | Perpetual Mobile Home Development</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
        .nav-blur { backdrop-filter: blur(12px); background: rgba(15, 23, 42, 0.9); }
        .emerald-glow { box-shadow: 0 0 40px rgba(16, 185, 129, 0.2); }
        .bg-grid { background-image: radial-gradient(circle at 2px 2px, rgba(16, 185, 129, 0.05) 1px, transparent 0); background-size: 40px 40px; }
        .gradient-text { background: linear-gradient(135deg, #10b981 0%, #3b82f6 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
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
                <a href="#scaling" class="hover:text-emerald-400 transition text-xs uppercase tracking-widest">Scaling Logic</a>
                <a href="#loop" class="hover:text-emerald-400 transition text-xs uppercase tracking-widest">The Loop</a>
                <a href="#legal" class="hover:text-emerald-400 transition text-xs uppercase tracking-widest">Legal</a>
                <a href="https://eshartcom-gif.github.io/Unitize-Whitepaper/" class="bg-slate-800 border border-slate-700 px-4 py-2 rounded-lg hover:bg-slate-700 transition text-xs">Whitepaper</a>
                <button onclick="connectWallet()" class="bg-emerald-500 hover:bg-emerald-600 text-slate-950 px-6 py-2 rounded-full font-bold transition emerald-glow shadow-lg">Join Squad</button>
            </div>
        </div>
    </nav>

    <section id="home" class="relative bg-slate-900 pt-40 pb-32 overflow-hidden">
        <div class="absolute top-0 left-1/4 w-[500px] h-[500px] bg-emerald-500/10 blur-[150px] rounded-full"></div>
        <div class="max-w-7xl mx-auto px-6 relative z-10 grid lg:grid-cols-2 gap-16 items-center">
            <div>
                <h1 class="text-6xl lg:text-7xl font-bold text-white leading-[1.1] mb-8 tracking-tighter">
                    One NFT. <br><span class="gradient-text">Infinite Communities.</span>
                </h1>
                <p class="text-xl text-slate-400 mb-12 leading-relaxed max-w-xl font-light">
                    We don't just build houses; we build a self-sustaining engine. By reinvesting profits from every sale, your Unitize Squad NFT powers a perpetual expansion from one lot to a global network.
                </p>
                <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-6">
                    <button class="bg-emerald-500 text-slate-950 px-10 py-5 rounded-2xl font-bold text-xl hover:bg-emerald-600 transition shadow-2xl">Invest in Lot Alpha</button>
                    <a href="#scaling" class="border border-slate-700 text-white px-10 py-5 rounded-2xl font-bold text-xl hover:bg-slate-800 transition text-center flex items-center justify-center">How We Scale</a>
                </div>
            </div>
            <div class="relative bg-slate-800/50 p-10 rounded-[3rem] border border-white/10 backdrop-blur-sm">
                <img src="https://i.ibb.co/Y4WHZtLz/1768162855762.png" alt="Squad Asset" class="w-24 h-auto mb-8 grayscale brightness-200 opacity-80">
                <div class="space-y-4">
                    <div class="flex justify-between border-b border-white/5 pb-2 text-white">
                        <span class="text-slate-500 uppercase text-xs font-bold tracking-widest">Current Status</span>
                        <span class="text-emerald-400 font-bold">Phase 1: 3-Home Build</span>
                    </div>
                    <div class="flex justify-between text-white">
                        <span class="text-slate-500 uppercase text-xs font-bold tracking-widest">Next Milestone</span>
                        <span class="font-bold">Lot Beta Acquisition</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="scaling" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold mb-4 tracking-tight">The Unitize "Rule of 3"</h2>
                <p class="text-slate-500 max-w-2xl mx-auto">Our mathematical model for exponential real estate growth. Each lot generates the capital for the next.</p>
            </div>

            <div class="grid lg:grid-cols-3 gap-12">
                <div class="p-10 rounded-3xl bg-slate-50 border border-slate-100 relative overflow-hidden group">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-emerald-500/5 -mr-8 -mt-8 rounded-full"></div>
                    <h3 class="text-5xl font-extrabold text-slate-200 mb-6 group-hover:text-emerald-100 transition">01</h3>
                    <h4 class="text-xl font-bold mb-4">First Home Sale</h4>
                    <p class="text-slate-600 text-sm leading-relaxed mb-6">Profit from House #1 is deployed to cover materials and labor for House #2 and #3 on the current lot.</p>
                    <div class="text-xs font-bold text-emerald-600 tracking-widest uppercase">Result: Build Momentum</div>
                </div>
                <div class="p-10 rounded-3xl bg-slate-50 border border-slate-100 relative overflow-hidden group">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-emerald-500/5 -mr-8 -mt-8 rounded-full"></div>
                    <h3 class="text-5xl font-extrabold text-slate-200 mb-6 group-hover:text-emerald-100 transition">02</h3>
                    <h4 class="text-xl font-bold mb-4">Community Completion</h4>
                    <p class="text-slate-600 text-sm leading-relaxed mb-6">Sale of House #2 completes the "Squad Dividend" pool and secures the operational reserve for expansion.</p>
                    <div class="text-xs font-bold text-emerald-600 tracking-widest uppercase">Result: Yield Distribution</div>
                </div>
                <div class="p-10 rounded-3xl bg-emerald-500 text-white relative overflow-hidden group shadow-2xl shadow-emerald-500/20">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-white/10 -mr-8 -mt-8 rounded-full"></div>
                    <h3 class="text-5xl font-extrabold text-emerald-400 mb-6 opacity-30">03</h3>
                    <h4 class="text-xl font-bold mb-4">The Expansion Trigger</h4>
                    <p class="text-emerald-50 text-sm leading-relaxed mb-6">The 3rd sale provides the critical mass of capital required to purchase **Lot Beta** and start a new 3-home cycle.</p>
                    <div class="text-xs font-bold text-slate-900 tracking-widest uppercase">Result: Perpetual Growth</div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-24 bg-slate-900 text-white relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 grid lg:grid-cols-2 gap-20 items-center">
            <div>
                <h2 class="text-4xl font-bold mb-6">From One Lot to a Network</h2>
                <p class="text-slate-400 text-lg mb-8">Every time we close a lot, the "Build Fund" expands. By Year 3, the Unitize Squad will be developing multiple lots across different territories simultaneously.</p>
                <div class="space-y-4">
                    <div class="flex items-center space-x-4 p-4 bg-white/5 rounded-2xl border border-white/10">
                        <span class="w-10 h-10 bg-emerald-500/20 text-emerald-400 flex items-center justify-center rounded-lg font-bold">1</span>
                        <span><strong>Lot Alpha:</strong> 3 Houses Sold → Funded Lot Beta</span>
                    </div>
                    <div class="flex items-center space-x-4 p-4 bg-white/5 rounded-2xl border border-white/10">
                        <span class="w-10 h-10 bg-emerald-500/20 text-emerald-400 flex items-center justify-center rounded-lg font-bold">2</span>
                        <span><strong>Lot Beta:</strong> 3 Houses Sold → Funded Lots Gamma & Delta</span>
                    </div>
                </div>
            </div>
            <div class="relative p-12 bg-slate-800 rounded-[3rem] border border-slate-700">
                <h4 class="text-center font-bold text-slate-500 uppercase text-xs tracking-[0.3em] mb-12">The Unitize Engine</h4>
                <div class="flex justify
