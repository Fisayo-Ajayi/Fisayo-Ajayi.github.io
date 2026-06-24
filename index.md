<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fisayo Ajayi | Data Portfolio Matrix</title>
    <!-- Tailwind CSS Engine -->
    <script src="https://tailwindcss.com"></script>
    <link href="https://googleapis.com" rel="stylesheet">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; background-color: #030712; color: #f3f4f6; overflow-x: hidden; }
        .glass-panel { background: rgba(17, 24, 39, 0.45); backdrop-filter: blur(16px); -webkit-backdrop-filter: blur(16px); }
        /* Smooth Custom Scrollbar */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #030712; }
        ::-webkit-scrollbar-thumb { background: #1f2937; border-radius: 99px; }
        ::-webkit-scrollbar-thumb:hover { background: #3b82f6; }
    </style>
</head>
<body class="antialiased relative selection:bg-blue-500 selection:text-white">

    <!-- 🌌 Interactive Particle Canvas Layer -->
    <canvas id="particleCanvas" class="absolute top-0 left-0 w-full h-full pointer-events-none z-0 opacity-40"></canvas>

    <div class="relative z-10 min-h-screen flex flex-col justify-between">
        
        <!-- 🌐 Premium Sticky Navigation Blur Header -->
        <nav class="sticky top-0 z-50 w-full border-b border-gray-900 bg-[#030712]/75 backdrop-blur-md">
            <div class="max-w-6xl mx-auto px-6 h-16 flex items-center justify-between">
                <span class="text-sm font-bold tracking-wider uppercase text-blue-500">FA // ANALYTICS</span>
                <div class="flex gap-4">
                    <a href="https://linkedin.com" target="_blank" class="text-xs text-gray-400 hover:text-white transition">LinkedIn</a>
                    <a href="#contact" class="text-xs font-semibold px-3 py-1.5 bg-blue-600 hover:bg-blue-500 rounded-md text-white transition">Get In Touch</a>
                </div>
            </div>
        </nav>

        <!-- 🚀 Hero / Split Dynamic Presentation Container -->
        <header class="max-w-6xl w-full mx-auto px-6 pt-16 pb-12 grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
            
            <!-- Left Info Column -->
            <div class="lg:col-span-7 space-y-6">
                <div>
                    <h1 class="text-5xl font-extrabold tracking-tight text-white leading-tight">
                        Fisayo Ajayi
                    </h1>
                    <!-- Dynamic Typing Text Subtitle -->
                    <p class="text-xl mt-3 text-blue-400 font-semibold h-8">
                        <span id="typingText"></span><span class="animate-pulse text-blue-500">|</span>
                    </p>
                    <p class="text-sm text-gray-500 mt-1 flex items-center gap-1.5">
                        <span class="w-2 h-2 rounded-full bg-emerald-500 animate-ping"></span> Lagos, Nigeria
                    </p>
                </div>
                
                <p class="text-gray-400 leading-relaxed max-w-xl">
                    Engineering reliable predictive data infrastructure. Specializing in resolving critical class imbalances within risk systems and converting warehouse models into high-end executive business intelligence views.
                </p>

                <!-- Core Stack Pills Wrapper -->
                <div class="flex flex-wrap gap-2 pt-2">
                    <span class="px-3 py-1 text-xs font-medium rounded-md bg-blue-950/40 border border-blue-900/60 text-blue-400">Python (Scikit-Learn)</span>
                    <span class="px-3 py-1 text-xs font-medium rounded-md bg-indigo-950/40 border border-indigo-900/60 text-indigo-400">SQL Database Engineering</span>
                    <span class="px-3 py-1 text-xs font-medium rounded-md bg-yellow-950/20 border border-yellow-900/30 text-yellow-500">Power BI / Tableau Developer</span>
                    <span class="px-3 py-1 text-xs font-medium rounded-md bg-purple-950/40 border border-purple-900/60 text-purple-400">Constrained Logistics Routing</span>
                </div>
            </div>

            <!-- Right Resume Document Column -->
            <div class="lg:col-span-5 w-full">
                <div class="glass-panel border border-gray-800/80 rounded-2xl p-2 shadow-2xl shadow-black/80">
                    <object data="/Fisayo_Olawale_Ajayi_Data_Analyst_Resume.pdf" type="application/pdf" width="100%" height="240px" class="rounded-xl">
                        <div class="p-6 text-center text-gray-400 bg-gray-900/40 rounded-xl">
                            <p class="text-xs mb-3">Professional Resume Document File</p>
                            <a href="/Fisayo_Olawale_Ajayi_Data_Analyst_Resume.pdf" class="inline-block px-4 py-2 bg-gray-800 text-xs font-semibold rounded-md hover:bg-gray-700 transition">📥 Download CV PDF</a>
                        </div>
                    </object>
                </div>
            </div>

        </header>

        <!-- 📊 Bento Grid Case Studies Framework Area -->
        <main class="max-w-6xl w-full mx-auto px-6 py-12">
            <h2 class="text-2xl font-bold text-white mb-8 flex items-center gap-3">
                <span class="w-1.5 h-6 bg-blue-500 rounded-full"></span> Advanced Analytics Suites
            </h2>

            <!-- Modern Card Matrix Stack -->
            <div class="space-y-12">

                <!-- Production Card 1: Power BI Layout -->
                <div class="glass-panel border border-gray-800/80 rounded-3xl p-6 md:p-8 hover:border-blue-500/40 transition duration-500 group shadow-xl">
                    <div class="flex items-center justify-between mb-4">
                        <span class="text-[10px] font-bold uppercase tracking-widest text-yellow-500 bg-yellow-500/10 px-2.5 py-1 rounded-md border border-yellow-500/20">Business Intelligence Studio</span>
                        <a href="https://github.com" target="_blank" class="text-xs text-gray-500 group-hover:text-blue-400 transition">Code Blueprint ↗</a>
                    </div>
                    <h3 class="text-2xl font-bold text-white group-hover:text-blue-300 transition duration-300">Sales Performance & Executive Revenue Architecture</h3>
                    <p class="text-gray-400 mt-2 max-w-3xl leading-relaxed">Structured an enterprise data warehouse schema tracking global transactions and regional margin health. Synthesized raw backend columns into dual-layer operational viewports to monitor capital leakage and sales execution anomalies.</p>
                    
                    <!-- Seamless Screen Previews Grid Container -->
                    <div class="mt-8 grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div class="rounded-2xl overflow-hidden border border-gray-900 shadow-2xl bg-gray-950">
                            <img src="https://postimg.cc" class="w-full h-full object-cover group-hover:scale-[101%] transition duration-500" alt="Executive Performance View">
                        </div>
                        <div class="rounded-2xl overflow-hidden border border-gray-900 shadow-2xl bg-gray-950">
                            <img src="https://postimg.cc" class="w-full h-full object-cover group-hover:scale-[101%] transition duration-500" alt="Product Insight Dashboard">
                        </div>
                    </div>
                </div>

                <!-- 2-Column Layout Grid for Risk & Logistics Frameworks -->
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    
                    <!-- Production Card 2: Imbalanced Risk Engine -->
                    <div class="glass-panel border border-gray-800/80 rounded-3xl p-6 md:p-8 hover:border-indigo-500/40 transition duration-500 group flex flex-col justify-between">
                        <div class="space-y-4">
                            <div class="flex items-center justify-between">
                                <span class="text-[10px] font-bold uppercase tracking-widest text-indigo-400 bg-indigo-500/10 px-2.5 py-1 rounded-md border border-indigo-500/20">Risk Modeling</span>
                                <div class="flex gap-3 text-xs text-gray-500">
                                    <a href="https://github.com" target="_blank" class="hover:text-indigo-400">Fraud ↗</a>
                                    <a href="https://github.com" target="_blank" class="hover:text-indigo-400">Credit ↗</a>
                                </div>
                            </div>
                            <h3 class="text-xl font-bold text-white group-hover:text-indigo-300 transition">Financial Fraud Mitigation Core</h3>
                            <p class="text-sm text-gray-400 leading-relaxed">Programmed classification pipelines managing heavy distribution skew (genuine transaction transactions vastly outnumber fraud). Leveraged Precision-Recall adjustments and F1 score criteria to flag default profiles cleanly.</p>
                        </div>
                    </div>

                    <!-- Production Card 3: Optimization Operations -->
                    <div class="glass-panel border border-gray-800/80 rounded-3xl p-6 md:p-8 hover:border-emerald-500/40 transition duration-500 group flex flex-col justify-between">
                        <div class="space-y-4">
                            <div class="flex items-center justify-between">
                                <span class="text-[10px] font-bold uppercase tracking-widest text-emerald-400 bg-emerald-500/10 px-2.5 py-1 rounded-md border border-emerald-500/20">Operational Systems</span>
