# Portfolio Project Structure

## 📁 Directory Structure

```
portfolio/
├── 📄 index.html              # Main portfolio website
├── 📄 resume.html             # Glassmorphism resume page
├── 📄 README.md               # Project documentation
├── 📄 .gitignore              # Git ignore rules
├── 📄 favicon.png             # Website favicon
│
├── 📁 css/                    # Stylesheets
│   ├── 📄 main.css            # Main glassmorphism styles
│   ├── 📄 base.css            # Base styles and resets
│   ├── 📄 vendor.css          # Third-party library styles
│   ├── 📄 fonts.css           # Font loading definitions
│   └── 📁 font-awesome/       # FontAwesome icon fonts
│       ├── 📁 css/
│       │   ├── 📄 font-awesome.css
│       │   └── 📄 font-awesome.min.css
│       └── 📁 fonts/
│           └── 📄 fontawesome-webfont.woff
│
├── 📁 js/                     # JavaScript files
│   ├── 📄 main.js             # Main application logic & animations
│   ├── 📄 plugins.js          # jQuery plugins (FitVids, Placeholder)
│   ├── 📄 modernizr.js        # Feature detection
│   ├── 📄 pace.min.js         # Page loading progress
│   └── 📄 jquery-2.1.3.min.js # jQuery library
│
├── 📁 fonts/                  # Custom web fonts
│   ├── 📁 lora/               # Lora serif font family
│   │   ├── 📄 *.woff          # Modern font formats only
│   │   └── 📄 stylesheet.css
│   └── 📁 poppins/            # Poppins sans-serif family
│       ├── 📄 *.woff/*.woff2  # Modern font formats only
│       └── 📄 stylesheet.css
│
└── 📁 images/                 # Image assets
    ├── 📄 profile-pic.jpg     # Profile picture
    ├── 📄 rag.png             # RAG Chatbot project thumbnail
    ├── 📄 rag2.png            # RAG Chatbot modal image
    ├── 📄 n8n.png             # Code Review Bot thumbnail
    ├── 📄 n8n2.png            # Code Review Bot modal image
    ├── 📄 agent.jfif          # AWS Bedrock project thumbnail
    └── 📄 agent2.png          # AWS Bedrock modal image
```

## 🎨 Design Features

### Glassmorphism UI
- **Animated gradient backgrounds** with continuous color shifts
- **Frosted glass cards** with backdrop-filter blur effects
- **Semi-transparent overlays** with subtle border highlights
- **Golden accent colors** (#ffd700) for consistency
- **Smooth hover animations** and transitions

### Modern Technologies
- **CSS3 Animations** for gradient shifts and floating elements
- **Backdrop Filter** for true glassmorphism effects
- **FontAwesome Icons** for consistent iconography
- **Responsive Design** with mobile-first approach
- **Performance Optimized** with lazy loading and modern formats

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 320px - 767px

## 🚀 Performance Optimizations

1. **Font Optimization**: Removed legacy formats (eot, svg, ttf)
2. **Image Optimization**: Lazy loading implemented
3. **CSS Minification**: Vendor prefixes optimized
4. **JavaScript**: Efficient counter animations and smooth scrolling

## 📄 Page Structure

### index.html
- **Header**: Glassmorphism navigation with blur effects
- **Intro**: Animated hero section with social links
- **About**: Professional summary with skills showcase
- **Experience**: Current role at Applaud Solutions
- **Resume**: Education and certifications timeline
- **Portfolio**: Featured projects with modal previews
- **Stats**: Animated counters with meaningful metrics
- **Contact**: Working contact form with glassmorphism styling

### resume.html
- **Modern Layout**: Professional timeline design
- **Print Optimized**: CSS for PDF generation
- **Interactive Elements**: Hover effects and animations
- **Mobile Responsive**: Adapts to all screen sizes

## 🔧 Build Process

No build process required - this is a static website using:
- Vanilla HTML5, CSS3, and JavaScript
- jQuery for DOM manipulation and animations
- FontAwesome for icons
- Custom fonts for typography

## 📦 Dependencies

- **jQuery 2.1.3**: DOM manipulation and animations
- **FontAwesome 4.x**: Icon fonts
- **Modernizr**: Feature detection
- **Pace.js**: Loading progress indication

## 🎯 Browser Support

- **Chrome/Edge**: Full support including backdrop-filter
- **Firefox**: Full support with fallbacks
- **Safari**: Full support including webkit-backdrop-filter
- **Mobile**: iOS Safari, Chrome Mobile, Samsung Internet

## 📈 SEO Features

- **Structured Data**: JSON-LD schema for person/professional
- **Open Graph Tags**: Social media optimization
- **Twitter Cards**: Rich previews for Twitter
- **Meta Tags**: Comprehensive SEO metadata
- **Semantic HTML**: Proper heading hierarchy and landmarks
