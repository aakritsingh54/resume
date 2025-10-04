





















<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aakrit Singh - Personal Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .glass-effect {
            background: rgba(23, 23, 23, 0.6);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        .gradient-text {
            background: linear-gradient(to right, #34d399, #60a5fa);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .section-glow {
            position: relative;
            overflow: hidden;
        }
        .section-glow::before {
            content: '';
            position: absolute;
            top: -100px;
            left: 50%;
            width: 300px;
            height: 300px;
            background: radial-gradient(circle, rgba(52, 211, 153, 0.1), transparent 70%);
            transform: translateX(-50%);
            pointer-events: none;
            z-index: -1;
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-300 antialiased">

    <!-- Header / Navbar -->
    <header id="header" class="glass-effect fixed top-0 left-0 right-0 z-50 transition-all duration-300">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex-shrink-0">
                    <a href="#home" class="text-xl font-bold tracking-wider gradient-text">Aakrit Singh</a>
                </div>
                <nav class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-4">
                        <a href="#about" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:bg-gray-700 hover:text-white transition-colors">About</a>
                        <a href="#skills" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:bg-gray-700 hover:text-white transition-colors">Skills</a>
                        <a href="#projects" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:bg-gray-700 hover:text-white transition-colors">Projects</a>
                        <a href="#contact" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:bg-gray-700 hover:text-white transition-colors">Contact</a>
                    </div>
                </nav>
                <div class="md:hidden">
                    <button id="mobile-menu-button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-white hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-gray-800 focus:ring-white">
                        <span class="sr-only">Open main menu</span>
                        <i data-lucide="menu" class="block h-6 w-6"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu, show/hide based on menu state. -->
        <div class="md:hidden hidden" id="mobile-menu">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#about" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">About</a>
                <a href="#skills" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Skills</a>
                <a href="#projects" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Projects</a>
                <a href="#contact" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Contact</a>
            </div>
        </div>
    </header>

    <main class="pt-16">
        <!-- Hero Section -->
        <section id="home" class="min-h-screen flex items-center justify-center section-glow">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <img src="your-photo.jpg" alt="A photo of Aakrit Singh" class="w-40 h-40 rounded-full mx-auto mb-6 border-4 border-emerald-400 shadow-lg">
                <h1 class="text-4xl sm:text-5xl md:text-6xl font-bold text-white mb-3">Hi, I'm <span class="gradient-text">Aakrit Singh</span></h1>
                <p class="text-lg md:text-xl text-gray-400 max-w-3xl mx-auto mb-8">I'm a passionate student and aspiring Software Developer creating innovative solutions for the web.</p>
                <div class="flex justify-center items-center space-x-6">
                    <a href="https://www.linkedin.com/in/aakrit-singh-4i1620i" target="_blank" class="text-gray-400 hover:text-emerald-400 transition-colors">
                        <i data-lucide="linkedin" class="w-8 h-8"></i>
                    </a>
                    <a href="https://www.instagram.com/_.akrit.singh._24?igsh=MXE4OWU4dzZ2eG04aQ==" target="_blank" class="text-gray-400 hover:text-emerald-400 transition-colors">
                        <i data-lucide="instagram" class="w-8 h-8"></i>
                    </a>
                    <a href="https://www.facebook.com/aakrit.singh.632333" target="_blank" class="text-gray-400 hover:text-emerald-400 transition-colors">
                        <i data-lucide="facebook" class="w-8 h-8"></i>
                    </a>
                    <a href="mailto:aakritsingh54@gmail.com" class="text-gray-400 hover:text-emerald-400 transition-colors">
                        <i data-lucide="mail" class="w-8 h-8"></i>
                    </a>
                </div>
            </div>
        </section>

        <!-- About Me Section -->
        <section id="about" class="py-20 sm:py-24 section-glow">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-12">
                    <h2 class="text-3xl sm:text-4xl font-bold text-white">About Me</h2>
                    <p class="text-lg text-gray-400 mt-2">A little bit about my journey and passions.</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-5 gap-8 md:gap-12 items-center">
                    <div class="md:col-span-2">
                        <img src="https://placehold.co/400x500/1f2937/60a5fa?text=About" alt="A photo of you" class="rounded-lg shadow-2xl w-full">
                    </div>
                    <div class="md:col-span-3">
                        <h3 class="text-2xl font-semibold text-white mb-4">Who I Am?</h3>
                        <p class="mb-4 text-gray-400">
                            Hello! I'm Aakrit Singh, a student at P P Savani University, currently pursuing a degree in B.Tech Computer Science Engineering. My fascination with Web Development began when...
                        </p>
                        <h4 class="text-xl font-semibold text-white mt-6 mb-2">🚀 My Journey</h4>
                        <p class="mb-4 text-gray-400">
                            I started as a curious learner, often unsure of where my path would lead. At times, progress felt slow and invisible, but I kept moving forward—one step, one effort at a time. Just like a seed growing roots underground, I was building a foundation. Today, I stand stronger, ready to rise higher with the skills, patience, and resilience I’veearned along the way.
                        </p>
                        <h4 class="text-xl font-semibold text-white mt-6 mb-2">✨ Lesson</h4>
                        <p class="mb-4 text-gray-400">
                           My journey reminds me that growth takes time, but every effort counts—and the right moment always comes. Since then, I've been dedicated to learning and applying my skills to build meaningful and efficient projects.
                        </p>
                        <p class="mb-6 text-gray-400">
                           "Outside of my academic and professional pursuits, I enjoy reading, traveling & cultural exploration and exploring new places. I believe a balanced life fuels creativity and problem-solving."
                        </p>
                        <a href="#contact" class="inline-block bg-emerald-500 text-white font-semibold px-6 py-3 rounded-lg hover:bg-emerald-600 transition-all duration-300 shadow-lg">Get In Touch</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-20 sm:py-24 bg-gray-900 section-glow">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-12">
                    <h2 class="text-3xl sm:text-4xl font-bold text-white">My Skillset</h2>
                    <p class="text-lg text-gray-400 mt-2">Technologies and tools I work with.</p>
                </div>
                <div class="max-w-4xl mx-auto">
                    <div class="mb-8">
                        <h3 class="text-xl font-semibold text-white mb-4">Languages</h3>
                        <div class="flex flex-wrap gap-3">
                            <span class="bg-gray-800 text-emerald-300 px-4 py-2 rounded-full text-sm font-medium">C</span>
                            <span class="bg-gray-800 text-emerald-300 px-4 py-2 rounded-full text-sm font-medium">C++</span>
                            <span class="bg-gray-800 text-emerald-300 px-4 py-2 rounded-full text-sm font-medium">JavaScript</span>
                            <span class="bg-gray-800 text-emerald-300 px-4 py-2 rounded-full text-sm font-medium">Python</span>
                            <span class="bg-gray-800 text-emerald-300 px-4 py-2 rounded-full text-sm font-medium">HTML</span>
                            <span class="bg-gray-800 text-emerald-300 px-4 py-2 rounded-full text-sm font-medium">CSS</span>
                        </div>
                    </div>
                    <div class="mb-8">
                        <h3 class="text-xl font-semibold text-white mb-4">Frameworks & Libraries</h3>
                        <div class="flex flex-wrap gap-3">
                            <span class="bg-gray-800 text-blue-300 px-4 py-2 rounded-full text-sm font-medium">React</span>
                            <span class="bg-gray-800 text-blue-300 px-4 py-2 rounded-full text-sm font-medium">Node.js</span>
                            <span class="bg-gray-800 text-blue-300 px-4 py-2 rounded-full text-sm font-medium">Express</span>
                            <span class="bg-gray-800 text-blue-300 px-4 py-2 rounded-full text-sm font-medium">Tailwind CSS</span>
                        </div>
                    </div>
                    <div>
                        <h3 class="text-xl font-semibold text-white mb-4">Tools & Platforms</h3>
                        <div class="flex flex-wrap gap-3">
                            <span class="bg-gray-800 text-purple-300 px-4 py-2 rounded-full text-sm font-medium">Git & GitHub</span>
                            <span class="bg-gray-800 text-purple-300 px-4 py-2 rounded-full text-sm font-medium">Docker</span>
                            <span class="bg-gray-800 text-purple-300 px-4 py-2 rounded-full text-sm font-medium">VS Code</span>
                            <span class="bg-gray-800 text-purple-300 px-4 py-2 rounded-full text-sm font-medium">Figma</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-20 sm:py-24 section-glow">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-12">
                    <h2 class="text-3xl sm:text-4xl font-bold text-white">Featured Projects</h2>
                    <p class="text-lg text-gray-400 mt-2">Some of the projects I'm proud of.</p>
                </div>
                <!-- Projects Grid -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Project Card 1 (Featured) -->
                    <div class="relative bg-gray-800/50 rounded-lg overflow-hidden shadow-lg transition-all duration-300 hover:shadow-emerald-500/20 ring-2 ring-emerald-500/50 transform hover:-translate-y-2 group">
                        <div class="absolute top-4 right-4 bg-emerald-500 text-white text-xs font-bold px-3 py-1 rounded-full shadow-md z-10 flex items-center">
                            <i data-lucide="star" class="w-3 h-3 inline-block -mt-0.5 mr-1"></i>Featured
                        </div>
                        <img src="https://placehold.co/600x400/1f2937/34d399?text=AI+Profile+Builder" alt="AI Profile Builder Project Screenshot" class="w-full h-48 object-cover group-hover:opacity-90 transition-opacity">
                        <div class="p-6">
                            <h3 class="text-xl font-bold text-white mb-2">ProfileCraft - Live Portfolio Builder</h3>
                            <p class="text-gray-400 mb-4 text-sm">
                                An interactive, AI-powered application to build and customize a professional portfolio in real-time. Features multiple design templates and one-click PDF export.
                            </p>
                            <div class="flex flex-wrap gap-2 mb-4">
                                <span class="text-xs font-semibold bg-emerald-900/50 text-emerald-300 px-3 py-1 rounded-full border border-emerald-700">React</span>
                                <span class="text-xs font-semibold bg-blue-900/50 text-blue-300 px-3 py-1 rounded-full border border-blue-700">TypeScript</span>
                                <span class="text-xs font-semibold bg-pink-900/50 text-pink-300 px-3 py-1 rounded-full border border-pink-700">PDF Export</span>
                                <span class="text-xs font-semibold bg-indigo-900/50 text-indigo-300 px-3 py-1 rounded-full border border-indigo-700">Tailwind CSS</span>
                            </div>
                            <div class="mt-6 flex items-center justify-between">
                                <a href="portfolio-builder.html" target="_blank" class="px-4 py-2 rounded-lg bg-gradient-to-r from-emerald-500 to-green-400 text-white font-semibold flex items-center text-sm hover:from-emerald-600 hover:to-green-500 transition-all transform hover:scale-105">
                                    Open Builder
                                </a>
                                <a href="https://github.com/your-username/profile-builder" target="_blank" class="text-gray-400 hover:text-white flex items-center transition-colors">
                                    <i data-lucide="github" class="w-5 h-5 mr-1"></i> View Code
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- Project Card 2 -->
                    <div class="bg-gray-800/50 rounded-lg overflow-hidden shadow-lg transform hover:-translate-y-2 transition-transform duration-300 hover:shadow-blue-500/20 hover:ring-2 hover:ring-blue-500/50 group transform hover:-translate-y-2 group">
                        <img src="https://placehold.co/600x400/1f2937/60a5fa?text=E-Commerce+Platform" alt="E-Commerce Platform Project Screenshot" class="w-full h-48 object-cover group-hover:opacity-90 transition-opacity">
                        <div class="p-6">
                            <h3 class="text-xl font-bold text-white mb-2">Full-Stack E-Commerce Platform</h3>
                            <p class="text-gray-400 mb-4 text-sm">A complete online store with user accounts, product browsing, a shopping cart, and a checkout system. Built with the MERN stack.</p>
                            <div class="flex flex-wrap gap-2 mb-4">
                                <span class="text-xs font-semibold bg-green-900/50 text-green-300 px-3 py-1 rounded-full border border-green-700">MongoDB</span>
                                <span class="text-xs font-semibold bg-gray-700/50 text-gray-300 px-3 py-1 rounded-full border border-gray-500">Express</span>
                                <span class="text-xs font-semibold bg-sky-900/50 text-sky-300 px-3 py-1 rounded-full border border-sky-700">React</span>
                                <span class="text-xs font-semibold bg-emerald-900/50 text-emerald-300 px-3 py-1 rounded-full border border-emerald-700">Node.js</span>
                            </div>
                             <div class="mt-6 flex items-center justify-between">
                                <a href="https://your-live-demo-link.com" target="_blank" class="px-4 py-2 rounded-lg bg-gradient-to-r from-blue-500 to-sky-400 text-white font-semibold flex items-center text-sm hover:from-blue-600 hover:to-sky-500 transition-all transform hover:scale-105">
                                    Live Demo
                                </a>
                                <a href="https://github.com/your-username/ecommerce-platform" target="_blank" class="text-gray-400 hover:text-white flex items-center transition-colors">
                                    <i data-lucide="github" class="w-5 h-5 mr-1"></i> View Code
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- Project Card 3 -->
                    <div class="bg-gray-800/50 rounded-lg overflow-hidden shadow-lg transform hover:-translate-y-2 transition-transform duration-300 hover:shadow-purple-500/20 hover:ring-2 hover:ring-purple-500/50 group">
                        <img src="https://placehold.co/600x400/1f2937/a78bfa?text=Project+3" alt="Project 3 Screenshot" class="w-full h-48 object-cover group-hover:opacity-90 transition-opacity">
                        <div class="p-6">
                            <h3 class="text-xl font-bold text-white mb-2">Project Title Three</h3>
                            <p class="text-gray-400 mb-4 text-sm">A brief description of the project, its purpose, and the value it brings. Keep it concise but informative.</p>
                            <div class="flex flex-wrap gap-2 mb-4">
                                <span class="text-xs font-semibold bg-purple-900/50 text-purple-300 px-3 py-1 rounded-full border border-purple-700">Vue.js</span>
                                <span class="text-xs font-semibold bg-green-900/50 text-green-300 px-3 py-1 rounded-full border border-green-700">Supabase</span>
                            </div>
                            <div class="mt-6 flex items-center justify-between">
                                <a href="https://your-other-project-link.com" target="_blank" class="px-4 py-2 rounded-lg bg-gradient-to-r from-purple-500 to-indigo-400 text-white font-semibold flex items-center text-sm hover:from-purple-600 hover:to-indigo-500 transition-all transform hover:scale-105">
                                    Live Demo
                                </a>
                                <a href="https://github.com/your-username/project-three" target="_blank" class="text-gray-400 hover:text-white flex items-center transition-colors">
                                    <i data-lucide="github" class="w-5 h-5 mr-1"></i> View Code
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 sm:py-24 section-glow">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h2 class="text-3xl sm:text-4xl font-bold text-white">Get In Touch</h2>
                <p class="text-lg text-gray-400 mt-4 max-w-2xl mx-auto">I'm currently open to new opportunities and collaborations. Feel free to reach out if you have a question or just want to connect!</p>
                <div class="mt-8">
                    <a href="mailto:aakritsingh54@gmail.com" class="inline-block bg-gradient-to-r from-emerald-500 to-blue-500 text-white font-bold text-lg px-8 py-4 rounded-lg hover:shadow-xl transform hover:-translate-y-1 transition-all duration-300">
                        Say Hello 👋
                    </a>
                </div>
                 <div class="mt-8">
                    <!-- 
                        IMPORTANT: To make this button work:
                        1. Add your resume file (e.g., "Aakrit_Singh_Resume.pdf") to the same folder as this index.html file.
                        2. Change the href below from "Aakrit_Singh_Resume.pdf" to the exact name of your file.
                    -->
                    <a href="Aakrit_Singh_Resume.pdf" download="Aakrit_Singh_Resume.pdf" class="text-emerald-400 hover:text-emerald-300 font-semibold flex items-center justify-center">
                        Download My Resume <i data-lucide="download" class="w-4 h-4 ml-2"></i>
                    </a>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 border-t border-gray-700">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 py-8 text-center text-gray-400">
            <div class="flex flex-wrap justify-center gap-4 mb-6">
                <a href="index.html" download="portfolio-website-source.html" class="inline-block bg-gray-700 text-white font-semibold px-5 py-2 rounded-lg hover:bg-gray-600 transition-all duration-300 flex items-center gap-2 text-sm">
                    <i data-lucide="code" class="w-4 h-4"></i> Download Portfolio Code
                </a>
                <a href="portfolio-builder.html" download="portfolio-builder-source.html" class="inline-block bg-gray-700 text-white font-semibold px-5 py-2 rounded-lg hover:bg-gray-600 transition-all duration-300 flex items-center gap-2 text-sm">
                    <i data-lucide="file-code" class="w-4 h-4"></i> Download Builder Code
                </a>
            </div>
            <p class="text-sm">&copy; 2024 Aakrit Singh. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        // Lucide Icons
        lucide.createIcons();

        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            const icon = mobileMenuButton.querySelector('i');
            if (mobileMenu.classList.contains('hidden')) {
                icon.setAttribute('data-lucide', 'menu');
            } else {
                icon.setAttribute('data-lucide', 'x');
            }
            lucide.createIcons(); // Re-render icons
        });

        // Close mobile menu on link click
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                mobileMenuButton.querySelector('i').setAttribute('data-lucide', 'menu');
                lucide.createIcons();
            });
        });
        
        // Header scroll effect
        const header = document.getElementById('header');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                header.classList.remove('h-16');
                header.classList.add('h-14');
            } else {
                header.classList.add('h-16');
                header.classList.remove('h-14');
            }
        });

    </script>
</body>
</html>
