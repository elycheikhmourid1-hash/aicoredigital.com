# aicoredigital.com
Official platform for AI Core Digital - driving global equilibrium through accessible, ethical AI solutions and transformative digital <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ely Cheikh Mourid - AI Data Evaluator & Consultant</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: Arial, sans-serif; line-height: 1.6; background: #0a0a0a; color: white; }
        
        /* Hero Section */
        .hero { 
            text-align: center; 
            padding: 80px 20px; 
            background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
        }
        .profile-img { 
            width: 180px; 
            height: 180px; 
            border-radius: 50%; 
            border: 4px solid #3a86ff;
            object-fit: cover;
            margin: 20px auto;
        }
        
        /* Buttons */
        .btn {
            display: inline-block;
            background: #3a86ff;
            color: white;
            padding: 12px 30px;
            margin: 15px 10px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }
        .btn:hover { background: #2667cc; transform: translateY(-3px); }
        
        /* Sections */
        .section { padding: 60px 20px; max-width: 1000px; margin: 0 auto; }
        .services { background: #1a1a1a; }
        
        /* Service Boxes */
        .service-box {
            background: #2d2d2d;
            padding: 25px;
            border-radius: 10px;
            margin: 20px;
            border-left: 4px solid #3a86ff;
        }
        
        /* Contact Form */
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            background: #2d2d2d;
            border: 1px solid #444;
            color: white;
            border-radius: 5px;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .hero { padding: 50px 15px; }
            .section { padding: 40px 15px; }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <div class="hero">
        <h1>Ely Cheikh Mourid</h1>
        <h2>AI Data Evaluator & Military Strategy Consultant</h2>
        
        <img src="https://i.ibb.co/Vc1y0mjc/IMG-5907.png" 
             alt="Ely Cheikh Mourid" 
             class="profile-img"
             onerror="this.src='https://via.placeholder.com/180'">
        
        <p>Former Military Lieutenant turned AI Data Specialist<br>
        Delivering high-quality data annotation and AI training solutions</p>
        
        <div>
            <a href="#contact" class="btn">Hire Me Now</a>
            <a href="https://www.linkedin.com/in/ely-cheikh-mourid" class="btn" target="_blank">LinkedIn</a>
            <a href="https://www.upwork.com/freelancers/~01..." class="btn" target="_blank">Upwork Profile</a>
        </div>
    </div>

    <!-- Services Section -->
    <div class="section services">
        <h2 style="text-align: center; margin-bottom: 40px;">My Services</h2>
        
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px;">
            <div class="service-box">
                <h3>🤖 AI Data Evaluation</h3>
                <p>Professional data annotation, labeling, and quality assessment for AI/ML training datasets.</p>
                <p><strong>Tools:</strong> Google Sheets, Hubstaff, Outlier Platform</p>
            </div>
            
            <div class="service-box">
                <h3>⚡ Quick E-commerce Setup</h3>
                <p>Shopify store development and digital product management for fast-track sales.</p>
                <p><strong>Platforms:</strong> Shopify, WooCommerce, Custom Solutions</p>
            </div>
            
            <div class="service-box">
                <h3>🎯 Strategic Consulting</h3>
                <p>Military operations analysis and security management consulting for tech companies.</p>
                <p><strong>Background:</strong> 1st Airborne Commando Paratrooper Battalion</p>
            </div>
        </div>
    </div>

    <!-- Contact Section -->
    <div class="section" id="contact">
        <h2 style="text-align: center; margin-bottom: 30px;">Get in Touch</h2>
        
        <div style="max-width: 600px; margin: 0 auto;">
            <!-- Simple Contact Form (using Formspree - FREE) -->
            <form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <input type="text" name="subject" placeholder="Subject" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit" class="btn" style="width: 100%;">Send Message</button>
            </form>
            
            <p style="text-align: center; margin-top: 40px; color: #aaa;">
                <strong>Direct Contact:</strong><br>
                📧 elycheikhmourid1@gmail.com<br>
                📞 804-485-3384<br>
                📍 Richmond, Virginia, USA
            </p>
        </div>
    </div>

    <!-- Footer -->
    <footer style="text-align: center; padding: 30px; background: #111; color: #777;">
        <p>© 2024 Ely Cheikh Mourid. All rights reserved.</p>
        <p style="margin-top: 10px;">
            <a href="https://aicoredigital.com" style="color: #3a86ff; margin: 0 10px;">Website</a> • 
            <a href="https://linkedin.com" style="color: #3a86ff; margin: 0 10px;">LinkedIn</a> • 
            <a href="https://outlier.ai" style="color: #3a86ff; margin: 0 10px;">Outlier</a>
        </p>
    </footer>

    <!-- Simple Script -->
    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
