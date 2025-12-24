<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Professional Website</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            background: radial-gradient(circle at top right, #1e293b, #0f172a);
            color: white;
            font-family: 'Inter', sans-serif;
        }
        .glass {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
    </style>
</head>
<body class="min-h-screen flex flex-col items-center justify-center p-6">

    <nav class="fixed top-0 w-full p-6 flex justify-between items-center max-w-6xl">
        <div class="text-2xl font-bold tracking-tighter">PROJECT.GEN</div>
        <div class="space-x-8 hidden md:flex text-gray-400">
            <a href="#" class="hover:text-white transition">About</a>
            <a href="#" class="hover:text-white transition">Work</a>
            <a href="#" class="hover:text-white transition">Contact</a>
        </div>
    </nav>

    <main class="text-center max-w-3xl mt-20">
        <h1 class="text-5xl md:text-7xl font-extrabold mb-6 bg-clip-text text-transparent bg-gradient-to-r from-blue-400 to-emerald-400">
            Building the future, <br> one pixel at a time.
        </h1>
        <p class="text-gray-400 text-lg md:text-xl mb-10 leading-relaxed">
            Welcome to my GitHub-hosted website. This is a clean, responsive design generated to help you kickstart your online presence instantly.
        </p>
        
        <div class="flex gap-4 justify-center">
            <a href="#" class="bg-blue-600 hover:bg-blue-500 text-white px-8 py-3 rounded-full font-medium transition shadow-lg shadow-blue-500/20">
                Get Started
            </a>
            <a href="#" class="glass px-8 py-3 rounded-full font-medium hover:bg-white/10 transition">
                View Gallery
            </a>
        </div>
    </main>

    <section class="mt-24 grid grid-cols-1 md:grid-cols-3 gap-6 max-w-6xl w-full">
        <div class="glass p-8 rounded-3xl">
            <h3 class="text-xl font-bold mb-2">Modern Design</h3>
            <p class="text-gray-400">Beautifully crafted layouts using the latest web standards.</p>
        </div>
        <div class="glass p-8 rounded-3xl">
            <h3 class="text-xl font-bold mb-2">GitHub Hosted</h3>
            <p class="text-gray-400">Blazing fast performance served directly from GitHub Pages.</p>
        </div>
        <div class="glass p-8 rounded-3xl">
            <h3 class="text-xl font-bold mb-2">Fully Responsive</h3>
            <p class="text-gray-400">Looks amazing on phones, tablets, and desktop computers.</p>
        </div>
    </section>

    <footer class="mt-24 text-gray-500 text-sm">
        &copy; 2025 Created via Gemini AI. Hosted on GitHub.
    </footer>

</body>
</html>
