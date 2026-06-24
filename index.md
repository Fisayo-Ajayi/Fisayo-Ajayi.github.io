<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fisayo Ajayi | Data Analyst & Engineer</title>
    <!-- Modern Tailwind UI Script -->
    <script src="https://tailwindcss.com"></script>
    <link href="https://googleapis.com" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; background-color: #0b0f19; color: #f3f4f6; }
    </style>
</head>
<body class="antialiased selection:bg-blue-500 selection:text-white">

    <!-- 🌐 Premium Navigation / Header Header -->
    <header class="max-w-5xl mx-auto px-6 pt-12 pb-8 border-b border-gray-800">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-4">
            <div>
                <h1 class="text-4xl font-extrabold tracking-tight text-white bg-clip-text text-transparent bg-gradient-to-r from-blue-400 to-indigo-500">Fisayo Ajayi</h1>
                <p class="text-lg mt-2 text-gray-400 font-medium">Data Analyst & Analytics Engineer</p>
                <p class="text-sm text-gray-500 mt-1">📍 Lagos, Nigeria</p>
            </div>
            <div class="flex flex-wrap gap-3">
                <a href="YOUR_LINKEDIN_URL" class="px-4 py-2 text-sm bg-gray-900 border border-gray-800 text-gray-300 rounded-lg hover:bg-gray-800 hover:text-white transition">🔗 LinkedIn</a>
                <a href="#contact" class="px-4 py-2 text-sm bg-blue-600 text-white font-medium rounded-lg hover:bg-blue-500 transition shadow-lg shadow-blue-900/40">✉️ Contact Me</a>
            </div>
        </div>
        
        <!-- 🏷️ Automated Tech Badges -->
        <div class="flex flex-wrap gap-2 mt-6">
            <span class="px-3 py-1 text-xs font-semibold rounded-full bg-blue-900/30 text-blue-400 border border-blue-800/50">Python</span>
            <span class="px-3 py-1 text-xs font-semibold rounded-full bg-indigo-900/30 text-indigo-400 border border-indigo-800/50">SQL</span>
            <span class="px-3 py-1 text-xs font-semibold rounded-full bg-yellow-900/20 text-yellow-500 border border-yellow-800/30">Power BI</span>
            <span class="px-3 py-1 text-xs font-semibold rounded-full bg-emerald-900/30 text-emerald-400 border border-emerald-800/50">Scikit-Learn</span>
            <span class="px-3 py-1 text-xs font-semibold rounded-full bg-purple-900/30 text-purple-400 border border-purple-800/50">Predictive Modeling</span>
        </div>
    </header>

    <!-- 📄 Interactive Resume Document Viewer Section -->
    <section class="max-w-5xl mx-auto px-6 py-8">
        <h2 class="text-xl font-bold text-white mb-4 border-l-4 border-indigo-500 pl-3">Professional Resume</h2>
        <div class="rounded-2xl overflow-hidden border border-gray-800 bg-gray-900/20 p-2">
            <!-- Ensure your PDF is uploaded into your repository root folder with the name resume.pdf -->
            <object data="/resume.pdf" type="application/pdf" width="100%" height="500px" class="rounded-xl">
                <div class="p-6 text-center text-gray-400">
                    <p class="mb-4">Your browser does not support embedded PDF views natively.</p>
                    <a href="/resume.pdf" class="inline-block px-5 py-2.5 bg-gray-800 text-white font-semibold rounded-lg hover:bg-gray-700 transition">📥 Download Resume PDF</a>
                </div>
            </object>
        </div>
    </section>

    <!-- 📋 Core Work Section -->
    <main class="max-w-5xl mx-auto px-6 py-8">
        <h2 class="text-2xl font-bold text-white mb-8 border-l-4 border-blue-500 pl-3">Advanced Analytics Suites</h2>

        <div class="grid grid-cols-1 gap-12">

            <!-- Card 1: Power BI Business Showcase -->
            <div class="bg-gray-900/40 border border-gray-800/80 rounded-2xl p-6 md:p-8 hover:border-gray-700 transition">
                <div class="flex items-center justify-between mb-4">
                    <span class="text-xs font-bold uppercase tracking-wider text-yellow-500 bg-yellow-900/20 px-2.5 py-1 rounded">Business Intelligence</span>
                    <a href="https://github.com" target="_blank" class="text-xs text-blue-400 hover:underline">View Repository ↗</a>
                </div>
                <h3 class="text-2xl font-bold text-white">Sales Performance & Executive Revenue Analytics</h3>
                <p class="text-gray-400 mt-2 leading-relaxed">Engineered a relational enterprise database structure to evaluate cross-channel sales behavior and map multi-region profit margins. Translated raw tables into high-end executive reporting sheets to eliminate data tracking delays.</p>
                
                <!-- Dashboard Imagery Flex Grid -->
                <div class="mt-6 grid grid-cols-1 md:grid-cols-2 gap-4">
                    <div class="rounded-xl overflow-hidden border border-gray-800">
                        <img src="https://postimg.cc" class="w-full object-cover hover:scale-105 transition duration-300" alt="Sales Overview">
                    </div>
                    <div class="rounded-xl overflow-hidden border border-gray-800">
                        <img src="https://postimg.cc" class="w-full object-cover hover:scale-105 transition duration-300" alt="Customer Insights">
                    </div>
                </div>
            </div>

            <!-- Card 2: Risk Analytics -->
            <div class="bg-gray-900/40 border border-gray-800/80 rounded-2xl p-6 md:p-8 hover:border-gray-700 transition">
                <div class="flex items-center justify-between mb-4">
                    <span class="text-xs font-bold uppercase tracking-wider text-blue-400 bg-blue-900/20 px-2.5 py-1 rounded">Risk Engineering</span>
                    <div class="flex gap-4 text-xs">
                        <a href="https://github.com" target="_blank" class="text-blue-400 hover:underline">Fraud Repo ↗</a>
                        <a href="https://github.com" target="_blank" class="text-blue-400 hover:underline">Credit Risk Repo ↗</a>
                    </div>
                </div>
                <h3 class="text-2xl font-bold text-white">Financial Risk Mitigation & High-Skew Class Anomaly Core</h3>
                <p class="text-gray-400 mt-2 leading-relaxed">Built predictive risk workflows to handle severe data imbalance (less than 1% target anomalies). Prioritized complex F1-Score metrics and Precision-Recall modeling over generic accuracy checks to secure transaction environments without introducing subscriber friction.</p>
            </div>

            <!-- Card 3: Logistics Optimization -->
            <div class="bg-gray-900/40 border border-gray-800/80 rounded-2xl p-6 md:p-8 hover:border-gray-700 transition">
                <div class="flex items-center justify-between mb-4">
                    <span class="text-xs font-bold uppercase tracking-wider text-emerald-400 bg-emerald-900/20 px-2.5 py-1 rounded">Operations</span>
                    <a href="https://github.com" target="_blank" class="text-xs text-blue-400 hover:underline">View Repository ↗</a>
                </div>
                <h3 class="text-2xl font-bold text-white">Supply Chain & Constrained Logistics Fleet Route Optimizer</h3>
                <p class="text-gray-400 mt-2 leading-relaxed">Formulated an operational route planner mapping complex delivery variables (such as coordinate weight parameters, vehicle capacities, and drop windows). Safely downsizes transportation overhead and increases fleet dispatch certainty.</p>
            </div>

        </div>
    </main>

    <!-- ✉️ Functional Contact Form Container -->
    <section id="contact" class="max-w-5xl mx-auto px-6 py-12 border-t border-gray-850">
        <div class="max-w-xl mx-auto bg-gray-900/30 border border-gray-800 p-6 md:p-8 rounded-2xl">
            <h2 class="text-2xl font-bold text-white mb-2">Get In Touch</h2>
            <p class="text-sm text-gray-400 mb-6">Drop a secure message directly to my corporate email queue regarding project opportunities or technical analytical collaboration.</p>
            
            <!-- Safe, secure endpoint tracking via Web3Forms -->
            <form action="https://web3forms.com" method="POST" class="space-y-4">
                <!-- Replace the value string below with your direct key from web3forms.com later if needed -->
                <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
                
                <div>
                    <label class="block text-xs font-semibold text-gray-400 uppercase tracking-wider mb-2">Your Name</label>
                    <input type="text" name="name" required class="w-full bg-gray-900 border border-gray-800 rounded-lg px-4 py-2.5 text-sm text-white focus:outline-none focus:border-blue-500 transition">
                </div>
                <div>
                    <label class="block text-xs font-semibold text-gray-400 uppercase tracking-wider mb-2">Email Address</label>
                    <input type="email" name="email" required class="w-full bg-gray-900 border border-gray-800 rounded-lg px-4 py-2.5 text-sm text-white focus:outline-none focus:border-blue-500 transition">
                </div>
                <div>
                    <label class="block text-xs font-semibold text-gray-400 uppercase tracking-wider mb-2">Message Description</label>
                    <textarea name="message" required rows="4" class="w-full bg-gray-900 border border-gray-800 rounded-lg px-4 py-2.5 text-sm text-white focus:outline-none focus:border-blue-500 transition resize-none"></textarea>
                </div>
                
