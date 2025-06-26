# liberiolanding
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Liberio.ai - Intelligent Support for the AI-Driven Software Era</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    
    <!-- FullStory Analytics -->
    <script>
    window['_fs_host'] = 'fullstory.com';
    window['_fs_script'] = 'edge.fullstory.com/s/fs.js';
    window['_fs_org'] = 'o-23F6MN-na1';
    window['_fs_namespace'] = 'FS';
    !function(m,n,e,t,l,o,g,y){var s,f,a=function(h){
    return!(h in m)||(m.console&&m.console.log&&m.console.log('FullStory namespace conflict. Please set window["_fs_namespace"].'),!1)}(e)
    ;function p(b){var h,d=[];function j(){h&&(d.forEach((function(b){var d;try{d=b[h[0]]&&b[h[0]](h[1])}catch(h){return void(b[3]&&b[3](h))}
    d&&d.then?d.then(b[2],b[3]):b[2]&&b[2](d)})),d.length=0)}function r(b){return function(d){h||(h=[b,d],j())}}return b(r(0),r(1)),{
    then:function(b,h){return p((function(r,i){d.push([b,h,r,i]),j()}))}}}a&&(g=m[e]=function(){var b=function(b,d,j,r){function i(i,c){
    h(b,d,j,i,c,r)}r=r||2;var c,u=/Async$/;return u.test(b)?(b=b.replace(u,""),"function"==typeof Promise?new Promise(i):p(i)):h(b,d,j,c,c,r)}
    ;function h(h,d,j,r,i,c){return b._api?b._api(h,d,j,r,i,c):(b.q&&b.q.push([h,d,j,r,i,c]),null)}return b.q=[],b}(),y=function(b){function h(h){
    "function"==typeof h[4]&&h[4](new Error(b))}var d=g.q;if(d){for(var j=0;j<d.length;j++)h(d[j]);d.length=0,d.push=h}},function(){
    (o=n.createElement(t)).async=!0,o.crossOrigin="anonymous",o.src="https://"+l,o.onerror=function(){y("Error loading "+l)}
    ;var b=n.getElementsByTagName(t)[0];b&&b.parentNode?b.parentNode.insertBefore(o,b):n.head.appendChild(o)}(),function(){function b(){}
    function h(b,h,d){g(b,h,d,1)}function d(b,d,j){h("setProperties",{type:b,properties:d},j)}function j(b,h){d("user",b,h)}function r(b,h,d){j({
    uid:b},d),h&&j(h,d)}g.identify=r,g.setUserVars=j,g.identifyAccount=b,g.clearUserCookie=b,g.setVars=d,g.event=function(b,d,j){h("trackEvent",{
    name:b,properties:d},j)},g.anonymize=function(){r(!1)},g.shutdown=function(){h("shutdown")},g.restart=function(){h("restart")},
    g.log=function(b,d){h("log",{level:b,msg:d})},g.consent=function(b){h("setIdentity",{consent:!arguments.length||b})}}(),s="fetch",
    f="XMLHttpRequest",g._w={},g._w[f]=m[f],g._w[s]=m[s],m[s]&&(m[s]=function(){return g._w[s].apply(this,arguments)}),g._v="2.0.0")
    }(window,document,window._fs_namespace,"script",window._fs_script);
    </script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            box-shadow: 0 2px 20px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }
        
        .logo {
            font-size: 2rem;
            font-weight: bold;
            background: linear-gradient(45deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }
        
        .nav-links a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            transition: color 0.3s ease;
        }
        
        .nav-links a:hover {
            color: #667eea;
        }
        
        .cta-button {
            background: linear-gradient(45deg, #667eea, #764ba2);
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            cursor: pointer;
        }
        
        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(102, 126, 234, 0.3);
        }
        
        main {
            margin-top: 100px;
        }
        
        .hero {
            text-align: center;
            padding: 6rem 0;
            color: white;
        }
        
        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            animation: fadeInUp 1s ease;
        }
        
        .hero p {
            font-size: 1.3rem;
            margin-bottom: 2rem;
            opacity: 0.9;
            animation: fadeInUp 1s ease 0.3s both;
        }
        
        .hero .cta-button {
            font-size: 1.1rem;
            padding: 15px 30px;
            animation: fadeInUp 1s ease 0.6s both;
        }
        
        .section {
            background: white;
            margin: 2rem 0;
            padding: 4rem 0;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }
        
        .section h2 {
            font-size: 2.5rem;
            margin-bottom: 2rem;
            text-align: center;
            background: linear-gradient(45deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .problem-section {
            background: linear-gradient(135deg, #ff6b6b, #ee5a24);
            color: white;
        }
        
        .problem-section h2 {
            color: white;
            -webkit-text-fill-color: white;
        }
        
        .solution-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .feature-card {
            background: linear-gradient(135deg, #f8f9fa, #e9ecef);
            padding: 2rem;
            border-radius: 15px;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        
        .feature-icon {
            font-size: 3rem;
            color: #667eea;
            margin-bottom: 1rem;
        }
        
        .metrics {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .metric-card {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 2rem;
            border-radius: 15px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .metric-card::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(255, 255, 255, 0.1), transparent);
            animation: shine 3s infinite;
        }
        
        .metric-number {
            font-size: 3rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        
        .team-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .team-member {
            background: linear-gradient(135deg, #f8f9fa, #e9ecef);
            padding: 2rem;
            border-radius: 15px;
            text-align: center;
        }
        
        .team-member h3 {
            color: #667eea;
            margin-bottom: 0.5rem;
        }
        
        .team-member .role {
            color: #764ba2;
            font-weight: bold;
            margin-bottom: 1rem;
        }
        
        footer {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            text-align: center;
            padding: 2rem 0;
            margin-top: 4rem;
        }
        
        .contact-info {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 3rem 0;
            text-align: center;
            border-radius: 20px;
            margin: 2rem 0;
        }
        
        .contact-info h2 {
            color: white;
            -webkit-text-fill-color: white;
        }
        
        .email-link {
            color: white;
            text-decoration: none;
            font-size: 1.2rem;
            font-weight: bold;
            transition: opacity 0.3s ease;
        }
        
        .email-link:hover {
            opacity: 0.8;
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes shine {
            0% { transform: translateX(-100%) translateY(-100%) rotate(45deg); }
            100% { transform: translateX(100%) translateY(100%) rotate(45deg); }
        }
        
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .nav-links {
                display: none;
            }
            
            .team-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">Liberio.ai</div>
                <ul class="nav-links">
                    <li><a href="#problem">Problem</a></li>
                    <li><a href="#solution">Solution</a></li>
                    <li><a href="#team">Team</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
                <a href="#contact" class="cta-button">Get Started</a>
            </nav>
        </div>
    </header>

    <main>
        <section class="hero">
            <div class="container">
                <h1>Intelligent Support for the AI-Driven Software Era</h1>
                <p>Bridge the velocity gap between AI-accelerated development and Tier 3 support</p>
                <a href="#solution" class="cta-button">Discover Our Solution</a>
            </div>
        </section>

        <div class="container">
            <section id="problem" class="section problem-section">
                <h2>The Agentic Velocity Gap</h2>
                <p style="font-size: 1.1rem; text-align: center; max-width: 800px; margin: 0 auto;">
                    The AI revolution is supercharging product engineering and lower support tiers with unprecedented efficiency. 
                    However, this creates a critical imbalance where Tier 3 engineers become overwhelmed bottlenecks, 
                    drowning in machine-assisted velocity while operating at human speed.
                </p>
                <div style="text-align: center; margin-top: 2rem;">
                    <div style="display: inline-block; background: rgba(255, 255, 255, 0.1); padding: 1.5rem; border-radius: 10px;">
                        <i class="fas fa-exclamation-triangle" style="font-size: 2rem; margin-bottom: 1rem;"></i>
                        <div>Ballooning MTTR • Eroding Customer Satisfaction • Resource Drain</div>
                    </div>
                </div>
            </section>

            <section id="solution" class="section">
                <h2>Our AI-Powered Solution</h2>
                <p style="text-align: center; font-size: 1.1rem; margin-bottom: 3rem; max-width: 800px; margin-left: auto; margin-right: auto;">
                    Liberio.ai is an automated Technical Support Agent that empowers Tier 3 engineers to resolve production issues 
                    swiftly and effectively, deployed securely within your VPC.
                </p>
                
                <div class="solution-grid">
                    <div class="feature-card">
                        <div class="feature-icon">
                            <i class="fas fa-rocket"></i>
                        </div>
                        <h3>Minimize R&D Escalations</h3>
                        <p>Bring engineering intuition into T3 actions, resolving tickets that would previously escalate to R&D.</p>
                    </div>
                    
                    <div class="feature-card">
                        <div class="feature-icon">
                            <i class="fas fa-analytics"></i>
                        </div>
                        <h3>Enhanced R&D Handover</h3>
                        <p>Deliver pre-analyzed tickets enriched with cross-platform analytics, metrics, logs, and recordings.</p>
                    </div>
                    
                    <div class="feature-card">
                        <div class="feature-icon">
                            <i class="fas fa-graduation-cap"></i>
                        </div>
                        <h3>Empower Tier 2 Support</h3>
                        <p>Continuously enrich knowledge bases with new procedures from resolved issues.</p>
                    </div>
                </div>
            </section>

            <section class="section">
                <h2>Key Differentiator</h2>
                <div style="background: linear-gradient(135deg, #f8f9fa, #e9ecef); padding: 2rem; border-radius: 15px; text-align: center;">
                    <h3 style="color: #667eea; margin-bottom: 1rem;">Collaborative AI for Support</h3>
                    <p style="font-size: 1.1rem;">
                        While AI tools like Cursor and Devin excel at code creation, Liberio.ai complements them by focusing on 
                        production issue resolution at Tier 3. Our AI crafts engineer-intuitive tickets with rich diagnostic data, 
                        ensuring faster, more effective resolutions when issues escalate to R&D.
                    </p>
                </div>
            </section>

            <section class="section">
                <h2>Quantifiable ROI & Impact</h2>
                <div class="metrics">
                    <div class="metric-card">
                        <div class="metric-number">20%</div>
                        <div>Reduction in R&D diagnostic time with enriched tickets</div>
                    </div>
                    
                    <div class="metric-card">
                        <div class="metric-number">25%</div>
                        <div>Reduction in T2 to T3 escalations through knowledge enrichment</div>
                    </div>
                    
                    <div class="metric-card">
                        <div class="metric-number">15%</div>
                        <div>Reduction in T3 to R&D escalations, saving resources</div>
                    </div>
                    
                    <div class="metric-card">
                        <div class="metric-number">15-25%</div>
                        <div>Overall MTTR reduction, boosting customer satisfaction</div>
                    </div>
                </div>
            </section>

            <section id="team" class="section">
                <h2>The Team</h2>
                <div class="team-grid">
                    <div class="team-member">
                        <h3>Ori Reshef</h3>
                        <div class="role">CEO</div>
                        <p>
                            Seasoned B2B leader with extensive R&D management experience and full product lifecycle expertise. 
                            Spearheaded innovative initiatives for NICE and SAP, drove growth at LivePerson, Clicktale, TaKaDu, 
                            and Varada as VP Product and Chief Solutions Officer.
                        </p>
                    </div>
                    
                    <div class="team-member">
                        <h3>Tal Ben-Moshe</h3>
                        <div class="role">CTO</div>
                        <p>
                            Over 20 years of deep tech leadership. Co-founded Varada (acquired by Starburst) and served as 
                            Chief Software Architect at Dell EMC XtremIO. Led development of innovative data infrastructure 
                            solutions with profound impact on cutting-edge technologies.
                        </p>
                    </div>
                </div>
            </section>

            <section id="contact" class="contact-info">
                <h2>Ready to Bridge the Velocity Gap?</h2>
                <p style="font-size: 1.2rem; margin-bottom: 1rem;">
                    Transform your Tier 3 support with AI-powered efficiency
                </p>
                <a href="mailto:info@liberio.ai" class="email-link">
                    <i class="fas fa-envelope"></i> info@liberio.ai
                </a>
            </section>
        </div>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Liberio.ai. All rights reserved. | Intelligent Support for the AI-Driven Software Era</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add scroll effect to header
        window.addEventListener('scroll', () => {
            const header = document.querySelector('header');
            if (window.scrollY > 100) {
                header.style.background = 'rgba(255, 255, 255, 0.98)';
            } else {
                header.style.background = 'rgba(255, 255, 255, 0.95)';
            }
        });

        // Animate metric numbers on scroll
        const observerOptions = {
            threshold: 0.7,
            rootMargin: '0px 0px -100px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    const number = entry.target.querySelector('.metric-number');
                    if (number && !number.classList.contains('animated')) {
                        number.classList.add('animated');
                        const finalNumber = number.textContent;
                        number.textContent = '0';
                        
                        const increment = finalNumber.includes('%') 
                            ? parseInt(finalNumber) / 20 
                            : parseInt(finalNumber.split('-')[0]) / 20;
                        
                        let current = 0;
                        const timer = setInterval(() => {
                            current += increment;
                            if (current >= parseInt(finalNumber)) {
                                number.textContent = finalNumber;
                                clearInterval(timer);
                            } else {
                                number.textContent = Math.floor(current) + (finalNumber.includes('%') ? '%' : '');
                            }
                        }, 50);
                    }
                }
            });
        }, observerOptions);

        document.querySelectorAll('.metric-card').forEach(card => {
            observer.observe(card);
        });
    </script>
</body>
</html>
