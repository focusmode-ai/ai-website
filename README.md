
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Resource Hub</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Space Grotesk', sans-serif;
            background-color: #030712;
            color: #ffffff;
            overflow-x: hidden;
        }

        .glass-card {
            background: rgba(17, 24, 39, 0.7);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
        }

        .glass-card:hover {
            border-color: #22d3ee;
            transform: translateY(-2px);
            box-shadow: 0 4px 20px -5px rgba(34, 211, 238, 0.3);
        }

        .glow-text {
            text-shadow: 0 0 20px rgba(34, 211, 238, 0.5);
        }

        .blob {
            position: absolute;
            filter: blur(80px);
            z-index: -1;
            opacity: 0.4;
            animation: pulse 8s infinite alternate;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            100% { transform: scale(1.1); }
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0f172a; 
        }
        ::-webkit-scrollbar-thumb {
            background: #334155; 
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #22d3ee; 
        }
    </style>
</head>
<body class="min-h-screen flex flex-col items-center py-12 px-4 relative">

    <!-- Background Effects -->
    <div class="blob bg-cyan-500 w-64 h-64 rounded-full top-0 left-0 -translate-x-1/2 -translate-y-1/2"></div>
    <div class="blob bg-purple-600 w-80 h-80 rounded-full bottom-0 right-0 translate-x-1/3 translate-y-1/3"></div>

    <!-- Profile Section -->
    <div class="text-center mb-8 relative z-10">
        <div class="w-24 h-24 mx-auto mb-4 rounded-full p-1 bg-gradient-to-r from-cyan-400 to-purple-600">
            <div class="w-full h-full bg-slate-900 rounded-full flex items-center justify-center overflow-hidden">
                <i class="fa-solid fa-robot text-4xl text-white"></i>
            </div>
        </div>
        <h1 class="text-2xl font-bold tracking-wider">FOCUS MODE <span class="text-cyan-400 glow-text">AI</span></h1>
        <p class="text-gray-400 mt-2 text-sm max-w-xs mx-auto">Curating the future. Master AI tools & prompts daily.</p>
        
        <div class="flex justify-center gap-4 mt-4">
            <a href="#" class="text-gray-400 hover:text-white transition-colors"><i class="fa-brands fa-instagram text-xl"></i></a>
            <a href="#" class="text-gray-400 hover:text-white transition-colors"><i class="fa-brands fa-tiktok text-xl"></i></a>
            <a href="#" class="text-gray-400 hover:text-white transition-colors"><i class="fa-brands fa-twitter text-xl"></i></a>
        </div>
    </div>

    <!-- Main Links Container -->
    <div class="w-full max-w-md space-y-4 relative z-10">
        
        <!-- Featured Link (Newsletter) -->
        <a href="#" class="block group">
            <div class="glass-card p-4 rounded-xl flex items-center justify-between bg-gradient-to-r from-slate-900 to-slate-800/50 border-cyan-500/30">
                <div class="flex items-center gap-4">
                    <div class="w-10 h-10 rounded-lg bg-cyan-500/20 flex items-center justify-center text-cyan-400 group-hover:bg-cyan-500 group-hover:text-black transition-all">
                        <i class="fa-solid fa-envelope"></i>
                    </div>
                    <div class="text-left">
                        <h3 class="font-bold text-sm">Join the AI Newsletter</h3>
                        <p class="text-xs text-gray-400">Get 5 free prompts weekly</p>
                    </div>
                </div>
                <i class="fa-solid fa-chevron-right text-gray-500 group-hover:text-cyan-400 transition-colors"></i>
            </div>
        </a>

        <!-- Link 1 -->
        <a href="#" class="block group">
            <div class="glass-card p-4 rounded-xl flex items-center justify-between">
                <div class="flex items-center gap-4">
                    <div class="w-10 h-10 rounded-lg bg-purple-500/20 flex items-center justify-center text-purple-400 group-hover:bg-purple-500 group-hover:text-white transition-all">
                        <i class="fa-solid fa-bolt"></i>
                    </div>
                    <div class="text-left">
                        <h3 class="font-bold text-sm">Top 10 AI Tools (2025)</h3>
                        <p class="text-xs text-gray-400">Updated List</p>
                    </div>
                </div>
                <i class="fa-solid fa-chevron-right text-gray-500 group-hover:text-white transition-colors"></i>
            </div>
        </a>

        <!-- Link 2 -->
        <a href="#" class="block group">
            <div class="glass-card p-4 rounded-xl flex items-center justify-between">
                <div class="flex items-center gap-4">
                    <div class="w-10 h-10 rounded-lg bg-green-500/20 flex items-center justify-center text-green-400 group-hover:bg-green-500 group-hover:text-white transition-all">
                        <i class="fa-solid fa-comment-dots"></i>
                    </div>
                    <div class="text-left">
                        <h3 class="font-bold text-sm">Best ChatGPT Prompts</h3>
                        <p class="text-xs text-gray-400">Copy & Paste</p>
                    </div>
                </div>
                <i class="fa-solid fa-chevron-right text-gray-500 group-hover:text-white transition-colors"></i>
            </div>
        </a>

        <!-- Affiliate Link Example -->
        <a href="#" class="block group">
            <div class="glass-card p-4 rounded-xl flex items-center justify-between">
                <div class="flex items-center gap-4">
                    <div class="w-10 h-10 rounded-lg bg-pink-500/20 flex items-center justify-center text-pink-400 group-hover:bg-pink-500 group-hover:text-white transition-all">
                        <i class="fa-solid fa-video"></i>
                    </div>
                    <div class="text-left">
                        <h3 class="font-bold text-sm">Try Video AI Generator</h3>
                        <p class="text-xs text-gray-400">Create videos from text</p>
                    </div>
                </div>
                <i class="fa-solid fa-chevron-right text-gray-500 group-hover:text-white transition-colors"></i>
            </div>
        </a>

    </div>

    <!-- Footer -->
    <div class="mt-12 text-center text-gray-600 text-xs relative z-10">
        <p>© 2025 Focus Mode AI. Powered by Future Tech.</p>
    </div>

</body>
</html>
