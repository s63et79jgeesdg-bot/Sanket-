<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ugam Space | Architecture Begins in the Ground</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom font import for a professional look */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f3ed; /* Very light earth tone */
            color: #333333; /* Dark charcoal text */
        }
        /* Styling for the minimalist navigation active state */
        .nav-link:hover {
            color: #795548; /* Darker terracotta hover */
            text-decoration: underline;
        }
        .section-padding {
            padding: 4rem 1.5rem;
            max-width: 1200px;
            margin: 0 auto;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header & Navigation -->
    <header class="sticky top-0 z-50 bg-white bg-opacity-95 shadow-md backdrop-blur-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center py-4 md:justify-start md:space-x-10">
                <!-- Logo/Brand -->
                <div class="flex justify-start lg:w-0 lg:flex-1">
                    <a href="#home" class="text-xl font-bold text-[#4E342E] uppercase tracking-wider">
                        UGAM SPACE
                    </a>
                </div>
                <!-- Navigation Links (Hidden on small screens, shown as menu) -->
                <nav class="hidden md:flex space-x-8">
                    <a href="#home" class="nav-link text-sm font-medium text-gray-700 transition duration-150 ease-in-out">Home</a>
                    <a href="#philosophy" class="nav-link text-sm font-medium text-gray-700 transition duration-150 ease-in-out">Philosophy</a>
                    <a href="#insights" class="nav-link text-sm font-medium text-gray-700 transition duration-150 ease-in-out">Insights</a>
                    <a href="#projects" class="nav-link text-sm font-medium text-gray-700 transition duration-150 ease-in-out">Projects</a>
                    <a href="#connect" class="nav-link text-sm font-medium text-gray-700 transition duration-150 ease-in-out">Connect</a>
                </nav>
            </div>
        </div>
    </header>

    <!-- 1. Home Section (Hero) -->
    <section id="home" class="section-padding pt-16 md:pt-24 min-h-screen flex items-center bg-cover bg-center" 
        style="background-image: url('https://placehold.co/1200x800/A0522D/F7F3ED?text=Striking+Visual+Placeholder');">
        <!-- Overlay for readability -->
        <div class="absolute inset-0 bg-black opacity-40"></div>
        <div class="relative z-10 text-center w-full">
            <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold text-white leading-tight mb-4 drop-shadow-lg">
                Ugam Space: Architecture Begins in the Ground
            </h1>
            <p class="mt-4 text-xl sm:text-2xl text-gray-100 font-light max-w-3xl mx-auto drop-shadow-md">
                A collaborative collective dedicated to design that is integrated with ecological principles and traditional wisdom.
            </p>
            <div class="mt-8">
                <a href="#philosophy" class="inline-flex items-center justify-center px-6 py-3 border border-transparent text-base font-medium rounded-full shadow-lg text-white bg-[#795548] hover:bg-[#A0522D] transition duration-300 transform hover:scale-105">
                    Explore Our Philosophy &rarr;
                </a>
            </div>
        </div>
    </section>

    <!-- 2. Our Philosophy / About Us Section -->
    <section id="philosophy" class="section-padding bg-[#fffbf6]">
        <h2 class="text-3xl font-bold text-center mb-12 text-[#4E342E]">Rethinking Our Foundations</h2>
        
        <div class="grid md:grid-cols-2 gap-12 items-center">
            <!-- Left Column: Vision & Mission -->
            <div class="space-y-8">
                <p class="text-xl font-medium text-gray-700 leading-relaxed border-l-4 border-[#795548] pl-4">
                    For too long, architecture has sought to conquer the environment, treating the earth beneath us as merely a foundation to be paved over. At **Ugam Space**, we challenge this disconnect, advocating for a profound return to the principles of integration, deep ecology, and traditional wisdom. We believe that truly resilient, sustainable, and beautiful design emerges when we understand and respect the **soil as a living, fundamental partner** in the act of creation.
                </p>

                <!-- Aim Block -->
                <div class="p-6 bg-[#f0e9e1] rounded-lg shadow-inner">
                    <h3 class="text-2xl font-semibold text-[#795548] mb-2">Our Aim (The Why)</h3>
                    <p class="text-gray-600">To create awareness and deep understanding of the vital connections between architecture, the natural environment, and the traditional knowledge systems that have successfully housed humanity for millennia. We seek to shift the global conversation from extraction and separation to **regeneration and synthesis**.</p>
                </div>
            </div>

            <!-- Right Column: Guiding Principles & Team -->
            <div class="space-y-8">
                <h3 class="text-2xl font-semibold text-[#4E342E] mb-4">Our Guiding Principles</h3>
                <ul class="space-y-4">
                    <li class="flex items-start">
                        <span class="text-[#A0522D] text-2xl mr-3">&diams;</span>
                        <p><strong class="font-medium">Respect for Nature:</strong> Every design decision must prioritize the health and integrity of the local ecosystem.</p>
                    </li>
                    <li class="flex items-start">
                        <span class="text-[#A0522D] text-2xl mr-3">&diams;</span>
                        <p><strong class="font-medium">Traditional Wisdom:</strong> We honor and learn from ancestral building practices that demonstrate long-term ecological and cultural harmony.</p>
                    </li>
                    <li class="flex items-start">
                        <span class="text-[#A0522D] text-2xl mr-3">&diams;</span>
                        <p><strong class="font-medium">Deep Sustainability:</strong> We look beyond simple "green" metrics to promote regenerative practices and circular material economies.</p>
                    </li>
                </ul>

                <h3 class="text-2xl font-semibold text-[#4E342E] pt-4 border-t border-gray-300">The Core Collective</h3>
                <p class="text-gray-600">
                    **Ugam Space** is initiated by four dedicated co-creators who share a singular vision: **Sanket, Riya, Varsha, and Isha.** Our strength lies in collaboration, uniting expertise across architectural theory, material science, ecological systems, cultural research, and visual communication. We are a growing community, dedicated to translating our philosophical foundation into actionable, regenerative design practices and fostering dialogue with all who join us.
                </p>
            </div>
        </div>
    </section>

    <!-- 3. Concepts / Insights (Blog Placeholder) -->
    <section id="insights" class="section-padding bg-[#f7f3ed]">
        <h2 class="text-3xl font-bold text-center mb-12 text-[#4E342E]">Concepts & Insights</h2>
        <p class="text-center text-lg text-gray-700 mb-10 max-w-3xl mx-auto">
            The heart of our platform, where we expand on the science, history, and practice of grounded architecture through detailed articles and essays.
        </p>

        <!-- Placeholder Grid for 3 Articles -->
        <div class="grid md:grid-cols-3 gap-8">
            <!-- Insight 1 -->
            <div class="bg-white p-6 rounded-xl shadow-lg hover:shadow-xl transition duration-300 border border-[#A0522D]/10">
                <h3 class="text-xl font-semibold text-[#795548] mb-2">Soil as Living Architecture</h3>
                <p class="text-gray-600 text-sm mb-4">A deep dive into soil microbiology and its structural properties, moving beyond the idea of inert dirt.</p>
                <a href="#" class="text-sm font-medium text-[#A0522D] hover:underline">Read Article &rarr;</a>
            </div>
            <!-- Insight 2 -->
            <div class="bg-white p-6 rounded-xl shadow-lg hover:shadow-xl transition duration-300 border border-[#A0522D]/10">
                <h3 class="text-xl font-semibold text-[#795548] mb-2">The Legacy of Rammed Earth</h3>
                <p class="text-gray-600 text-sm mb-4">Exploring historical methods and modern innovations in using compressed earth for durable, carbon-neutral construction.</p>
                <a href="#" class="text-sm font-medium text-[#A0522D] hover:underline">Read Article &rarr;</a>
            </div>
            <!-- Insight 3 -->
            <div class="bg-white p-6 rounded-xl shadow-lg hover:shadow-xl transition duration-300 border border-[#A0522D]/10">
                <h3 class="text-xl font-semibold text-[#795548] mb-2">Cultural Wisdom in Building</h3>
                <p class="text-gray-600 text-sm mb-4">How ancestral knowledge informs resilient design strategies in various climates around the world.</p>
                <a href="#" class="text-sm font-medium text-[#A0522D] hover:underline">Read Article &rarr;</a>
            </div>
        </div>
    </section>

    <!-- 4. Projects / Case Studies Placeholder -->
    <section id="projects" class="section-padding bg-[#fffbf6]">
        <h2 class="text-3xl font-bold text-center mb-12 text-[#4E342E]">Projects & Case Studies</h2>
        <p class="text-center text-lg text-gray-700 mb-10 max-w-3xl mx-auto">
            Showcasing real-world examples (historical and contemporary) that exemplify our principles of grounded, regenerative design.
        </p>

        <!-- Placeholder Grid for 2 Projects -->
        <div class="grid md:grid-cols-2 gap-8">
            <!-- Project 1 -->
            <div class="rounded-xl overflow-hidden shadow-xl bg-white border border-[#4E342E]/10">
                <img src="https://placehold.co/600x400/A0522D/F7F3ED?text=Project+Placeholder+1" alt="Project Example 1" class="w-full h-64 object-cover">
                <div class="p-6">
                    <h3 class="text-2xl font-semibold text-[#4E342E] mb-2">The Regenerative Earth Home</h3>
                    <p class="text-gray-600 mb-4">A modern interpretation of passive design, using local cob and greywater recycling integrated into a living roof system.</p>
                    <a href="#" class="text-lg font-medium text-[#795548] hover:underline">View Case Study &rarr;</a>
                </div>
            </div>
            <!-- Project 2 -->
            <div class="rounded-xl overflow-hidden shadow-xl bg-white border border-[#4E342E]/10">
                <img src="https://placehold.co/600x400/795548/F7F3ED?text=Project+Placeholder+2" alt="Project Example 2" class="w-full h-64 object-cover">
                <div class="p-6">
                    <h3 class="text-2xl font-semibold text-[#4E342E] mb-2">Ancestral Building Restoration</h3>
                    <p class="text-gray-600 mb-4">Documenting the meticulous restoration of a 500-year-old adobe structure, preserving its structural integrity and wisdom.</p>
                    <a href="#" class="text-lg font-medium text-[#795548] hover:underline">View Case Study &rarr;</a>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. Connect / CTA Section -->
    <section id="connect" class="section-padding bg-[#A0522D] text-white">
        <div class="text-center">
            <h2 class="text-3xl font-bold mb-4">Join the Ugam Space Movement</h2>
            <p class="text-xl font-light mb-8 max-w-2xl mx-auto">
                Be part of the community dedicated to design that honors the earth. Sign up for our **Insights Newsletter** and follow our journey.
            </p>
            <form class="max-w-md mx-auto">
                <div class="flex flex-col sm:flex-row gap-4">
                    <input type="email" placeholder="Your Email Address" required 
                           class="flex-1 px-4 py-3 rounded-lg text-gray-900 border-2 border-transparent focus:border-[#F7F3ED] focus:ring-0 transition duration-300 shadow-inner"
                           aria-label="Email for newsletter signup">
                    <button type="submit" 
                            class="px-6 py-3 bg-[#4E342E] text-white font-semibold rounded-lg shadow-lg hover:bg-black transition duration-300 transform hover:scale-[1.02]">
                        Subscribe
                    </button>
                </div>
            </form>
            <div class="mt-8">
                <p class="text-lg mb-4">Follow Our Journey:</p>
                <!-- Placeholder Social Icons (Using simple text for minimalist design) -->
                <div class="flex justify-center space-x-6">
                    <a href="#" class="text-xl hover:text-[#f0e9e1] transition duration-300" aria-label="Link to Instagram">Instagram</a>
                    <a href="#" class="text-xl hover:text-[#f0e9e1] transition duration-300" aria-label="Link to Pinterest">Pinterest</a>
                    <a href="#" class="text-xl hover:text-[#f0e9e1] transition duration-300" aria-label="Link to LinkedIn">LinkedIn</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-[#4E342E] text-gray-300 py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-sm">
            <p>&copy; 2025 Ugam Space. All rights reserved.</p>
            <p class="mt-2">Built with respect for the earth and a minimalist design philosophy.</p>
        </div>
    </footer>

</body>
</html>

