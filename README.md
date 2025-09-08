# Earth-
earth live luckashon and spice other force information real-time expectation 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DeepSite | earth live stream </title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.globe.min.js"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <style>
        .gradient-text {
            background: linear-gradient(90deg, #3b82f6, #8b5cf6, #ec4899);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        #vanta-bg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }
        .blur-bg {
            backdrop-filter: blur(10px);
            background-color: rgba(15, 23, 42, 0.7);
        }
        .pulse-animation {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { opacity: 0.8; }
            50% { opacity: 1; }
            100% { opacity: 0.8; }
        }
    </style>
</head>
<body class="bg-slate-900 text-slate-100 min-h-screen overflow-x-hidden">
    <div id="vanta-bg"></div>
    
    <nav class="fixed w-full z-50 blur-bg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0">
                        <span class="text-xl font-bold gradient-text">DeepSite</span>
                    </div>
                    <div class="hidden md:block">
                        <div class="ml-10 flex items-baseline space-x-4">
                            <a href="#" class="px-3 py-2 rounded-md text-sm font-medium text-white bg-indigo-900">Dashboard</a>
                            <a href="#" class="px-3 py-2 rounded-md text-sm font-medium text-slate-300 hover:text-white">Analytics</a>
                            <a href="#" class="px-3 py-2 rounded-md text-sm font-medium text-slate-300 hover:text-white">Networks</a>
                            <a href="#" class="px-3 py-2 rounded-md text-sm font-medium text-slate-300 hover:text-white">API</a>
                            <a href="#" class="px-3 py-2 rounded-md text-sm font-medium text-slate-300 hover:text-white">Docs</a>
                        </div>
                    </div>
                </div>
                <div class="hidden md:block">
                    <div class="ml-4 flex items-center md:ml-6">
                        <button class="p-1 rounded-full text-slate-400 hover:text-white">
                            <i data-feather="bell"></i>
                        </button>
                        <div class="ml-3 relative">
                            <div>
                                <button class="max-w-xs flex items-center text-sm rounded-full focus:outline-none">
                                    <span class="inline-block h-8 w-8 rounded-full overflow-hidden bg-gray-100">
                                        <img src="http://static.photos/technology/200x200/5" alt="User avatar">
                                    </span>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="-mr-2 flex md:hidden">
                    <button type="button" class="inline-flex items-center justify-center p-2 rounded-md text-slate-400 hover:text-white hover:bg-slate-700 focus:outline-none">
                        <i data-feather="menu"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <main class="pt-24 pb-12">
        <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center" data-aos="fade-up">
                <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight">
                    <span class="gradient-text">Real-time</span> Data Visualization
                </h1>
                <p class="mt-6 max-w-3xl mx-auto text-lg text-slate-300">
                    Monitor and analyze your network activity with our powerful real-time dashboard. Get insights when you need them.
                </p>
                <div class="mt-8 flex justify-center">
                    <a href="#" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700">
                        Get Started
                        <i data-feather="arrow-right" class="ml-2"></i>
                    </a>
                    <a href="#" class="ml-4 inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md text-indigo-300 bg-indigo-900 hover:bg-indigo-800">
                        Live Demo
                        <i data-feather="eye" class="ml-2"></i>
                    </a>
                </div>
            </div>

            <div class="mt-20 grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="blur-bg rounded-xl p-6" data-aos="fade-up" data-aos-delay="100">
                    <div class="flex items-center">
                        <div class="flex-shrink-0 bg-indigo-500 rounded-md p-3">
                            <i data-feather="activity" class="h-6 w-6 text-white"></i>
                        </div>
                        <div class="ml-4">
                            <h3 class="text-lg font-medium text-white">Real-time Monitoring</h3>
                            <p class="mt-1 text-sm text-slate-300">Track activity as it happens with sub-second latency.</p>
                        </div>
                    </div>
                </div>
                <div class="blur-bg rounded-xl p-6" data-aos="fade-up" data-aos-delay="200">
                    <div class="flex items-center">
                        <div class="flex-shrink-0 bg-purple-500 rounded-md p-3">
                            <i data-feather="layers" class="h-6 w-6 text-white"></i>
                        </div>
                        <div class="ml-4">
                            <h3 class="text-lg font-medium text-white">Multi-layer Analysis</h3>
                            <p class="mt-1 text-sm text-slate-300">Deep dive into network layers with comprehensive tools.</p>
                        </div>
                    </div>
                </div>
                <div class="blur-bg rounded-xl p-6" data-aos="fade-up" data-aos-delay="300">
                    <div class="flex items-center">
                        <div class="flex-shrink-0 bg-pink-500 rounded-md p-3">
                            <i data-feather="alert-triangle" class="h-6 w-6 text-white"></i>
                        </div>
                        <div class="ml-4">
                            <h3 class="text-lg font-medium text-white">Anomaly Detection</h3>
                            <p class="mt-1 text-sm text-slate-300">AI-powered alerts for suspicious activity patterns.</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="mt-20 blur-bg rounded-xl p-6" data-aos="fade-up">
                <div class="flex flex-col md:flex-row items-center">
                    <div class="md:w-1/2 p-6">
                        <h2 class="text-2xl font-bold text-white">Interactive Network Map</h2>
                        <p class="mt-4 text-slate-300">
                            Visualize your entire network topology in real-time. See connections, traffic flow, and performance metrics in an intuitive interface.
                        </p>
                        <div class="mt-6">
                            <div class="flex items-center">
                                <i data-feather="check" class="text-green-400"></i>
                                <span class="ml-2 text-slate-300">Live node status updates</span>
                            </div>
                            <div class="flex items-center mt-2">
                                <i data-feather="check" class="text-green-400"></i>
                                <span class="ml-2 text-slate-300">Bandwidth monitoring</span>
                            </div>
                            <div class="flex items-center mt-2">
                                <i data-feather="check" class="text-green-400"></i>
                                <span class="ml-2 text-slate-300">Connection health indicators</span>
                            </div>
                        </div>
                    </div>
                    <div class="md:w-1/2 p-6" id="network-visualization">
                        <div class="bg-slate-800 rounded-lg p-4 h-64 flex items-center justify-center pulse-animation">
                            <p class="text-slate-400">Live network visualization will appear here</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="mt-20">
                <h2 class="text-2xl font-bold text-white text-center mb-8" data-aos="fade-up">Real-time Metrics</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                    <div class="blur-bg rounded-xl p-6" data-aos="fade-up" data-aos-delay="100">
                        <div class="flex justify-between">
                            <div>
                                <p class="text-sm text-slate-400">Requests</p>
                                <h3 class="text-3xl font-bold text-white mt-1" id="requests-count">1,247</h3>
                            </div>
                            <div class="bg-indigo-500 rounded-md p-3 h-12 w-12 flex items-center justify-center">
                                <i data-feather="send" class="h-5 w-5 text-white"></i>
                            </div>
                        </div>
                        <div class="mt-4">
                            <div class="flex items-center text-sm text-green-400">
                                <i data-feather="trending-up" class="h-4 w-4"></i>
                                <span class="ml-1">12.3% from last hour</span>
                            </div>
                        </div>
                    </div>
                    <div class="blur-bg rounded-xl p-6" data-aos="fade-up" data-aos-delay="200">
                        <div class="flex justify-between">
                            <div>
                                <p class="text-sm text-slate-400">Latency</p>
                                <h3 class="text-3xl font-bold text-white mt-1" id="latency-ms">42ms</h3>
                            </div>
                            <div class="bg-purple-500 rounded-md p-3 h-12 w-12 flex items-center justify-center">
                                <i data-feather="clock" class="h-5 w-5 text-white"></i>
                            </div>
                        </div>
                        <div class="mt-4">
                            <div class="flex items-center text-sm text-green-400">
                                <i data-feather="trending-down" class="h-4 w-4"></i>
                                <span class="ml-1">8.7% improvement</span>
                            </div>
                        </div>
                    </div>
                    <div class="blur-bg rounded-xl p-6" data-aos="fade-up" data-aos-delay="300">
                        <div class="flex justify-between">
                            <div>
                                <p class="text-sm text-slate-400">Errors</p>
                                <h3 class="text-3xl font-bold text-white mt-1" id="errors-count">3</h3>
                            </div>
                            <div class="bg-pink-500 rounded-md p-3 h-12 w-12 flex items-center justify-center">
                                <i data-feather="alert-circle" class="h-5 w-5 text-white"></i>
                            </div>
                        </div>
                        <div class="mt-4">
                            <div class="flex items-center text-sm text-red-400">
                                <i data-feather="alert-triangle" class="h-4 w-4"></i>
                                <span class="ml-1">1 new in last 5 min</span>
                            </div>
                        </div>
                    </div>
                    <div class="blur-bg rounded-xl p-6" data-aos="fade-up" data-aos-delay="400">
                        <div class="flex justify-between">
                            <div>
                                <p class="text-sm text-slate-400">Uptime</p>
                                <h3 class="text-3xl font-bold text-white mt-1" id="uptime-percent">99.98%</h3>
                            </div>
                            <div class="bg-green-500 rounded-md p-3 h-12 w-12 flex items-center justify-center">
                                <i data-feather="check-circle" class="h-5 w-5 text-white"></i>
                            </div>
                        </div>
                        <div class="mt-4">
                            <div class="flex items-center text-sm text-green-400">
                                <i data-feather="check" class="h-4 w-4"></i>
                                <span class="ml-1">All systems operational</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="blur-bg border-t border-slate-700">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-sm font-semibold text-slate-300 tracking-wider uppercase">DeepSite</h3>
                    <p class="mt-4 text-sm text-slate-400">
                        Real-time data visualization and network monitoring for the modern web.
                    </p>
                </div>
                <div>
                    <h3 class="text-sm font-semibold text-slate-300 tracking-wider uppercase">Product</h3>
                    <ul class="mt-4 space-y-2">
                        <li><a href="#" class="text-sm text-slate-400 hover:text-white">Features</a></li>
                        <li><a href="#" class="text-sm text-slate-400 hover:text-white">Pricing</a></li>
                        <li><a href="#" class="text-sm text-slate-400 hover:text-white">API</a></li>
                        <li><a href="#" class="text-sm text-slate-400 hover:text-white">Integrations</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-sm font-semibold text-slate-300 tracking-wider uppercase">Resources</h3>
                    <ul class="mt-4 space-y-2">
                        <li><a href="#" class="text-sm text-slate-400 hover:text-white">Documentation</a></li>
                        <li><a href="#" class="text-sm text-slate-400 hover:text-white">Guides</a></li>
                        <li><a href="#" class="text-sm text-slate-400 hover:text-white">Blog</a></li>
                        <li><a href="#" class="text-sm text-slate-400 hover:text-white">Support</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-sm font-semibold text-slate-300 tracking-wider uppercase">Connect</h3>
                    <div class="mt-4 flex space-x-4">
                        <a href="#" class="text-slate-400 hover:text-white">
                            <i data-feather="twitter"></i>
                        </a>
                        <a href="#" class="text-slate-400 hover:text-white">
                            <i data-feather="github"></i>
                        </a>
                        <a href="#" class="text-slate-400 hover:text-white">
                            <i data-feather="linkedin"></i>
                        </a>
                        <a href="#" class="text-slate-400 hover:text-white">
                            <i data-feather="mail"></i>
                        </a>
                    </div>
                </div>
            </div>
            <div class="mt-8 pt-8 border-t border-slate-700 flex flex-col md:flex-row justify-between items-center">
                <p class="text-sm text-slate-400">© 2023 DeepSite. All rights reserved.</p>
                <div class="mt-4 md:mt-0 flex space-x-6">
                    <a href="#" class="text-sm text-slate-400 hover:text-white">Privacy</a>
                    <a href="#" class="text-sm text-slate-400 hover:text-white">Terms</a>
                    <a href="#" class="text-sm text-slate-400 hover:text-white">Cookies</a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Initialize animations
        AOS.init({
            duration: 800,
            once: true
        });
        
        // Initialize feather icons
        feather.replace();
        
        // Initialize Vanta.js background
        VANTA.GLOBE({
            el: "#vanta-bg",
            mouseControls: true,
            touchControls: true,
            gyroControls: false,
            minHeight: 200.00,
            minWidth: 200.00,
            scale: 1.00,
            scaleMobile: 1.00,
            color: 0x3b82f6,
            backgroundColor: 0x020617,
            size: 0.8
        });
        
        // Simulate real-time data updates
        function updateMetrics() {
            // Requests count
            const requestsEl = document.getElementById('requests-count');
            const currentRequests = parseInt(requestsEl.textContent.replace(/,/g, ''));
            const newRequests = currentRequests + Math.floor(Math.random() * 50);
            requestsEl.textContent = newRequests.toLocaleString();
            
            // Latency
            const latencyEl = document.getElementById('latency-ms');
            const currentLatency = parseInt(latencyEl.textContent.replace('ms', ''));
            const newLatency = Math.max(20, Math.min(80, currentLatency + Math.floor(Math.random() * 10) - 5));
            latencyEl.textContent = newLatency + 'ms';
            
            // Errors
            const errorsEl = document.getElementById('errors-count');
            const currentErrors = parseInt(errorsEl.textContent);
            const errorChange = Math.random() > 0.8 ? 1 : 0;
            const newErrors = Math.max(0, currentErrors + errorChange);
            errorsEl.textContent = newErrors;
            
            // Uptime (small random fluctuation)
            const uptimeEl = document.getElementById('uptime-percent');
            const currentUptime = parseFloat(uptimeEl.textContent.replace('%', ''));
            const uptimeChange = (Math.random() * 0.01) - 0.005;
            const newUptime = Math.max(99.9, Math.min(100, currentUptime + uptimeChange));
            uptimeEl.textContent = newUptime.toFixed(2) + '%';
            
            // Schedule next update
            setTimeout(updateMetrics, 3000);
        }
        
        // Start the updates
        updateMetrics();
        
        // Mobile menu toggle would go here
    </script>
</body>
</html>
