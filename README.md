<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vladyslav Finiak | Portfolio</title>
    <style>
        /* Base styles and color palette */
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --accent: #3b82f6;
            --accent-hover: #60a5fa;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
        }
        body {
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
        }
         /* Animated Container */
        .profile-card {
            background-color: var(--card-bg);
            max-width: 650px;
            padding: 40px;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            border: 1px solid rgba(255, 255, 255, 0.1);
             /* Entry Animation */
            opacity: 0;
            transform: translateY(30px);
            animation: fadeUp 1s ease-out forwards;
             /* Continuous floating animation */
            transition: transform 0.3s ease;
        }
        .profile-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.6);
        }
        /* Typography */
        h1 {
            margin: 0 0 10px 0;
            font-size: 2.2rem;
            color: var(--text-main);
        }
        .subtitle {
            font-size: 1.1rem;
            color: var(--accent);
            margin-bottom: 25px;
            font-weight: 500;
        }
        p, li {
            color: var(--text-muted);
            line-height: 1.6;
            font-size: 1rem;
        }
        /* Section Styling */
        .section-title {
            font-size: 1.2rem;
            margin: 25px 0 15px 0;
            color: var(--text-main);
            display: flex;
            align-items: center;
            gap: 10px;
        }
        ul {
            padding-left: 20px;
            margin-bottom: 25px;
        }
        /* Interactive Tech Stack Tags */
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }
        .tech-tag {
            background: rgba(59, 130, 246, 0.1);
            color: var(--accent);
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 600;
            border: 1px solid rgba(59, 130, 246, 0.2);
            cursor: default;
            transition: all 0.3s ease;
        }
        .tech-tag:hover {
            background: var(--accent);
            color: white;
            transform: scale(1.05);
            box-shadow: 0 4px 12px rgba(59, 130, 246, 0.4);
        }
        /* Keyframe Animations */
        @keyframes fadeUp {
            0% {
                opacity: 0;
                transform: translateY(30px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
    </head>
    <body>
    <div class="profile-card">
        <h1>Hi, I'm Vladyslav Finiak 👋</h1>
        <div class="subtitle">CS Student • Applied AI & Backend Systems</div>
        <p>Based in Warsaw, Poland. I am passionate about bridging academic foundations with industry standards, frequently supplementing my university studies with rigorous independent coursework to build scalable, production-ready tools.</p>
        <div class="section-title">🧠 Currently Exploring</div>
        <ul>
            <li><strong>Deep Learning:</strong> Implementing neural network architectures and mastering matrix calculus via Stanford's CS224n.</li>
            <li><strong>LLMs:</strong> Researching architecture and preparing for local model serving using vLLM and SGLang.</li>
        </ul>
        <div class="section-title">🛠️ Technical Arsenal</div>
        <div class="tech-stack">
            <span class="tech-tag">Python</span>
            <span class="tech-tag">PyTorch</span>
            <span class="tech-tag">NumPy & Pandas</span>
            <span class="tech-tag">Django & DRF</span>
            <span class="tech-tag">PostgreSQL</span>
            <span class="tech-tag">Docker</span>
            <span class="tech-tag">Linux</span>
            <span class="tech-tag">Streamlit</span>
        </div>
    </div>

</body>
</html>
<!--
**finyak4/finyak4** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
