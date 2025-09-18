<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parvesh Rawal - Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom animations */
        .icon-hover {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .icon-hover:hover {
            transform: scale(1.2) rotate(5deg);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .section-fade-in {
            animation: fadeIn 1s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .pulse {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800 font-sans">
    <!-- Hero Section -->
    <header class="bg-gradient-to-r from-blue-500 to-indigo-600 text-white py-16 px-4 text-center section-fade-in">
        <h1 class="text-4xl md:text-6xl font-bold mb-4 pulse">Hi 👋, I'm Parvesh Rawal</h1>
        <p class="text-xl md:text-2xl mb-8">A passionate Machine Learning and Deep Learning student eager to explore the world of data and AI.</p>
        <div class="flex justify-center space-x-4">
            <a href="https://x.com/Parveshiiii" class="bg-white text-blue-500 px-4 py-2 rounded hover:bg-blue-100 transition">Twitter</a>
            <a href="https://www.linkedin.com/in/parvesh-rawal/" class="bg-white text-blue-700 px-4 py-2 rounded hover:bg-blue-100 transition">LinkedIn</a>
            <a href="https://www.instagram.com/parveshiiii/" class="bg-white text-pink-500 px-4 py-2 rounded hover:bg-pink-100 transition">Instagram</a>
            <a href="https://github.com/Parveshiiii" class="bg-white text-gray-800 px-4 py-2 rounded hover:bg-gray-100 transition">GitHub</a>
        </div>
    </header>

    <!-- Skills Section -->
    <section id="skills" class="py-12 px-4 md:px-8 section-fade-in">
        <h2 class="text-3xl font-bold text-center mb-8">🚀 Languages and Tools I Use</h2>
        <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 lg:grid-cols-8 gap-6 max-w-6xl mx-auto">
            <!-- Machine Learning & Data Science -->
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" class="w-16 h-16 icon-hover" />
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow" class="w-16 h-16 icon-hover" />
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" alt="PyTorch" class="w-16 h-16 icon-hover" />
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="Scikit-learn" class="w-16 h-16 icon-hover" />
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="Pandas" class="w-16 h-16 icon-hover" />
            <img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" alt="Seaborn" class="w-16 h-16 icon-hover" />
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" alt="OpenCV" class="w-16 h-16 icon-hover" />

            <!-- Web Development -->
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" class="w-16 h-16 icon-hover" />
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" class="w-16 h-16 icon-hover" />
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" class="w-16 h-16 icon-hover" />
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Node.js" class="w-16 h-16 icon-hover" />
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" alt="Flask" class="w-16 h-16 icon-hover" />
            <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="TailwindCSS" class="w-16 h-16 icon-hover" />

            <!-- Databases & Services -->
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB" class="w-16 h-16 icon-hover" />
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL" class="w-16 h-16 icon-hover" />
            <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="Firebase" class="w-16 h-16 icon-hover" />
            <img src="https://www.vectorlogo.zone/logos/appwriteio/appwriteio-icon.svg" alt="Appwrite" class="w-16 h-16 icon-hover" />

            <!-- Others -->
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git" class="w-16 h-16 icon-hover" />
        </div>
    </section>

    <!-- Projects Section (Added) -->
    <section id="projects" class="bg-white py-12 px-4 md:px-8 section-fade-in">
        <h2 class="text-3xl font-bold text-center mb-8">📁 My Projects</h2>
        <div class="max-w-4xl mx-auto space-y-6">
            <div class="p-4 border rounded shadow hover:shadow-lg transition">
                <h3 class="text-xl font-semibold"><a href="https://github.com/Parveshiiii/Dev-Stack-Agents" class="text-blue-500 hover:underline">Dev-Stack-Agents</a></h3>
                <p>An army of agents. One repo. Zero manual coding. (Stars: 6, Forks: 1)</p>
            </div>
            <div class="p-4 border rounded shadow hover:shadow-lg transition">
                <h3 class="text-xl font-semibold"><a href="https://github.com/Parveshiiii/Deepresearch-Agent" class="text-blue-500 hover:underline">Deepresearch-Agent</a></h3>
                <p>Deep research agent built with Python. (Stars: 2, Forks: 0)</p>
            </div>
            <div class="p-4 border rounded shadow hover:shadow-lg transition">
                <h3 class="text-xl font-semibold"><a href="https://github.com/Parveshiiii/Search.tool" class="text-blue-500 hover:underline">Search.tool</a></h3>
                <p>Search tool from Blazingboys. (Stars: 1, Forks: 0, Language: Python)</p>
            </div>
            <div class="p-4 border rounded shadow hover:shadow-lg transition">
                <h3 class="text-xl font-semibold"><a href="https://github.com/Parveshiiii/Web-Agent" class="text-blue-500 hover:underline">Web-Agent</a></h3>
                <p>Run AI Agent in your browser (forked). (Stars: 0, Forks: 0, Language: Python)</p>
            </div>
        </div>
    </section>

    <!-- GitHub Stats Section -->
    <section id="stats" class="py-12 px-4 md:px-8 section-fade-in">
        <h2 class="text-3xl font-bold text-center mb-8">📊 My GitHub Stats</h2>
        <div class="flex flex-col md:flex-row justify-center items-center space-y-8 md:space-y-0 md:space-x-8">
            <img src="https://github-readme-stats.vercel.app/api?username=Parveshiiii&show_icons=true&locale=en&theme=radical" alt="GitHub Stats" class="w-full md:w-1/2 rounded shadow icon-hover" />
            <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Parveshiiii&show_icons=true&locale=en&layout=compact&theme=radical" alt="Top Languages" class="w-full md:w-1/2 rounded shadow icon-hover" />
        </div>
        <div class="mt-8 flex justify-center">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=Parveshiiii&theme=radical" alt="GitHub Streak" class="rounded shadow icon-hover" />
        </div>
        <div class="mt-8 flex justify-center">
            <img src="https://github-profile-trophy.vercel.app/?username=Parveshiiii&theme=radical" alt="GitHub Trophies" class="rounded shadow icon-hover" />
        </div>
    </section>

    <!-- Recent X Posts Section (Added) -->
    <section id="recent-x" class="bg-gray-200 py-12 px-4 md:px-8 section-fade-in">
        <h2 class="text-3xl font-bold text-center mb-8">🗣️ Recent Posts on X</h2>
        <div class="max-w-4xl mx-auto space-y-6">
            <div class="p-4 bg-white rounded shadow hover:shadow-lg transition">
                <p class="text-sm text-gray-500">June 5, 2025</p>
                <p>are you jokeing do you really think you all or the world can trust trump he is just taking you all to the greatest recession of this century</p>
                <a href="https://x.com/Parveshiiii/status/1930464439335088587" class="text-blue-500 hover:underline">View Post</a>
            </div>
            <div class="p-4 bg-white rounded shadow hover:shadow-lg transition">
                <p class="text-sm text-gray-500">June 5, 2025</p>
                <p>bro then what we can do you don't know the people who suffered as an indian i don't think we should advocate people like Mally and RCB won the cup doesn't means we give credit to him</p>
                <a href="https://x.com/Parveshiiii/status/1930463724646646267" class="text-blue-500 hover:underline">View Post</a>
            </div>
            <div class="p-4 bg-white rounded shadow hover:shadow-lg transition">
                <p class="text-sm text-gray-500">June 5, 2025</p>
                <p>who are you are you from india</p>
                <a href="https://x.com/Parveshiiii/status/1930463239730835823" class="text-blue-500 hover:underline">View Post</a>
            </div>
            <div class="p-4 bg-white rounded shadow hover:shadow-lg transition">
                <p class="text-sm text-gray-500">June 5, 2025</p>
                <p>idk why this guy is supporting Mallya i doubt if he is really indian as indians know what he really did here</p>
                <a href="https://x.com/Parveshiiii/status/1930463038106112192" class="text-blue-500 hover:underline">View Post</a>
            </div>
            <div class="p-4 bg-white rounded shadow hover:shadow-lg transition">
                <p class="text-sm text-gray-500">June 5, 2025</p>
                <p>sir who are you what is the problem with you its our country's matter and you should not come in between a non citizen can bever understand what really happened due to Mallya</p>
                <a href="https://x.com/Parveshiiii/status/1930462327289139610" class="text-blue-500 hover:underline">View Post</a>
            </div>
            <!-- Limited to top 5 for brevity; you can add more if needed -->
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-4 text-center">
        <p>&copy; 2025 Parvesh Rawal. All rights reserved.</p>
    </footer>
</body>
</html>
