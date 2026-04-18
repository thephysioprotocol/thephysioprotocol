<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    
    <meta property="og:title" content="The Physio Protocol | Premium Wellness & Rehab">
    <meta property="og:description" content="Elite in-home physiotherapy, fitness coaching, and nutrition. Online and In-person.">
    <meta property="og:image" content="https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?q=80&w=1000&auto=format">
    <meta property="og:type" content="website">

    <title>The Physio Protocol</title>
    <style>
        * { box-sizing: border-box; -webkit-tap-highlight-color: transparent; }
        body {
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            background-color: #eef5ec; 
            color: #1b4332; 
            margin: 0; padding: 0;
            line-height: 1.6;
            overflow-x: hidden;
        }
        .container { width: 92%; max-width: 1200px; margin: auto; padding: 60px 0; }
        
        /* Premium Animations */
        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: all 1.2s cubic-bezier(0.2, 1, 0.3, 1);
        }
        .reveal.active { opacity: 1; transform: translateY(0); }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 140px 20px;
            background: linear-gradient(rgba(27, 67, 50, 0.85), rgba(27, 67, 50, 0.85)), url('https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?q=80&w=1200&auto=format') center/cover no-repeat;
            color: #ffffff;
        }
        .hero h1 { font-size: 2.8em; margin-bottom: 20px; letter-spacing: 3px; text-transform: uppercase; font-weight: 700; }
        .hero p { font-size: 1.2em; max-width: 750px; margin: 0 auto; opacity: 0.9; font-weight: 300; letter-spacing: 0.5px; }

        /* Service Cards */
        .services-wrapper {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 40px;
            margin-top: 50px;
        }
        .service-card {
            background: #fff;
            border-radius: 16px;
            overflow: hidden;
            box-shadow: 0 20px 40px rgba(0,0,0,0.05);
            display: flex; flex-direction: column;
            min-height: 550px;
        }
        
        .collage-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            grid-template-rows: 140px 140px;
            gap: 2px;
            background: #fff;
        }
        .collage-grid img { width: 100%; height: 100%; object-fit: cover; filter: brightness(0.95); }
        .card-img { width: 100%; height: 282px; object-fit: cover; filter: brightness(0.95); }

        .card-content { padding: 35px 25px; flex-grow: 1; }
        .card-content h3 { 
            margin-top: 0; 
            font-size: 1.6em; 
            color: #1b4332; 
            border-bottom: 2px solid #eef5ec; 
            padding-bottom: 15px;
            margin-bottom: 20px;
        }
        .card-content ul { padding: 0; list-style: none; margin: 0; }
        .card-content li { margin-bottom: 12px; padding-left: 25px; position: relative; font-size: 1em; color: #444; }
        .card-content li::before { content: "•"; color: #f5a623; position: absolute; left: 0; font-weight: bold; font-size: 1.4em; top: -4px; }

        /* Contact Section */
        .footer { background: #1b4332; color: #fff; text-align: center; padding: 100px 20px; }
        .footer h2 { font-size: 2.2em; margin-bottom: 20px; letter-spacing: 1px; }
        .footer p { opacity: 0.8; max-width: 600px; margin: 0 auto 40px; font-weight: 300; }
        
        .btn-group { display: flex; flex-direction: column; gap: 18px; max-width: 360px; margin: 0 auto; }
        .btn {
            display: block;
            background: #f5a623; color: #fff; padding: 20px;
            text-decoration: none; border-radius: 50px; font-weight: 600;
            text-transform: uppercase; font-size: 0.85em; letter-spacing: 1.5px;
            transition: all 0.3s ease;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        .btn:active { transform: scale(0.97); }
        .btn-whatsapp { background: #25D366; }
        .btn-email { background: transparent; border: 2px solid #fff; }
    </style>
</head>
<body>

    <div class="hero reveal active">
        <div class="container" style="padding:0;">
            <h1>The Physio Protocol</h1>
            <p>We deliver elite professional wellness and clinical rehabilitation designed seamlessly around your lifestyle. Our bespoke services are available through <strong>premium in-home clinical visits</strong> as well as <strong>fully integrated online virtual care</strong> for clients globally.</p>
        </div>
    </div>

    <div class="container">
        <div class="services-wrapper">
            <div class="service-card reveal">
                <div class="collage-grid">
                    <img src="https://images.unsplash.com/photo-1579684385127-1ef15d508118?q=80&w=400&auto=format" alt="Physiotherapist">
                    <img src="https://images.unsplash.com/photo-1519823551278-64ac92734fb1?q=80&w=400&auto=format" alt="Manual Therapy">
                    <img src="https://images.unsplash.com/photo-1620916297397-a4a5402a3c6c?q=80&w=400&auto=format" alt="Dry Needling">
                    <img src="https://images.unsplash.com/photo-1576091160550-2173dba999ef?q=80&w=400&auto=format" alt="TENS Therapy">
                </div>
                <div class="card-content">
                    <h3>Physiotherapy & Rehab</h3>
                    <ul>
                        <li>Post-Operative Rehabilitation</li>
                        <li>Sports Injury Management</li>
                        <li>Manual Therapy & IASTM</li>
                        <li>Dry Needling & Cupping</li>
                        <li>Advanced TENS & Electrotherapy</li>
                        <li>Online Virtual Consultations</li>
                    </ul>
                </div>
            </div>

            <div class="service-card reveal">
                <img src="https://images.unsplash.com/photo-1534438327276-14e5300c3a48?q=80&w=600&auto=format" class="card-img" alt="Fitness Training">
                <div class="card-content">
                    <h3>Elite Fitness Training</h3>
                    <ul>
                        <li>Strength & Conditioning</li>
                        <li>Functional Mobility Training</li>
                        <li>Hypertrophy & Muscle Building</li>
                        <li>Animal Flow & Yoga Integration</li>
                        <li>Personalized Online Coaching</li>
                    </ul>
                </div>
            </div>

            <div class="service-card reveal">
                <img src="https://images.unsplash.com/photo-1490645935967-10de6ba17061?q=80&w=600&auto=format" class="card-img" alt="Nutrition">
                <div class="card-content">
                    <h3>Clinical Nutrition</h3>
                    <ul>
                        <li>Performance & Sports Nutrition</li>
                        <li>Hormonal & Metabolic Support</li>
                        <li>Anti-Inflammatory Protocols</li>
                        <li>Gut Health Optimization</li>
                        <li>Global Virtual Meal Planning</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

    <div class="footer reveal">
        <div class="container" style="padding:0;">
            <h2>Begin Your Wellness Journey</h2>
            <p>Connect with our expert team for a private consultation regarding our in-home or global online services.</p>
            
            <div class="btn-group">
                <a href="tel:+917981010248" class="btn">Speak with Us</a>
                
                <a href="https://wa.me/917981010248" class="btn btn-whatsapp">Message on WhatsApp</a>
                
                <a href="mailto:thephysioprotocol@gmail.com?subject=New%20Patient%20Enquiry&body=Hello%20Team,%0A%0ABooking%20for:%20(Self%20/%20Someone%20Else)%0A%0AService%20Interested%20in:%0A%0ABrief%20overview%20of%20goals:" class="btn btn-email">Send Email Enquiry</a>
            </div>
        </div>
    </div>

    <script>
        function reveal() {
            var reveals = document.querySelectorAll(".reveal");
            for (var i = 0; i < reveals.length; i++) {
                var windowHeight = window.innerHeight;
                var elementTop = reveals[i].getBoundingClientRect().top;
                if (elementTop < windowHeight - 50) { 
                    reveals[i].classList.add("active"); 
                }
            }
        }
        window.addEventListener("scroll", reveal);
        window.addEventListener("load", reveal);
        reveal();
    </script>
</body>
</html>
