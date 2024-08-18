<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dua Fatima's GitHub Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: white;
            background-color: black;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color:black;
            box-shadow: 0 0 10px rgba(73, 209, 73, 0.562);
        }
        p{
            color: #91c153;
        }
        h1, h2 {
            color:#91c153;
            text-align: center;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            background-color:rgba(73, 209, 73, 0.562);
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
        a {
            color: rgb(10, 29, 10);
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }

        .marquee-container {
            width: 100%;
            overflow: hidden;
            white-space: nowrap;
            box-sizing: border-box;
            font-size: 3em;
            font-weight: 900;
            font-family: monospace;
            position: relative;
           
        }

        .marquee-text {
            display: inline-block;
            animation: typing 5s steps(30, end), blink-caret 0.75s step-end infinite;
          
            color: transparent;
            -webkit-text-stroke: 1px #91c153;
        }

        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }

        @keyframes blink-caret {
            from, to { border-color: transparent; }
            50% { border-color: black; }
        }


      
    </style>
</head>
<body>

<div class="container">
    <h1>👋 Assalam u Alaikum!

        <div class="marquee-container">
            <span class="marquee-text">I'm Dua Fatima</span>
        </div>


    <h2>📝 About Me</h2>
    <p>Assalam u Alaikum (Hi)!!</p>
    <p>I'm Dua Fatima, a passionate designer, developer, debater, and artist. I'm currently pursuing a Bachelor's in Computer Science from Virtual University while also learning GenAI, Metaverse, and Web 3.0 at the Governor Sindh Initiative. With a strong foundation in HTML, CSS, JavaScript, and TypeScript, I've built various projects like Amazon, LinkedIn, and Sidcup Family Golf website clones, integrating advanced tools like GSAP and ScrollTrigger. I'm deeply committed to continuous learning and applying my knowledge to create impactful digital experiences.
    </p>

    <p>Beyond technology, I am an accomplished debater, skilled content writer, and creative artist. My interests extend to crafting and design. With that, I'm also a mentor in the fields of IT, Islamic Studies, Urdu Adab, Art, and Computer.</p>

    <p>As a Freelancer, I work across multiple platforms. Currently, my primary focus is on expanding my expertise in IT and AI to contribute meaningfully to the forefront of technological innovation.</p>
    <h2>💼 My Projects</h2>
    <ul>
        <li><strong>Sidcup Family Golf Website Clone:</strong> A clone using HTML, CSS, JS animations, GSAP, and ScrollTrigger.</li>
        <li><strong>Amazon Website Clone:</strong> A clone project using HTML and CSS.</li>
        <li><strong>LinkedIn Website Clone:</strong> A clone project using HTML, CSS.</li>
        <li><strong>CLI Arithmetic Calculator:</strong> A command-line based calculator for performing arithmetic operations.</li>
        <li><strong>45 TypeScript Assignments:</strong> A comprehensive set of TypeScript assignments to sharpen programming skills.</li>
        <li><strong>CLI ATM Application:</strong> A command-line interface ATM simulation for practice.</li>
    </ul>

    <h2>🛠️ My Skills</h2>
    <ul>
        <li><strong>Programming Languages:</strong> HTML, CSS, JavaScript, TypeScript, C, SQL</li>
        <li><strong>Web Development:</strong> HTML, CSS, JS animations, GSAP, ScrollTrigger</li>
        <li><strong>Frameworks & Tools:</strong> Inquirer, Canva, Adobe Photoshop</li>
    </ul>

    <h2>🎓 Education</h2>
    <ul>
        <li><strong>Bachelor's in Computer Science:</strong> Virtual University (Ongoing)</li>
        <li><strong>Governor Sindh Initiative for AI, Metaverse, Web 3.0:</strong> Currently learning</li>
        <li><strong>Intermediate in Computer Science (ICS):</strong></li>
    </ul>

    <h2>🌟 Fun Facts</h2>
    <ul>
        <li>I run a YouTube channel named <a href="https://www.youtube.com/channel/UCeZpinT3OCDGkFZ4HBGlIQw">Coder's School</a> where I upload coding tutorials, MS Office, and MS Access content.</li>
        <li>I have a small painting business where I sell my artistic creations.</li>
    </ul>

    <h2>📫 How to Reach Me</h2>
    <ul>
        <li>Email: <a href="mailto:officialduafatima64648@gmail.com">officialduafatima64648@gmail.com</a></li>
        <li>LinkedIn: <a href="https://www.linkedin.com/in/dua-fatima-906208258/">Dua Fatima</a></li>
    </ul>
</div>



<script>
    const textElement = document.querySelector('.marquee-text');
    const text = textElement.textContent;
    const typingSpeed = 190; // Adjust typing speed here

    function typeText() {
        let index = 0;
        textElement.textContent = '';
        function step() {
            textElement.textContent = text.slice(0, index);
            index++;
            if (index <= text.length) {
                setTimeout(step, typingSpeed);
            } else {
                setTimeout(() => {
                    typeText(); // Restart typing effect
                }, typingSpeed * 2); // Delay before restart
            }
        }
        step();
    }

    typeText();
</script>

</body>
</html>
