# KDA-achievements
<!doctype html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>King David Academy: Achieving Excellence</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Lucide Icons for aesthetic touches -->
    <script src="https://unpkg.com/lucide@latest/dist/umd/lucide.js"></script>
    <style>
        /* Custom font import and general style */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117; /* Dark background */
            color: #e5e7eb; /* Light text */
            line-height: 1.6;
        }
        .gradient-text {
            /* Academic colors: Royal Blue and Gold */
            background: linear-gradient(90deg, #FFD700, #4169e1);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-fill-color: transparent;
        }
        .card {
            background-color: #161b22;
            box-shadow: 0 10px 15px -3px rgba(65, 105, 225, 0.2), 0 4px 6px -2px rgba(65, 105, 225, 0.05);
            transition: transform 0.3s ease-in-out;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(65, 105, 225, 0.4), 0 10px 10px -5px rgba(65, 105, 225, 0.1);
        }
        .kda-border {
            border-left: 4px solid;
            border-image: linear-gradient(to bottom, #FFD700, #4169e1) 1;
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- Header Section -->
    <header class="py-6 border-b border-gray-700 bg-black sticky top-0 z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex justify-between items-center">
            <h1 class="text-3xl font-extrabold tracking-tight">
                <span class="gradient-text">KING DAVID ACADEMY</span>
            </h1>
            <nav class="hidden md:flex space-x-8 text-sm font-medium">
                <a href="#intro" class="text-gray-400 hover:text-white transition duration-200">Our Mission</a>
                <a href="#milestones" class="text-gray-400 hover:text-white transition duration-200">Key Achievements</a>
                <a href="#impact" class="text-gray-400 hover:text-white transition duration-200">Honors & Impact</a>
            </nav>
        </div>
    </header>

    <main class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:px-8">

        <!-- Introduction Section -->
        <section id="intro" class="text-center mb-16">
            <h2 class="text-6xl font-black mb-4 gradient-text sm:text-7xl lg:text-8xl leading-tight">
                ACADEMIC EXCELLENCE
            </h2>
            <p class="text-lg text-gray-400 max-w-3xl mx-auto">
                King David Academy is dedicated to nurturing future leaders through holistic education. Our commitment to high standards across academics, arts, and athletics ensures every student achieves their full potential and makes a positive global impact.
            </p>
            <div class="mt-8">
                <!-- Placeholder image for visual appeal -->
                <img src="https://placehold.co/1200x400/1e293b/FFD700?text=KDA+School+Campus+Placeholder" 
                     alt="King David Academy Campus Photo Placeholder" 
                     class="rounded-xl shadow-2xl mx-auto w-full max-w-6xl"
                     onerror="this.onerror=null; this.src='https://placehold.co/1200x400/1e293b/FFD700?text=KDA+School+Building';"
                >
            </div>
        </section>

        <!-- Achievements & Milestones Section -->
        <section id="milestones" class="mb-16">
            <h3 class="text-5xl font-bold mb-10 text-center text-white">
                Key Student Achievements
            </h3>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                
                <!-- Milestone 1: Academic Excellence -->
                <div class="card p-6 rounded-xl kda-border">
                    <div class="flex items-center mb-3">
                        <i data-lucide="book-open-check" class="text-yellow-400 w-8 h-8 mr-3"></i>
                        <span class="text-2xl font-semibold gradient-text">Top Academic Scores</span>
                    </div>
                    <p class="text-gray-400">Our senior class achieved a record-breaking 95% average pass rate on national exams, demonstrating consistent academic rigor.</p>
                </div>

                <!-- Milestone 2: University Placement -->
                <div class="card p-6 rounded-xl kda-border">
                    <div class="flex items-center mb-3">
                        <i data-lucide="graduation-cap" class="text-blue-500 w-8 h-8 mr-3"></i>
                        <span class="text-2xl font-semibold gradient-text">University Acceptance</span>
                    </div>
                    <p class="text-gray-400">98% of our graduates received acceptance letters from their top three university choices, including prestigious international institutions.</p>
                </div>

                <!-- Milestone 3: Athletic Success -->
                <div class="card p-6 rounded-xl kda-border">
                    <div class="flex items-center mb-3">
                        <i data-lucide="trophy" class="text-indigo-400 w-8 h-8 mr-3"></i>
                        <span class="text-2xl font-semibold gradient-text">Sports Championships</span>
                    </div>
                    <p class="text-gray-400">The KDA Eagles won 4 state/regional championships this year in Basketball, Debate, Robotics, and Track & Field.</p>
                </div>

                <!-- Milestone 4: Community Service -->
                <div class="card p-6 rounded-xl kda-border">
                    <div class="flex items-center mb-3">
                        <i data-lucide="heart-handshake" class="text-green-400 w-8 h-8 mr-3"></i>
                        <span class="text-2xl font-semibold gradient-text">Community Impact</span>
                    </div>
                    <p class="text-gray-400">Students contributed over 15,000 hours of community service, running successful local clean-up and mentorship programs.</p>
                </div>
            </div>
        </section>

        <!-- Honors & Impact Section -->
        <section id="impact" class="mb-16">
            <h3 class="text-5xl font-bold mb-10 text-center text-white">
                Honors & Cultural Impact
            </h3>
            <div class="lg:flex space-y-10 lg:space-y-0 lg:space-x-10">
                <!-- Key Programs -->
                <div class="lg:w-1/2 p-8 card rounded-xl">
                    <h4 class="text-3xl font-semibold mb-6 border-b border-gray-700 pb-3 text-white">Signature Programs</h4>
                    <ul class="space-y-4">
                        <li class="flex items-center kda-border p-3 rounded-lg">
                            <i data-lucide="microscope" class="text-yellow-500 w-6 h-6 mr-4"></i>
                            <div>
                                <p class="font-bold text-lg">STEM Innovation Lab</p>
                                <p class="text-sm text-gray-400">A dedicated center for robotics, coding, and scientific research projects.</p>
                            </div>
                        </li>
                        <li class="flex items-center kda-border p-3 rounded-lg">
                            <i data-lucide="palette" class="text-red-500 w-6 h-6 mr-4"></i>
                            <div>
                                <p class="font-bold text-lg">Visual & Performing Arts</p>
                                <p class="text-sm text-gray-400">Award-winning drama and music programs with professional-grade facilities.</p>
                            </div>
                        </li>
                        <li class="flex items-center kda-border p-3 rounded-lg">
                            <i data-lucide="users-2" class="text-indigo-500 w-6 h-6 mr-4"></i>
                            <div>
                                <p class="font-bold text-lg">Global Leadership Initiative</p>
                                <p class="text-sm text-gray-400">A curriculum track focused on ethics, governance, and international relations.</p>
                            </div>
                        </li>
                        <li class="flex items-center kda-border p-3 rounded-lg">
                            <i data-lucide="mountain" class="text-green-500 w-6 h-6 mr-4"></i>
                            <div>
                                <p class="font-bold text-lg">Outdoor Education</p>
                                <p class="text-sm text-gray-400">Programs promoting teamwork, resilience, and environmental stewardship.</p>
                            </div>
                        </li>
                    </ul>
                </div>

                <!-- Accreditations / Awards -->
                <div class="lg:w-1/2 p-8 card rounded-xl flex flex-col justify-center">
                    <h4 class="text-3xl font-semibold mb-6 border-b border-gray-700 pb-3 text-white">School Accreditations & Awards</h4>
                    <ul class="space-y-5 text-gray-300">
                        <li class="flex">
                            <i data-lucide="award" class="text-green-400 w-5 h-5 mr-3 mt-1 flex-shrink-0"></i>
                            Awarded Top 10 High School for Innovation' for three consecutive years.
                        </li>
                        <li class="flex">
                            <i data-lucide="award" class="text-green-400 w-5 h-5 mr-3 mt-1 flex-shrink-0"></i>
                            Certified Green School status for excellence in sustainability and environmental education.
                        </li>
                        <li class="flex">
                            <i data-lucide="award" class="text-green-400 w-5 h-5 mr-3 mt-1 flex-shrink-0"></i>
                            Faculty includes two National Teacher of the Year finalists, highlighting staff quality.
                        </li>
                        <li class="flex">
                            <i data-lucide="award" class="text-green-400 w-5 h-5 mr-3 mt-1 flex-shrink-0"></i>
                            Fully accredited by the Council of Independent Schools (CIS).
                        </li>
                    </ul>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="py-6 border-t border-gray-800 bg-black">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-gray-500 text-sm">
            <p>&copy; 2025 King David Academy Showcase. Dedicated to student success.</p>
        </div>
    </footer>

    <script>
        // Initialize lucide icons for display
        lucide.createIcons();
    </script>
</body>
</html>
