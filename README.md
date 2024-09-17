# Hi! 👋
<style>
        body {
            background-color: #000;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        h1 {
            color: #00ff00;
            font-size: 48px;
            font-family: 'Courier New', Courier, monospace;
            position: relative;
            animation: glitch 2s infinite;
        }

        @keyframes glitch {
            0% {
                text-shadow: 2px 2px 0 #ff00ff, -2px -2px 0 #00ffff;
            }
            25% {
                text-shadow: -2px 2px 0 #ff00ff, 2px -2px 0 #00ffff;
            }
            50% {
                text-shadow: 2px -2px 0 #ff00ff, -2px 2px 0 #00ffff;
            }
            75% {
                text-shadow: -2px -2px 0 #ff00ff, 2px 2px 0 #00ffff;
            }
            100% {
                text-shadow: 2px 2px 0 #ff00ff, -2px -2px 0 #00ffff;
            }
        }

        h1::before {
            content: 'Hi! 👋';
            position: absolute;
            left: 0;
            top: 0;
            animation: glitchTop 2s infinite;
            clip: rect(0, 900px, 0, 0);
        }

        @keyframes glitchTop {
            0%, 100% {
                clip: rect(20px, 9999px, 25px, 0);
                transform: skew(0.5deg);
            }
            50% {
                clip: rect(85px, 9999px, 90px, 0);
                transform: skew(-0.5deg);
            }
        }

        h1::after {
            content: '<script>alert("SrPatoMan")</script>';
            position: absolute;
            left: 0;
            top: 0;
            animation: glitchBot 2s infinite;
            clip: rect(0, 900px, 0, 0);
        }

        @keyframes glitchBot {
            0%, 100% {
                clip: rect(85px, 9999px, 90px, 0);
                transform: skew(-0.5deg);
            }
            50% {
                clip: rect(20px, 9999px, 25px, 0);
                transform: skew(0.5deg);
            }
        }

    </style>


<a text-align="centre" href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Oswald&size=30&duration=4000&pause=1800&color=1AF71C&background=8EFFAD00&center=true&width=435&lines=%3Cscript%3Ealert(%22SrPatoMan%22)%3C%2Fscript%3E" alt="Typing SVG" /></a>

