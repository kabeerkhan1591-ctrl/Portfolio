Kabeer Khan - Front-End Developer Portfolio
A modern, responsive, and visually stunning portfolio website built with pure HTML, CSS, and JavaScript. This portfolio showcases my skills, education, and projects as a Front-End Web Developer.
________________________________________
🚀 Live Demo
View Portfolio
________________________________________
✨ Features
•	Fully Responsive - Works perfectly on desktop, tablet, and mobile
•	Modern Design - Dark theme with navy blue and electric blue accents
•	Smooth Animations - Scroll reveal animations, typing effect, hover effects
•	Single Page - All sections in one scrollable page
•	Fast Loading - No external CSS/JS files, everything is inline
•	SEO Friendly - Proper meta tags and semantic HTML structure
________________________________________
🛠️ Technologies Used
Technology	Purpose
HTML5	Semantic structure
CSS3	Styling, animations, responsive design
JavaScript	Interactivity, typing effect, scroll animations
Font Awesome	Icons
Google Fonts	Inter & JetBrains Mono typography
________________________________________
📁 Project Structure
portfolio/
├── index.html          # Main portfolio file (single file, self-contained)
├── README.md           # This file
└── image/
    ├── img3.JPG        # Profile photo
    └── terramax-preview.jpg  # Project screenshot
Note: This is a single-file portfolio. All CSS and JavaScript is embedded in index.html for fast loading and easy deployment.
________________________________________
📸 Portfolio Sections
Section	Description
Hero	Animated introduction with typing effect
About	Professional summary with stats
Education	Timeline of academic journey
Skills	Technical expertise with animated progress bars
Projects	Featured project with live demo links
Contact	Contact form and social links
________________________________________
🚀 Getting Started
Option 1: Direct Download
1.	Download index.html
2.	Open in any web browser
3.	Done!
Option 2: Clone & Customize
# Clone the repository
git clone https://github.com/kabeerkhan1591-ctrl/portfolio.git

# Navigate to folder
cd portfolio

# Open in browser
open index.html
Option 3: Deploy on GitHub Pages
1.	Fork this repository
2.	Go to Settings → Pages
3.	Select source: Deploy from a branch → main → / (root)
4.	Your portfolio will be live at https://yourusername.github.io/portfolio/
________________________________________
🎨 Customization Guide
Change Profile Photo
Replace image/img3.JPG with your own photo:
<div class="box">
    <img src="image/your-photo.jpg" alt="Your Name">
</div>
Add More Projects
Find the Projects section and add new project cards:
<div class="proj-card reveal">
    <div class="proj-img">
        <img src="image/project-screenshot.jpg" alt="Project Name">
        <div class="proj-over">
            <a href="live-demo-link"><i class="fas fa-external-link-alt"></i></a>
            <a href="github-link"><i class="fab fa-github"></i></a>
        </div>
    </div>
    <div class="proj-body">
        <h4>Project Name</h4>
        <p>Short description of the project.</p>
        <div class="proj-tech">
            <span>HTML5</span><span>CSS3</span><span>JavaScript</span>
        </div>
        <div class="proj-links">
            <a href="live-demo" class="btn btn-main"><i class="fas fa-eye"></i> Demo</a>
            <a href="github" class="btn btn-sec"><i class="fab fa-github"></i> Code</a>
        </div>
    </div>
</div>
Update Contact Information
Find the Contact section and update: - Email: kabeerkhan1591@gmail.com - WhatsApp: +92 330 2741348 - Instagram: @kbrx_.sn09
Change Colors
Edit CSS custom properties in the <style> section:
:root {
    --primary-bg: #050816;      /* Deep Navy Black */
    --secondary-bg: #0F172A;     /* Navy Blue */
    --accent: #2563EB;           /* Bright Blue */
    --accent-hover: #3B82F6;    /* Hover Blue */
    --text-primary: #FFFFFF;     /* White */
    --text-secondary: #94A3B8;  /* Gray */
}
________________________________________
📱 Responsive Breakpoints
Breakpoint	Target
1200px+	Large desktops
992px - 1199px	Medium desktops
768px - 991px	Tablets
576px - 767px	Mobile landscape
< 576px	Mobile portrait
________________________________________
🎯 Performance
•	No external CSS/JS files - Everything loads instantly
•	Minimal dependencies - Only Font Awesome & Google Fonts
•	Lightweight - Under 50KB total (excluding images)
•	Mobile-first - Optimized for all screen sizes
________________________________________
📄 License
This project is open source and available under the MIT License.
Feel free to use this portfolio template for your own projects. Just give credit by linking back or starring the repo! ⭐
________________________________________
👤 About Me
Kabeer Khan - Front-End Web Developer - HTML | CSS | JavaScript | Bootstrap | Responsive Design - 📧 kabeerkhan1591@gmail.com - 📱 +92 330 2741348 - 📷 @kbrx_.sn09
________________________________________
“Crafting pixel-perfect, responsive, and performant web experiences with modern technologies.”
