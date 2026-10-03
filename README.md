# ima-website
It is the website of my Neet academy
```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ichalkaranji Medical Academy (IMA) - NEET Coaching Excellence</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            50: '#f0f4f8',
                            100: '#d9e2ec',
                            800: '#102a43',
                            900: '#0b1b2b',
                        },
                        gold: {
                            400: '#f6ad55',
                            500: '#ed8936',
                            600: '#dd6b20',
                        },
                        emerald: {
                            600: '#059669',
                            700: '#047857',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        .gold-gradient {
            background: linear-gradient(135deg, #f6ad55 0%, #dd6b20 100%);
        }
        .navy-gradient {
            background: linear-gradient(135deg, #0b1b2b 0%, #102a43 100%);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans antialiased">

    <!-- Header Navbar -->
    <header class="sticky top-0 z-40 bg-navy-900 text-white shadow-lg border-b border-navy-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-12 h-12 rounded-xl gold-gradient flex items-center justify-center shadow-md font-bold text-2xl text-navy-900">
                    IMA
                </div>
                <div>
                    <h1 class="text-xl font-bold tracking-tight text-white leading-tight">Ichalkaranji Medical Academy</h1>
                    <p class="text-xs text-gold-400 font-medium">Excellence in NEET Coaching</p>
                </div>
            </div>
            <nav class="hidden md:flex space-x-8 text-sm font-semibold">
                <a href="#about" class="hover:text-gold-400 transition">About Us</a>
                <a href="#results" class="hover:text-gold-400 transition">Top Rankers</a>
                <a href="#faculty" class="hover:text-gold-400 transition">Our Faculty</a>
                <a href="#courses" class="hover:text-gold-400 transition">Courses</a>
                <a href="#contact" class="hover:text-gold-400 transition">Contact</a>
            </nav>
            <button onclick="openModal()" class="hidden md:inline-flex items-center px-5 py-2.5 rounded-lg text-sm font-bold gold-gradient text-navy-900 hover:opacity-90 transition shadow-lg transform hover:-translate-y-0.5">
                Enquire Now
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="navy-gradient text-white py-16 md:py-24 relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-6">
                    <span class="inline-block px-4 py-1.5 rounded-full text-xs font-bold uppercase tracking-wider bg-gold-500/20 text-gold-400 border border-gold-500/30">
                        Top NEET Academy in Ichalkaranji
                    </span>
                    <h2 class="text-3xl md:text-5xl font-extrabold leading-tight">
                        Transform Your Medical Dreams Into Reality
                    </h2>
                    <p class="text-gray-300 text-base md:text-lg">
                        Expert mentorship by experienced doctors and subject experts. Proven track record of top rankers in NEET-UG with admissions into prestigious government medical colleges.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4 pt-2">
                        <button onclick="openModal()" class="px-6 py-3.5 rounded-xl text-base font-bold gold-gradient text-navy-900 hover:opacity-90 shadow-xl text-center">
                            Book Free Demo Class
                        </button>
                        <a href="#results" class="px-6 py-3.5 rounded-xl text-base font-semibold bg-navy-800 hover:bg-gray-800 border border-navy-700 text-center">
                            View Top Rankers
                        </a>
                    </div>
                </div>
                <!-- Hero Highlight Card -->
                <div class="bg-navy-800/80 backdrop-blur-sm border border-navy-700 p-6 md:p-8 rounded-2xl shadow-2xl space-y-6">
                    <div class="flex items-center space-x-4 border-b border-navy-700 pb-4">
                        <div class="w-12 h-12 rounded-full bg-emerald-600/20 text-emerald-400 flex items-center justify-center text-xl">
                            <i class="fas fa-trophy"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-white">NEET 2025 Success Highlights</h3>
                            <p class="text-xs text-gray-400">Consistent Top Scores Year After Year</p>
                        </div>
                    </div>
                    <div class="grid grid-cols-2 gap-4 text-center">
                        <div class="bg-navy-900/60 p-4 rounded-xl border border-navy-700">
                            <div class="text-2xl md:text-3xl font-extrabold text-gold-400">685+</div>
                            <p class="text-xs text-gray-300 mt-1">Highest NEET Score</p>
                        </div>
                        <div class="bg-navy-900/60 p-4 rounded-xl border border-navy-700">
                            <div class="text-2xl md:text-3xl font-extrabold text-emerald-400">92%</div>
                            <p class="text-xs text-gray-300 mt-1">Qualifying Rate</p>
                        </div>
                        <div class="bg-navy-900/60 p-4 rounded-xl border border-navy-700">
                            <div class="text-2xl md:text-3xl font-extrabold text-gold-400">45+</div>
                            <p class="text-xs text-gray-300 mt-1">Govt MBBS Admissions</p>
                        </div>
                        <div class="bg-navy-900/60 p-4 rounded-xl border border-navy-700">
                            <div class="text-2xl md:text-3xl font-extrabold text-emerald-400">12+</div>
                            <p class="text-xs text-gray-300 mt-1">Years of Excellence</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION 1: TOP SCORERS & RANKERS -->
    <section id="results" class="py-16 bg-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-12">
                <span class="inline-block px-3 py-1 rounded-full text-xs font-bold bg-gold-500/10 text-gold-600 uppercase tracking-wider mb-2">
                    Wall of Pride
                </span>
                <h2 class="text-3xl font-extrabold text-navy-900">NEET Top Rankers & Stars</h2>
                <p class="text-gray-600 mt-2 text-sm sm:text-base">
                    Our proud students who achieved exceptional marks and earned seats in top government medical colleges.
                </p>

                <!-- Filter Tabs for Years -->
                <div class="flex flex-wrap justify-center gap-2 mt-6" id="year-filters">
                    <button onclick="filterRankers('all')" class="filter-btn active-filter px-5 py-2 rounded-full text-xs sm:text-sm font-bold transition shadow-sm bg-navy-900 text-white">
                        All Years
                    </button>
                    <button onclick="filterRankers('2025')" class="filter-btn px-5 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-navy-900 hover:bg-gray-200 transition shadow-sm border border-gray-300">
                        NEET 2025
                    </button>
                    <button onclick="filterRankers('2024')" class="filter-btn px-5 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-navy-900 hover:bg-gray-200 transition shadow-sm border border-gray-300">
                        NEET 2024
                    </button>
                    <button onclick="filterRankers('2023')" class="filter-btn px-5 py-2 rounded-full text-xs sm:text-sm font-bold bg-white text-navy-900 hover:bg-gray-200 transition shadow-sm border border-gray-300">
                        NEET 2023
                    </button>
                </div>
            </div>

            <!-- Ranker Cards Grid -->
            <!-- 
                CUSTOMIZATION NOTE FOR USER:
                To add/modify students, update the cards below. Replace 'src' with the student's photo URL or keep placehold.co images.
            -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8" id="rankers-grid">
                
                <!-- Ranker Card 1 -->
                <div class="ranker-card bg-white rounded-2xl shadow-lg border border-gray-200 overflow-hidden transform hover:-translate-y-1 transition duration-300" data-year="2025">
                    <div class="relative bg-navy-900 p-6 text-center text-white">
                        <span class="absolute top-3 right-3 bg-emerald-600 text-white text-[10px] font-extrabold uppercase px-2.5 py-1 rounded-full shadow-sm">
                            650+ Marks
                        </span>
                        <!-- Student Photo -->
                        <img src="https://placehold.co/120x120/102a43/ffffff?text=Aarav+S" alt="Aarav Sharma" class="w-24 h-24 rounded-full mx-auto border-4 border-gold-400 shadow-md object-cover" onerror="this.src='https://placehold.co/120x120/102a43/ffffff?text=Student'">
                        <h3 class="text-xl font-bold mt-3 text-white">Aarav Sharma</h3>
                        <p class="text-xs text-gold-400 font-semibold">NEET 2025 Batch</p>
                    </div>
                    <div class="p-6 space-y-4">
                        <div class="flex justify-between items-center bg-gray-50 p-3 rounded-xl border border-gray-100">
                            <div>
                                <p class="text-xs text-gray-500 uppercase font-bold">NEET Score</p>
                                <p class="text-xl font-extrabold text-navy-900">685 <span class="text-xs text-gray-500 font-normal">/ 720</span></p>
                            </div>
                            <div class="text-right">
                                <p class="text-xs text-gray-500 uppercase font-bold">All India Rank</p>
                                <p class="text-lg font-bold text-gold-600">AIR 420</p>
                            </div>
                        </div>
                        <div class="flex items-center space-x-3 text-sm text-gray-700">
                            <i class="fas fa-university text-emerald-600 text-lg"></i>
                            <div>
                                <p class="text-xs text-gray-400 font-medium">Allotted Medical College</p>
                                <p class="font-bold text-gray-800">KEM Hospital & Seth GS Medical College, Mumbai</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Ranker Card 2 -->
                <div class="ranker-card bg-white rounded-2xl shadow-lg border border-gray-200 overflow-hidden transform hover:-translate-y-1 transition duration-300" data-year="2025">
                    <div class="relative bg-navy-900 p-6 text-center text-white">
                        <span class="absolute top-3 right-3 bg-emerald-600 text-white text-[10px] font-extrabold uppercase px-2.5 py-1 rounded-full shadow-sm">
                            650+ Marks
                        </span>
                        <!-- Student Photo -->
                        <img src="https://placehold.co/120x120/059669/ffffff?text=Ananya+P" alt="Ananya Patil" class="w-24 h-24 rounded-full mx-auto border-4 border-gold-400 shadow-md object-cover" onerror="this.src='https://placehold.co/120x120/059669/ffffff?text=Student'">
                        <h3 class="text-xl font-bold mt-3 text-white">Ananya Patil</h3>
                        <p class="text-xs text-gold-400 font-semibold">NEET 2025 Batch</p>
                    </div>
                    <div class="p-6 space-y-4">
                        <div class="flex justify-between items-center bg-gray-50 p-3 rounded-xl border border-gray-100">
                            <div>
                                <p class="text-xs text-gray-500 uppercase font-bold">NEET Score</p>
                                <p class="text-xl font-extrabold text-navy-900">672 <span class="text-xs text-gray-500 font-normal">/ 720</span></p>
                            </div>
                            <div class="text-right">
                                <p class="text-xs text-gray-500 uppercase font-bold">State Rank</p>
                                <p class="text-lg font-bold text-gold-600">MH Rank 85</p>
                            </div>
                        </div>
                        <div class="flex items-center space-x-3 text-sm text-gray-700">
                            <i class="fas fa-university text-emerald-600 text-lg"></i>
                            <div>
                                <p class="text-xs text-gray-400 font-medium">Allotted Medical College</p>
                                <p class="font-bold text-gray-800">BJ Government Medical College, Pune</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Ranker Card 3 -->
                <div class="ranker-card bg-white rounded-2xl shadow-lg border border-gray-200 overflow-hidden transform hover:-translate-y-1 transition duration-300" data-year="2024">
                    <div class="relative bg-navy-900 p-6 text-center text-white">
                        <span class="absolute top-3 right-3 bg-emerald-600 text-white text-[10px] font-extrabold uppercase px-2.5 py-1 rounded-full shadow-sm">
                            650+ Marks
                        </span>
                        <!-- Student Photo -->
                        <img src="https://placehold.co/120x120/dd6b20/ffffff?text=Rohan+K" alt="Rohan Kulkarni" class="w-24 h-24 rounded-full mx-auto border-4 border-gold-400 shadow-md object-cover" onerror="this.src='https://placehold.co/120x120/dd6b20/ffffff?text=Student'">
                        <h3 class="text-xl font-bold mt-3 text-white">Rohan Kulkarni</h3>
                        <p class="text-xs text-gold-400 font-semibold">NEET 2024 Batch</p>
                    </div>
                    <div class="p-6 space-y-4">
                        <div class="flex justify-between items-center bg-gray-50 p-3 rounded-xl border border-gray-100">
                            <div>
                                <p class="text-xs text-gray-500 uppercase font-bold">NEET Score</p>
                                <p class="text-xl font-extrabold text-navy-900">664 <span class="text-xs text-gray-500 font-normal">/ 720</span></p>
                            </div>
                            <div class="text-right">
                                <p class="text-xs text-gray-500 uppercase font-bold">All India Rank</p>
                                <p class="text-lg font-bold text-gold-600">AIR 1150</p>
                            </div>
                        </div>
                        <div class="flex items-center space-x-3 text-sm text-gray-700">
                            <i class="fas fa-university text-emerald-600 text-lg"></i>
                            <div>
                                <p class="text-xs text-gray-400 font-medium">Allotted Medical College</p>
                                <p class="font-bold text-gray-800">RCSM Government Medical College, Kolhapur</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Ranker Card 4 -->
                <div class="ranker-card bg-white rounded-2xl shadow-lg border border-gray-200 overflow-hidden transform hover:-translate-y-1 transition duration-300" data-year="2024">
                    <div class="relative bg-navy-900 p-6 text-center text-white">
                        <span class="absolute top-3 right-3 bg-emerald-600 text-white text-[10px] font-extrabold uppercase px-2.5 py-1 rounded-full shadow-sm">
                            650+ Marks
                        </span>
                        <!-- Student Photo -->
                        <img src="https://placehold.co/120x120/102a43/ffffff?text=Saniya+M" alt="Saniya Mane" class="w-24 h-24 rounded-full mx-auto border-4 border-gold-400 shadow-md object-cover" onerror="this.src='https://placehold.co/120x120/102a43/ffffff?text=Student'">
                        <h3 class="text-xl font-bold mt-3 text-white">Saniya Mane</h3>
                        <p class="text-xs text-gold-400 font-semibold">NEET 2024 Batch</p>
                    </div>
                    <div class="p-6 space-y-4">
                        <div class="flex justify-between items-center bg-gray-50 p-3 rounded-xl border border-gray-100">
                            <div>
                                <p class="text-xs text-gray-500 uppercase font-bold">NEET Score</p>
                                <p class="text-xl font-extrabold text-navy-900">658 <span class="text-xs text-gray-500 font-normal">/ 720</span></p>
                            </div>
                            <div class="text-right">
                                <p class="text-xs text-gray-500 uppercase font-bold">State Rank</p>
                                <p class="text-lg font-bold text-gold-600">MH Rank 142</p>
                            </div>
                        </div>
                        <div class="flex items-center space-x-3 text-sm text-gray-700">
                            <i class="fas fa-university text-emerald-600 text-lg"></i>
                            <div>
                                <p class="text-xs text-gray-400 font-medium">Allotted Medical College</p>
                                <p class="font-bold text-gray-800">Grant Medical College & JJ Hospital, Mumbai</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Ranker Card 5 -->
                <div class="ranker-card bg-white rounded-2xl shadow-lg border border-gray-200 overflow-hidden transform hover:-translate-y-1 transition duration-300" data-year="2023">
                    <div class="relative bg-navy-900 p-6 text-center text-white">
                        <span class="absolute top-3 right-3 bg-emerald-600 text-white text-[10px] font-extrabold uppercase px-2.5 py-1 rounded-full shadow-sm">
                            650+ Marks
                        </span>
                        <!-- Student Photo -->
                        <img src="https://placehold.co/120x120/059669/ffffff?text=Aditya+J" alt="Aditya Joshi" class="w-24 h-24 rounded-full mx-auto border-4 border-gold-400 shadow-md object-cover" onerror="this.src='https://placehold.co/120x120/059
