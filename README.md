### Snowball Rabbit
> Blockchain || Fullstack Web Development
---

<svg xmlns="http://www.w3.org/2000/svg" width="300" height="405" viewBox="0 0 300 405" fill="none" role="img"
    aria-labelledby="descId">
    <script xmlns="" />
    <title id="titleId"/>
        <desc id="descId"/>
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #2f80ed;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          @supports(-moz-appearance: auto) {
            /* Selector detects Firefox */
            .header { font-size: 15.5px; }
          }
          
    @keyframes slideInAnimation {
      from {
        width: 0;
      }
      to {
        width: calc(100%-100px);
      }
    }
    @keyframes growWidthAnimation {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }
    .lang-name {
      font: 400 11px "Segoe UI", Ubuntu, Sans-Serif;
      fill: #434d58;
    }
    .stagger {
      opacity: 0;
      animation: fadeInAnimation 0.3s ease-in-out forwards;
    }
    #rect-mask rect{
      animation: slideInAnimation 1s ease-in-out forwards;
    }
    .lang-progress{
      animation: growWidthAnimation 0.6s ease-in-out forwards;
    }
    

          
    /* Animations */
    @keyframes scaleInAnimation {
      from {
        transform: translate(-5px, 5px) scale(0);
      }
      to {
        transform: translate(-5px, 5px) scale(1);
      }
    }
    @keyframes fadeInAnimation {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }
  
          
    </style>

    <rect data-testid="card-bg" x="0.5" y="0.5" rx="4.5" height="99%" stroke="#e4e2e2" width="299" fill="#fffefe" stroke-opacity="1"/>

    <g data-testid="card-title" transform="translate(25, 35)">
        <g transform="translate(0, 0)">
            <text x="0" y="0" class="header" data-testid="header">Most Used Languages</text>
        </g>
    </g>
    
    <g data-testid="main-card-body" transform="translate(0, 55)">
        <svg data-testid="lang-items" x="25">
            <g transform="translate(0, 0)">
        <g class="stagger" style="animation-delay: 450ms">
            <text data-testid="lang-name" x="2" y="15" class="lang-name">Golang</text>
            <text x="215" y="34" class="lang-name">95%</text>
            <svg width="205" x="0" y="25">
                <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"/>
                <svg data-testid="lang-progress" width="95%">
                    <rect height="8" fill="#00ADD8" rx="5" ry="5" x="0" y="0" class="lang-progress" style="animation-delay: 750ms;"/>
                </svg>
            </svg>
        </g>
    </g>
    <g transform="translate(0, 40)">
        <g class="stagger" style="animation-delay: 600ms">
            <text data-testid="lang-name" x="2" y="15" class="lang-name">TypeScript</text>
            <text x="215" y="34" class="lang-name">90%</text>
            <svg width="205" x="0" y="25">
                <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"/>
                <svg data-testid="lang-progress" width="90%">
                    <rect height="8" fill="#3178c6" rx="5" ry="5" x="0" y="0" class="lang-progress" style="animation-delay: 900ms;"/>
                </svg>
            </svg>
        </g>
    </g>
    <!-- <g transform="translate(0, 40)">
        <g class="stagger" style="animation-delay: 600ms">
            <text data-testid="lang-name" x="2" y="15" class="lang-name">C#</text>
            <text x="215" y="34" class="lang-name">23.62%</text>
            <svg width="205" x="0" y="25">
                <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"/>
                <svg data-testid="lang-progress" width="23.62%">
                    <rect height="8" fill="#178600" rx="5" ry="5" x="0" y="0" class="lang-progress" style="animation-delay: 900ms;"/>
                </svg>
            </svg>
        </g>
    </g> -->
    <g transform="translate(0, 80)">
        <g class="stagger" style="animation-delay: 750ms">
            <text data-testid="lang-name" x="2" y="15" class="lang-name">Solidity</text>
            <text x="215" y="34" class="lang-name">90%</text>
            <svg width="205" x="0" y="25">
                <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"/>
                <svg data-testid="lang-progress" width="90%">
                    <rect height="8" fill="#AA6746" rx="5" ry="5" x="0" y="0" class="lang-progress" style="animation-delay: 1050ms;"/>
                </svg>
            </svg>
        </g>
    </g>
    <g transform="translate(0, 120)">
        <g class="stagger" style="animation-delay: 900ms">
            <text data-testid="lang-name" x="2" y="15" class="lang-name">C++/C#</text>
            <text x="215" y="34" class="lang-name">90%</text>
            <svg width="205" x="0" y="25">
                <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"/>
                <svg data-testid="lang-progress" width="90%">
                    <rect height="8" fill="#6866fb" rx="5" ry="5" x="0" y="0" class="lang-progress" style="animation-delay: 1200ms;"/>
                </svg>
            </svg>
        </g>
    </g>
    <g transform="translate(0, 160)">
        <g class="stagger" style="animation-delay: 900ms">
            <text data-testid="lang-name" x="2" y="15" class="lang-name">Java</text>
            <text x="215" y="34" class="lang-name">85%</text>
            <svg width="205" x="0" y="25">
                <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"/>
                <svg data-testid="lang-progress" width="85%">
                    <rect height="8" fill="#b07219" rx="5" ry="5" x="0" y="0" class="lang-progress" style="animation-delay: 1200ms;"/>
                </svg>
            </svg>
        </g>
    </g>
    <g transform="translate(0, 200)">
        <g class="stagger" style="animation-delay: 900ms">
            <text data-testid="lang-name" x="2" y="15" class="lang-name">Python</text>
            <text x="215" y="34" class="lang-name">85%</text>
            <svg width="205" x="0" y="25">
                <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"/>
                <svg data-testid="lang-progress" width="85%">
                    <rect height="8" fill="#3572A5" rx="5" ry="5" x="0" y="0" class="lang-progress" style="animation-delay: 1200ms;"/>
                </svg>
            </svg>
        </g>
    </g>
    <g transform="translate(0, 240)">
        <g class="stagger" style="animation-delay: 900ms">
            <text data-testid="lang-name" x="2" y="15" class="lang-name">PHP</text>
            <text x="215" y="34" class="lang-name">80%</text>
            <svg width="205" x="0" y="25">
                <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"/>
                <svg data-testid="lang-progress" width="80%">
                    <rect height="8" fill="#4F5D95" rx="5" ry="5" x="0" y="0" class="lang-progress" style="animation-delay: 1200ms;"/>
                </svg>
            </svg>
        </g>
    </g>
    <g transform="translate(0, 280)">
        <g class="stagger" style="animation-delay: 1050ms">
            <text data-testid="lang-name" x="2" y="15" class="lang-name">HTML</text>
            <text x="215" y="34" class="lang-name">100%</text>
            
            <svg width="205" x="0" y="25">
                <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"/>
                <svg data-testid="lang-progress" width="100%">
                    <rect height="8" fill="#e34c26" rx="5" ry="5" x="0" y="0" class="lang-progress" style="animation-delay: 1350ms;"/>
                </svg>
            </svg>
        </g>
    </g>
