<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atul Kumar - GitHub Profile Preview</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        @keyframes gradient-animation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes blink {
            50% { opacity: 0; }
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117;
            background-image: radial-gradient(circle at top, rgba(29, 78, 216, 0.15) 0%, transparent 40%);
            color: #c9d1d9;
        }
        .badge {
            transition: transform 0.2s ease-in-out;
        }
        .badge:hover {
            transform: translateY(-2px);
        }
        hr {
            border-color: #21262d;
        }
        .typing-cursor {
            display: inline-block;
            width: 10px;
            height: 1.4rem;
            background-color: #58a6ff;
            animation: blink 1s step-end infinite;
            vertical-align: bottom;
            margin-left: 4px;
        }
        
        .fade-in-section {
            opacity: 0;
            animation: fadeInUp 0.8s ease-out forwards;
        }

        .tech-skill {
            transition: all 0.2s ease-in-out;
        }
        .tech-skill:hover {
            transform: scale(1.1);
            box-shadow: 0 0 15px rgba(59, 130, 246, 0.5);
        }
    </style>
</head>
<body class="antialiased">

    <div class="max-w-4xl mx-auto p-4 sm:p-6 lg:p-8">

        <!-- Header Section -->
        <div class="text-center py-8 fade-in-section" style="animation-delay: 100ms;">
            <h1 class="text-4xl sm:text-5xl font-bold text-white">Hi 👋, I'm Atul Kumar</h1>
            <h3 class="text-xl sm:text-2xl text-gray-400 mt-2 h-8"><span id="typing-text"></span><span class="typing-cursor"></span></h3>
            <p class="mt-4 max-w-2xl mx-auto text-gray-400">Fervently dedicated to building intelligent solutions and continuously learning.</p>
        </div>

        <!-- Social Links -->
        <div class="flex justify-center items-center gap-3 my-6 fade-in-section" style="animation-delay: 200ms;">
            <a href="https://linkedin.com/in/atulkr245" target="_blank" class="badge">
                <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
            </a>
            <a href="mailto:atulsams245@gmail.com" class="badge">
                <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail Badge"/>
            </a>
            <a href="https://www.leetcode.com/Atul245156" target="_blank" class="badge">
                <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode Badge"/>
            </a>
            <a href="https://kaggle.com/atulkumar245" target="_blank" class="badge">
                <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle Badge"/>
            </a>
        </div>

        <hr class="my-8 fade-in-section" style="animation-delay: 300ms;">

        <!-- About Me & Stats Section -->
        <div class="flex flex-col md:flex-row gap-8 fade-in-section" style="animation-delay: 400ms;">
            <!-- Left Column: About Me -->
            <div class="w-full md:w-3/5">
                <h2 class="text-2xl font-bold text-white mb-4">👨‍💻 About Me</h2>
                <ul class="space-y-3 text-gray-300 list-inside">
                    <li><span class="text-green-400 mr-2">🌱</span> I’m currently diving deep into <strong class="font-semibold text-white">React</strong> and <strong class="font-semibold text-white">Advanced Deep Learning</strong> concepts.</li>
                    <li><span class="text-blue-400 mr-2">💬</span> Ask me anything about <strong class="font-semibold text-white">Machine Learning</strong> or <strong class="font-semibold text-white">Data Structures</strong>.</li>
                    <li><span class="text-purple-400 mr-2">📫</span> You can reach me at: <a href="mailto:atulsams245@gmail.com" class="font-semibold text-white hover:underline">atulsams245@gmail.com</a></li>
                    <li><span class="text-yellow-400 mr-2">⚡</span> Fun fact: I believe the best code is not just functional, but also elegant and readable.</li>
                </ul>
            </div>
            <!-- Right Column: Stats -->
            <div class="w-full md:w-2/5 space-y-4">
                <img class="w-full" src="https://github-readme-stats.vercel.app/api?username=Atul245&show_icons=true&theme=dracula&hide_border=true&include_all_commits=true&count_private=true" alt="Atul's GitHub Stats"/>
                <img class="w-full" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Atul245&layout=compact&theme=dracula&hide_border=true" alt="Top Languages"/>
            </div>
        </div>

        <hr class="my-8 fade-in-section" style="animation-delay: 500ms;">

        <!-- Tech Stack Section -->
        <div class="fade-in-section" style="animation-delay: 600ms;">
            <h2 class="text-2xl font-bold text-white mb-4 text-center sm:text-left">🛠️ Tech Stack & Skills</h2>
            <div class="space-y-4">
                <div class="flex flex-wrap items-center gap-x-4 gap-y-2">
                    <strong class="font-semibold text-white w-full sm:w-auto">Languages:</strong>
                    <span class="tech-skill bg-gray-800 text-blue-300 text-xs font-semibold px-2.5 py-1 rounded-full">Python</span>
                    <span class="tech-skill bg-gray-800 text-blue-300 text-xs font-semibold px-2.5 py-1 rounded-full">C++</span>
                    <span class="tech-skill bg-gray-800 text-blue-300 text-xs font-semibold px-2.5 py-1 rounded-full">JavaScript</span>
                    <span class="tech-skill bg-gray-800 text-blue-300 text-xs font-semibold px-2.5 py-1 rounded-full">TypeScript</span>
                    <span class="tech-skill bg-gray-800 text-blue-300 text-xs font-semibold px-2.5 py-1 rounded-full">Java</span>
                </div>
                 <div class="flex flex-wrap items-center gap-x-4 gap-y-2">
                    <strong class="font-semibold text-white w-full sm:w-auto">Frontend:</strong>
                    <span class="tech-skill bg-gray-800 text-green-300 text-xs font-semibold px-2.5 py-1 rounded-full">React</span>
                    <span class="tech-skill bg-gray-800 text-green-300 text-xs font-semibold px-2.5 py-1 rounded-full">HTML5</span>
                    <span class="tech-skill bg-gray-800 text-green-300 text-xs font-semibold px-2.5 py-1 rounded-full">CSS3</span>
                    <span class="tech-skill bg-gray-800 text-green-300 text-xs font-semibold px-2.5 py-1 rounded-full">TailwindCSS</span>
                </div>
                <div class="flex flex-wrap items-center gap-x-4 gap-y-2">
                    <strong class="font-semibold text-white w-full sm:w-auto">Backend:</strong>
                    <span class="tech-skill bg-gray-800 text-yellow-300 text-xs font-semibold px-2.5 py-1 rounded-full">Node.js</span>
                    <span class="tech-skill bg-gray-800 text-yellow-300 text-xs font-semibold px-2.5 py-1 rounded-full">Express.js</span>
                    <span class="tech-skill bg-gray-800 text-yellow-300 text-xs font-semibold px-2.5 py-1 rounded-full">MySQL</span>
                    <span class="tech-skill bg-gray-800 text-yellow-300 text-xs font-semibold px-2.5 py-1 rounded-full">MongoDB</span>
                </div>
                 <div class="flex flex-wrap items-center gap-x-4 gap-y-2">
                    <strong class="font-semibold text-white w-full sm:w-auto">ML / AI:</strong>
                    <span class="tech-skill bg-gray-800 text-red-300 text-xs font-semibold px-2.5 py-1 rounded-full">TensorFlow</span>
                    <span class="tech-skill bg-gray-800 text-red-300 text-xs font-semibold px-2.5 py-1 rounded-full">Scikit-learn</span>
                    <span class="tech-skill bg-gray-800 text-red-300 text-xs font-semibold px-2.5 py-1 rounded-full">Pandas</span>
                    <span class="tech-skill bg-gray-800 text-red-300 text-xs font-semibold px-2.5 py-1 rounded-full">OpenCV</span>
                </div>
                <div class="flex flex-wrap items-center gap-x-4 gap-y-2">
                    <strong class="font-semibold text-white w-full sm:w-auto">Tools & DevOps:</strong>
                    <span class="tech-skill bg-gray-800 text-purple-300 text-xs font-semibold px-2.5 py-1 rounded-full">AWS</span>
                    <span class="tech-skill bg-gray-800 text-purple-300 text-xs font-semibold px-2.5 py-1 rounded-full">Docker</span>
                    <span class="tech-skill bg-gray-800 text-purple-300 text-xs font-semibold px-2.5 py-1 rounded-full">Git</span>
                    <span class="tech-skill bg-gray-800 text-purple-300 text-xs font-semibold px-2.5 py-1 rounded-full">Jenkins</span>
                    <span class="tech-skill bg-gray-800 text-purple-300 text-xs font-semibold px-2.5 py-1 rounded-full">Linux</span>
                </div>
            </div>
        </div>

        <hr class="my-8 fade-in-section" style="animation-delay: 700ms;">

        <!-- Activity Graph Section -->
        <div class="fade-in-section" style="animation-delay: 800ms;">
            <h2 class="text-2xl font-bold text-white mb-4 text-center">📊 GitHub Activity</h2>
            <div class="p-4 bg-[#2D2B55] rounded-lg shadow-lg">
                 <img src="https://github-readme-activity-graph.vercel.app/graph?username=Atul245&theme=react-dark&hide_border=true&bg_color=2D2B55" alt="activity graph"/>
            </div>
        </div>

    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const typingTextElement = document.getElementById('typing-text');
            const roles = ['AI & Machine Learning Engineer', 'Full-Stack Developer'];
            let roleIndex = 0;
            let charIndex = 0;
            let isDeleting = false;

            function type() {
                const currentRole = roles[roleIndex];
                let displayText = '';

                if (isDeleting) {
                    displayText = currentRole.substring(0, charIndex - 1);
                    charIndex--;
                } else {
                    displayText = currentRole.substring(0, charIndex + 1);
                    charIndex++;
                }

                typingTextElement.textContent = displayText;

                let typeSpeed = isDeleting ? 100 : 200;

                if (!isDeleting && charIndex === currentRole.length) {
                    typeSpeed = 2000; // Pause at the end
                    isDeleting = true;
                } else if (isDeleting && charIndex === 0) {
                    isDeleting = false;
                    roleIndex = (roleIndex + 1) % roles.length;
                    typeSpeed = 500; // Pause before typing next role
                }

                setTimeout(type, typeSpeed);
            }

            type();
        });
    </script>

</body>
</html>


