Basic HTML & CSS Layout 🎨💻
My first web development project - a fundamental HTML and CSS layout assignment showcasing semantic HTML structure and responsive design principles.

🎯 About This Project
This is my very first project in learning HTML and CSS! It represents the foundation of my web development journey, demonstrating core concepts like semantic HTML, CSS flexbox, and responsive design. The project creates a classic web layout with header, navigation, three-column content area, and footer.

✨ Features
Semantic HTML Structure
Proper use of HTML5 semantic elements
Clean, accessible markup
Well-organized content hierarchy


Responsive Three-Column Layout:
Flexible main content area
Left and right sidebars
CSS Flexbox implementation

Interactive Navigation:
Horizontal navigation bar
Hover effects with underline
Clean, centered design

Professional Styling:
Color scheme with red headers and sky blue content
Consistent typography using Arial font family
Rounded corners and borders for visual appeal
Proper spacing and padding throughout

🎨 Design Elements
Color Palette:
Primary Red: #f44336 (Header/Footer)
Accent Red: #FF204E (Navigation)
Sky Blue: skyblue (Content areas)
White: #ffffff (Text on red backgrounds)
Black: #000000 (Text on blue backgrounds)
Light Gray: #ccc (Borders)

Layout Structure:
┌─────────────────────────────────────┐
│              HEADER                 │
├─────────────────────────────────────┤
│         NAVIGATION BAR              │
├─────────┬─────────────┬─────────────┤
│  SIDE   │    MAIN     │    SIDE     │
│ CONTENT │   CONTENT   │   CONTENT   │
│  (LEFT) │             │   (RIGHT)   │
├─────────┴─────────────┴─────────────┤
│              FOOTER                 │
└─────────────────────────────────────┘
🚀 How to Run

Option 1: Direct File Opening
Download both index.html and styles.css files
Make sure both files are in the same folder
Double-click index.html to open in your browser

Option 2: Online IDEs (Great for Beginners)
CodePen: https://codepen.io/

Create new pen:
Copy HTML to HTML section
Copy CSS to CSS section
See live preview instantly

JSFiddle: https://jsfiddle.net/
Paste HTML in HTML panel
Paste CSS in CSS panel
Click "Run" to see results


Replit: https://replit.com/
Create new HTML/CSS/JS repl
Add files and code
Run to see live version



Option 3: Local Development Server
bash# Using Python (if installed)
python -m http.server 8000
# Then visit: http://localhost:8000
# Using Node.js live-server (if installed)
npx live-server

📁 File Structure
project-folder/
├── index.html          # Main HTML file
├── styles.css          # CSS stylesheet
└── README.md          # This documentation

🔧 Technical Implementation
HTML Features Used:
DOCTYPE declaration for HTML5
Semantic elements (<header>, <nav>, <main>, <section>, <footer>)
Proper meta tags for responsiveness
External CSS linking
Accessibility-friendly structure

CSS Features Used:
Flexbox Layout: For responsive three-column design
Box Model: Margin, padding, border management
Typography: Font families and text styling
Hover Effects: Interactive navigation elements
Color Management: Consistent color scheme
Responsive Design: Flexible layouts

🐛 Known Issues (Learning in Progress!)
As this was my first HTML/CSS project, there are some areas for improvement:
Incomplete CSS: The footer styling appears to be cut off (font-s)
Class Mismatch: HTML uses .side-column and .side-column2, but CSS targets .side-content
Extra Closing Tag: There's an extra </nav> tag in the HTML
Mobile Responsiveness: Could benefit from media queries for better mobile experience

These issues are preserved to show the authentic learning process!
🎓 What I Learned
HTML Fundamentals: Document structure, semantic elements, proper nesting
CSS Basics: Selectors, properties, values, and styling techniques
Layout Systems: Introduction to Flexbox for responsive design
Color Theory: Working with color schemes and contrast
Typography: Font selection and text styling
User Experience: Creating interactive elements with hover effects

💡 Key Concepts Demonstrated
Semantic HTML: Using appropriate HTML5 elements for meaning
CSS Selectors: Class selectors, element selectors, pseudo-classes
Flexbox: Modern layout technique for responsive design
Box Model: Understanding margins, borders, padding, and content
Cascading: How CSS rules are applied and inherited
Responsive Design: Creating layouts that work on different screen sizes

🔧 Quick Fixes
To make this code work perfectly, here are the needed adjustments:
Fix 1: Remove Extra Nav Tag
html<!-- Remove this extra closing tag -->
</nav>
Fix 2: Update CSS Class Names
css/* Change from .side-content to match HTML classes */
.side-column, .side-column2 {
    background-color: skyblue;
    padding: 20px;
    color: #000000;
    margin: 0 5px;
    text-align: center;
    border: 2px solid #ccc;
    border-radius: 10px;
}
Fix 3: Complete Footer Styling
cssfooter h5 {
    font-size: 1.2em;
    margin: 0;
}

🤝 Contributing
While this is a personal learning project, feel free to:
Fork and improve the design
Add responsive breakpoints
Enhance the color scheme
Create variations for learning purposes

📜 License
This project is open source and available under the MIT License.

🙏 Acknowledgments
Thanks to online HTML/CSS tutorials and documentation
Appreciation for the web development community's learning resources
Recognition to all beginner developers taking their first steps in web development

"Every expert was once a beginner. This layout represents the first step in my web development journey - from basic HTML structure to understanding CSS styling and layout principles."
📸 Expected Layout Preview
╔═══════════════════════════════════════╗
║               HEADER                  ║
╠═══════════════════════════════════════╣
║     About    Home    Contacts         ║
╠═══════════╦═══════════════╦═══════════╣
║   Side    ║     Main      ║   Side    ║
║  Content  ║    Content    ║  Content  ║
║  (Left)   ║               ║  (Right)  ║
╠═══════════╩═══════════════╩═══════════╣
║               FOOTER                  ║
╚═══════════════════════════════════════╝

Red header/footer, red navigation, blue content areas with the main content prominently displayed in the center.