</svg>
</g>
</svg>

- ⛳ I'm from Canada
- 🔨 I’m currently working as a developer of [Deamtest Team](https://deamtest.com)
- 💻 I'm currently in love with Golang, Blockchain and Typescript
- 💬 Telegram [telegram](https://t.me/rabbit0516)
- 📨 Skype [skype](live:.cid.ec35550a867087a4)
- 📃 Linkedin: [https://linkedin.com/in/irinesh0516](https://www.linkedin.com/in/rabbit0516/)
- 📭 E-Mail: irina880011@gmail.com

<h1 align='center'><i>Stay awesome!</i></h1>

Thank you for your visiting my profile.

I am a passionate web developer who has been programming since grade school.
Having completed a bachelor's degree in computer science, I spent several years working for personal company, mostly developing web applications.
I am available to work full-time and to change my time zone to reach client goals. As well as this, I will maintain client trust.
It is not easy to maintain trust with clients to everyone, but I will try my best to maintain the relationship.

My abilities:

Web
* CSS3, HTML5, Bootstrap, MUI Tailwindcss
* React.js, Node.js, AngularJS, Vue.js, Nextjs
* PHP framework (Code Igniter, Laravel)
* Google Cloud functions, Firestore, firebase and cloud storage
* developing REST APIs with NodeJS and Express.
* modern ES5, ES6 standards
* Golang, JavaScript, TypeScript, C++, Rust, Solidity, Blockchain, Solidity, Solana
* MongoDB, MySQL, GraphQL, DynamoDB PostgreSQL

Mobile
* Frontend : React Native/Flutter for Android & iPhone & iPad
* Backend : Laravel/Django/Flask/Node/Firebase
* Software Architecture : C/C++/C#/Java/Python

Get your success with me. Looking forward to working with you!
