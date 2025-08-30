<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Kinz | Full-Stack Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
        
        .floating {
            animation: float 3s ease-in-out infinite;
        }
        
        .language-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1);
        }
        
        .glow-text {
            text-shadow: 0 0 10px rgba(59, 130, 246, 0.5);
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-100 min-h-screen">
    <div class="container mx-auto px-4 py-12">
        <!-- Header Section -->
        <header class="text-center mb-16">
            <div class="flex justify-center mb-6">
                <div class="relative w-32 h-32 rounded-full overflow-hidden border-4 border-blue-500 shadow-lg">
                    <div class="absolute inset-0 bg-gradient-to-br from-blue-500 to-purple-600 flex items-center justify-center">
                        <i class="fas fa-code text-5xl text-white"></i>
                    </div>
                </div>
            </div>
            <h1 class="text-4xl md:text-5xl font-bold mb-2 glow-text">Hey, I'm <span class="text-blue-400">Kinz</span></h1>
            <p class="text-xl text-blue-300 mb-4">Full-Stack Developer & Compiler Enthusiast</p>
            <div class="max-w-2xl mx-auto">
                <p class="text-gray-300 mb-6">
                    With over <span class="text-blue-400 font-bold">7 years</span> of coding experience, I've been crafting digital experiences since childhood. 
                    My journey began with HTML, CSS, and JavaScript and has evolved into creating my own languages and compilers.
                </p>
                
            </div>
        </header>

        <!-- Main Content -->
        <main>
            <!-- Skills Section -->
            <section class="mb-16">
                <h2 class="text-3xl font-bold mb-8 text-center">My <span class="text-blue-400">Technical Arsenal</span></h2>
                
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                    <!-- HTML -->
                    <div class="language-card bg-gray-800 rounded-xl p-6 transition-all duration-300">
                        <div class="flex items-center mb-4">
                            <i class="fab fa-html5 text-4xl text-orange-500 mr-3"></i>
                            <h3 class="text-xl font-semibold">HTML</h3>
                        </div>
                        <p class="text-gray-400">Mastered since childhood, the foundation of all my web projects.</p>
                    </div>
                    
                    <!-- CSS -->
                    <div class="language-card bg-gray-800 rounded-xl p-6 transition-all duration-300">
                        <div class="flex items-center mb-4">
                            <i class="fab fa-css3-alt text-4xl text-blue-400 mr-3"></i>
                            <h3 class="text-xl font-semibold">CSS</h3>
                        </div>
                        <p class="text-gray-400">Transforming designs into pixel-perfect realities for years.</p>
                    </div>
                    
                    <!-- JavaScript -->
                    <div class="language-card bg-gray-800 rounded-xl p-6 transition-all duration-300">
                        <div class="flex items-center mb-4">
                            <i class="fab fa-js-square text-4xl text-yellow-400 mr-3"></i>
                            <h3 class="text-xl font-semibold">JavaScript</h3>
                        </div>
                        <p class="text-gray-400">My go-to for creating interactive and dynamic web experiences.</p>
                    </div>
                    
                    <!-- Java -->
                    <div class="language-card bg-gray-800 rounded-xl p-6 transition-all duration-300">
                        <div class="flex items-center mb-4">
                            <i class="fab fa-java text-4xl text-red-500 mr-3"></i>
                            <h3 class="text-xl font-semibold">Java</h3>
                        </div>
                        <p class="text-gray-400">Currently expanding my knowledge in this powerful language.</p>
                    </div>
                    
                    <!-- Python -->
                    <div class="language-card bg-gray-800 rounded-xl p-6 transition-all duration-300">
                        <div class="flex items-center mb-4">
                            <i class="fab fa-python text-4xl text-blue-300 mr-3"></i>
                            <h3 class="text-xl font-semibold">Python</h3>
                        </div>
                        <p class="text-gray-400">The language I chose to create my own compiler subset.</p>
                    </div>
                    
                    <!-- C -->
                    <div class="language-card bg-gray-800 rounded-xl p-6 transition-all duration-300">
                        <div class="flex items-center mb-4">
                            <i class="fas fa-copyright text-4xl text-blue-200 mr-3"></i>
                            <h3 class="text-xl font-semibold">C</h3>
                        </div>
                        <p class="text-gray-400">Understanding the roots of modern programming.</p>
                    </div>
                    
                    <!-- C++ -->
                    <div class="language-card bg-gray-800 rounded-xl p-6 transition-all duration-300">
                        <div class="flex items-center mb-4">
                            <i class="fas fa-code text-4xl text-blue-600 mr-3"></i>
                            <h3 class="text-xl font-semibold">C++</h3>
                        </div>
                        <p class="text-gray-400">For when performance and object-oriented design matter.</p>
                    </div>
                    
                    <!-- Cython -->
                    <div class="language-card bg-gray-800 rounded-xl p-6 transition-all duration-300">
                        <div class="flex items-center mb-4">
                            <i class="fas fa-bolt text-4xl text-yellow-300 mr-3"></i>
                            <h3 class="text-xl font-semibold">Cython</h3>
                        </div>
                        <p class="text-gray-400">Bridging Python's ease with C's performance.</p>
                    </div>
                    
                    <!-- PyTorch -->
                    <div class="language-card bg-gray-800 rounded-xl p-6 transition-all duration-300">
                        <div class="flex items-center mb-4">
                            <i class="fas fa-brain text-4xl text-orange-500 mr-3"></i>
                            <h3 class="text-xl font-semibold">PyTorch</h3>
                        </div>
                        <p class="text-gray-400">Building cutting-edge neural networks and machine learning models.</p>
                    </div>
                </div>
            </section>
            
            <!-- AI Skills Section -->
            <section class="mb-16">
                <h2 class="text-3xl font-bold mb-8 text-center">My <span class="text-blue-400">AI Expertise</span></h2>
                
                <div class="grid md:grid-cols-1 gap-8 max-w-4xl mx-auto">
                    <div class="bg-gradient-to-br from-gray-800 to-gray-700 rounded-xl p-6 border-l-4 border-yellow-500">
                        <div class="flex items-center mb-4">
                            <div class="bg-yellow-500/20 p-3 rounded-lg mr-4">
                                <i class="fas fa-brain text-2xl text-yellow-400"></i>
                            </div>
                            <h3 class="text-xl font-semibold">PyTorch Development</h3>
                        </div>
                        <p class="text-gray-300">
                            Experienced in building and training neural networks using PyTorch. Skilled in implementing computer vision models,
                            natural language processing systems, and reinforcement learning algorithms. My work with PyTorch includes:
                        </p>
                        <ul class="list-disc pl-5 mt-4 text-gray-400">
                            <li>Designing custom neural network architectures</li>
                            <li>Implementing transfer learning techniques</li>
                            <li>Optimizing model performance through hyperparameter tuning</li>
                            <li>Developing production-ready AI solutions</li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- Achievements Section -->
            <section class="mb-16">
                <h2 class="text-3xl font-bold mb-8 text-center">My <span class="text-blue-400">Notable Creations</span></h2>
                
                <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                    <div class="bg-gradient-to-br from-gray-800 to-gray-700 rounded-xl p-6 border-l-4 border-blue-500">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-500/20 p-3 rounded-lg mr-4">
                                <i class="fas fa-cogs text-2xl text-blue-400"></i>
                            </div>
                            <h3 class="text-xl font-semibold">Python Subset Compiler</h3>
                        </div>
                        <p class="text-gray-300">
                            Engineered a custom compiler for a Python subset, demonstrating deep understanding of language design and compilation processes.
                        </p>
                    </div>
                    
                    <div class="bg-gradient-to-br from-gray-800 to-gray-700 rounded-xl p-6 border-l-4 border-purple-500">
                        <div class="flex items-center mb-4">
                            <div class="bg-purple-500/20 p-3 rounded-lg mr-4">
                                <i class="fas fa-file-code text-2xl text-purple-400"></i>
                            </div>
                            <h3 class="text-xl font-semibold">Custom Markup Language</h3>
                        </div>
                        <p class="text-gray-300">
                            Designed and implemented a bespoke markup language that compiles to HTML, streamlining content creation workflows.
                        </p>
                    </div>
                </div>
            </section>
            
            <!-- Timeline -->
            <section>
                <h2 class="text-3xl font-bold mb-8 text-center">My <span class="text-blue-400">Coding Journey</span></h2>
                
                <div class="max-w-2xl mx-auto">
                    <div class="relative">
                        <!-- Timeline line -->
                        <div class="absolute left-5 top-0 h-full w-1 bg-blue-500/30"></div>
                        
                        <!-- Timeline items -->
                        <div class="relative pl-12 pb-10">
                            <!-- Childhood -->
                            <div class="mb-10">
                                <div class="absolute left-0 top-0 h-4 w-4 rounded-full bg-blue-500 border-4 border-gray-900"></div>
                                <div class="bg-gray-800 rounded-xl p-6">
                                    <h3 class="text-xl font-semibold mb-2">The Beginning</h3>
                                    <p class="text-gray-400 mb-2">Started learning HTML, CSS, and JavaScript as a kid</p>
                                    <p class="text-sm text-blue-300">Age: Young enough to be amazed by &lt;blink&gt; tags</p>
                                </div>
                            </div>
                            
                            <!-- 7+ Years -->
                            <div class="mb-10">
                                <div class="absolute left-0 top-0 h-4 w-4 rounded-full bg-blue-500 border-4 border-gray-900"></div>
                                <div class="bg-gray-800 rounded-xl p-6">
                                    <h3 class="text-xl font-semibold mb-2">Professional Growth</h3>
                                    <p class="text-gray-400 mb-2">Accumulated over 7 years of professional coding experience</p>
                                    <p class="text-sm text-blue-300">Languages: Expanded to Java, Python, C, C++, and more</p>
                                </div>
                            </div>
                            
                            <!-- Compilers -->
                            <div class="mb-10">
                                <div class="absolute left-0 top-0 h-4 w-4 rounded-full bg-blue-500 border-4 border-gray-900"></div>
                                <div class="bg-gray-800 rounded-xl p-6">
                                    <h3 class="text-xl font-semibold mb-2">Language Design</h3>
                                    <p class="text-gray-400 mb-2">Created Python subset compiler and custom markup language</p>
                                    <p class="text-sm text-blue-300">Achievement: From using languages to creating them</p>
                                </div>
                            </div>
                            
                            <!-- Present -->
                            <div>
                                <div class="absolute left-0 top-0 h-4 w-4 rounded-full bg-blue-500 border-4 border-gray-900"></div>
                                <div class="bg-gray-800 rounded-xl p-6">
                                    <h3 class="text-xl font-semibold mb-2">Current Focus</h3>
                                    <p class="text-gray-400 mb-2">Advancing Java skills while maintaining expertise in other languages</p>
                                    <p class="text-sm text-blue-300">Goal: Continuous learning and pushing boundaries</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </main>
        
        <!-- Footer -->
        <footer class="mt-20 text-center text-gray-500">
            <div class="flex justify-center mb-6">
                <a href="https://github.com/minikids" class="text-xl hover:text-blue-400 transition-colors" target="_blank"><i class="fab fa-github"></i></a>
            </div>
            <p>© 2023 Kinz. All code and no play makes Kinz a full-stack developer.</p>
        </footer>
    </div>

    <script>
        // Simple animation for language cards on scroll
        document.addEventListener('DOMContentLoaded', function() {
            const languageCards = document.querySelectorAll('.language-card');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, { threshold: 0.1 });
            
            languageCards.forEach(card => {
                card.style.opacity = '0';
                card.style.transform = 'translateY(20px)';
                card.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
                observer.observe(card);
            });
            
            // Add floating animation to profile icon
            const profileIcon = document.querySelector('.relative.w-32.h-32');
            profileIcon.classList.add('floating');
        });
    </script>
</body>
</html>
