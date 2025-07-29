<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shubham Darji // AI & Data Engineer</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Fira+Code&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117; /* GitHub Dark Mode Background */
            color: #c9d1d9; /* Light gray text */
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 1rem;
        }
        .container {
            background-color: #161b22; /* Slightly lighter background for the terminal */
            border: 1px solid #30363d; /* Border color */
            border-radius: 0.5rem; /* Rounded corners */
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
            max-width: 900px; /* Max width for readability */
            width: 100%;
            padding: 1.5rem;
            box-sizing: border-box;
        }
        .terminal-header {
            display: flex;
            align-items: center;
            padding-bottom: 1rem;
            border-bottom: 1px solid #30363d;
            margin-bottom: 1.5rem;
        }
        .terminal-buttons div {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            margin-right: 8px;
        }
        .close { background-color: #ff5f56; }
        .minimize { background-color: #ffbd2e; }
        .maximize { background-color: #27c93f; }

        .terminal-content {
            font-family: 'Fira Code', monospace; /* Monospaced font for code/terminal look */
            white-space: pre-wrap; /* Preserve whitespace and wrap text */
            word-wrap: break-word; /* Break long words */
            line-height: 1.6;
        }
        .typing-svg {
            display: block;
            margin-left: auto;
            margin-right: auto;
            max-width: 100%; /* Ensure it's responsive */
            height: auto;
        }
        .neon-blue {
            color: #00F7FF; /* Neon blue */
        }
        .neon-green {
            color: #27c93f; /* Neon green */
        }
        .text-header {
            font-weight: 700;
            color: #c9d1d9;
            margin-top: 1.5rem;
            margin-bottom: 0.5rem;
            font-size: 1.25rem;
        }
        .grid-container {
            display: grid;
            gap: 1rem;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        }
        .grid-item {
            background-color: #0d1117; /* Darker background for grid items */
            padding: 1rem;
            border-radius: 0.375rem; /* Slightly smaller rounded corners for items */
            border: 1px solid #30363d;
        }
        /* Responsive adjustments for smaller screens */
        @media (max-width: 640px) {
            .container {
                padding: 1rem;
            }
            .terminal-header {
                padding-bottom: 0.75rem;
                margin-bottom: 1rem;
            }
            .terminal-content {
                font-size: 0.875rem;
            }
            .text-header {
                font-size: 1.125rem;
            }
            .grid-container {
                grid-template-columns: 1fr; /* Stack items on small screens */
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="terminal-header">
            <div class="flex">
                <div class="close"></div>
                <div class="minimize"></div>
                <div class="maximize"></div>
            </div>
            <span class="text-xs text-gray-500 ml-2">shubham-darji-portfolio.sh</span>
        </div>

        <div class="terminal-content">
            <p align="center">
                <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=00F7FF&center=true&vCenter=true&width=435&lines=Shubham+Darji;AI+%26+Data+Engineer;Deep+Learning+%7C+MLOps+%7C+Cloud+%7C+Big+Data" alt="Typing SVG" class="typing-svg" />
            </p>

            <pre align="center" class="neon-blue text-lg">
█▀█ █░█ █▄░█ █▀▀ █░█ ▄▀█ █▀ █▀█ █▄█
█▀▀ █▄█ █░▀█ ██▄ █▀█ █▀█ ▄█ █▄█ ░█░
            </pre>

            <p align="center">
                <img src="https://komarev.com/ghpvc/?username=shubham7310&label=Profile+Views&color=00f7ff&style=for-the-badge" alt="profile views" class="inline-block" />
            </p>

            <p class="text-xl font-bold border-b border-[#30363d] pb-2 mt-4">&gt; 🔐 `whoami`</p>
            <pre class="mt-4">
👨‍💻  Name      : Shubham Darji
📍  Location  : Mumbai, India
🎓  Student   : B.E. in Computer Engineering @ KJSIT
🛠️  Role      : AI & Data Engineer
🎯  Focus     : ML Pipelines | MLOps | Data Engineering | AWS
            </pre>

            <p class="text-xl font-bold border-b border-[#30363d] pb-2 mt-6">&gt; 🔧 `toolkit --show all`</p>
            <div class="grid-container mt-4">
                <div class="grid-item">
                    <p class="text-header neon-green">Languages</p>
                    <ul class="list-disc list-inside ml-4">
                        <li>Python</li>
                        <li>Java</li>
                        <li>JavaScript</li>
                        <li>C++</li>
                        <li>SQL</li>
                    </ul>
                </div>
                <div class="grid-item">
                    <p class="text-header neon-green">ML, Data & Cloud</p>
                    <ul class="list-disc list-inside ml-4">
                        <li>Deep Learning</li>
                        <li>Machine Learning</li>
                        <li>Data Engineering</li>
                        <li>MLOps</li>
                        <li>AWS</li>
                        <li>Big Data</li>
                    </ul>
                </div>
                <div class="grid-item">
                    <p class="text-header neon-green">Tools & Databases</p>
                    <ul class="list-disc list-inside ml-4">
                        <li>TensorFlow</li>
                        <li>PyTorch</li>
                        <li>Docker</li>
                        <li>Kubernetes</li>
                        <li>Apache Spark</li>
                        <li>SQL, NoSQL</li>
                    </ul>
                </div>
            </div>

            <p class="text-xl font-bold border-b border-[#30363d] pb-2 mt-6">&gt; 📂 `projects.log --tail`</p>
            <div class="overflow-x-auto mt-4 rounded-md border border-[#30363d]">
                <table class="min-w-full bg-[#0d1117] text-left">
                    <thead>
                        <tr class="bg-[#161b22]">
                            <th class="py-2 px-4 border-b border-[#30363d] text-sm font-semibold text-[#00F7FF] rounded-tl-md">Project Name</th>
                            <th class="py-2 px-4 border-b border-[#30363d] text-sm font-semibold text-[#00F7FF]">Status</th>
                            <th class="py-2 px-4 border-b border-[#30363d] text-sm font-semibold text-[#00F7FF] rounded-tr-md">Achievement</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td class="py-2 px-4 border-b border-[#30363d]">🚑 Lung Cancer ML</td>
                            <td class="py-2 px-4 border-b border-[#30363d]">📢 Published</td>
                            <td class="py-2 px-4 border-b border-[#30363d]">93% accuracy + IEEE Paper</td>
                        </tr>
                        <tr>
                            <td class="py-2 px-4 border-b border-[#30363d]">🧵 Fabric Defect DL</td>
                            <td class="py-2 px-4 border-b border-[#30363d]">📢 Published</td>
                            <td class="py-2 px-4 border-b border-[#30363d]">83% accuracy + 20% optimized Swin</td>
                        </tr>
                        <tr>
                            <td class="py-2 px-4 border-b border-[#30363d]">🥫 Food Pantry System</td>
                            <td class="py-2 px-4 border-b border-[#30363d]">✅ Deployed</td>
                            <td class="py-2 px-4 border-b border-[#30363d]">Boosted NGO ops by 40%</td>
                        </tr>
                        <tr>
                            <td class="py-2 px-4 rounded-bl-md">🧮 BMI + Diet Planner</td>
                            <td class="py-2 px-4">✅ Deployed</td>
                            <td class="py-2 px-4 rounded-br-md">Engaged 30% more users</td>
                        </tr>
                    </tbody>
                </table>
            </div>


            <p class="text-xl font-bold border-b border-[#30363d] pb-2 mt-6">&gt; 🏆 `achievements.sh`</p>
            <ul class="list-disc list-inside ml-4 mt-4">
                <li>🥇 Smart India Hackathon Finalist (Top 25)</li>
                <li>🛠️ Technical Admin – CSI, KJSIT (2024–25)</li>
                <li>🧠 Certifications from DeepLearning.AI, AWS, UC Davis, and UPenn</li>
                <li>🧑‍🏫 Organized 500+ participant tech events (e.g., Code Odyssey 3.0)</li>
            </ul>

            <p class="text-xl font-bold border-b border-[#30363d] pb-2 mt-6">&gt; 📊 `git stats --fetch`</p>
            <!-- GitHub Stats Placeholder - Replace with actual images or integrate API calls if preferred -->
            <p align="center" class="mt-4">
                <img src="https://github-readme-stats.vercel.app/api?username=shubham7310&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="Shubham's GitHub Stats" class="inline-block w-full sm:w-auto mb-4"/>
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=shubham7310&theme=dark&hide_border=true" alt="GitHub Streak" class="inline-block w-full sm:w-auto mb-4"/>
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shubham7310&layout=compact&theme=dark&hide_border=true" alt="Top Languages" class="inline-block w-full sm:w-auto"/>
            </p>

            <p class="text-xl font-bold border-b border-[#30363d] pb-2 mt-6">&gt; 📫 `connect.sh`</p>
            <p class="mt-4">You can connect with me on:</p>
            <ul class="list-disc list-inside ml-4">
                <li><a href="https://www.linkedin.com/in/shubhamdarji" target="_blank" class="text-blue-400 hover:underline">LinkedIn</a></li>
                <li><a href="https://github.com/shubham7310" target="_blank" class="text-blue-400 hover:underline">GitHub</a></li>
                <!-- Add other links as needed -->
            </ul>
        </div>
    </div>
</body>
</html>

