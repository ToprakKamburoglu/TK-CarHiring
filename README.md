# TK CarHire - Personal Car Rental Website

## 📋 Project Overview

TK CarHire is a personal car rental website project developed to improve HTML, CSS, and JavaScript skills. This project features a modern, responsive design with interactive elements and showcases various car rental services.

## 🖼️ Website Screenshots

<!-- Image carousel showing different pages -->
<div align="center">
  
### 🏠 Homepage
![Homepage](images/anasayfa.png)
*Main landing page with navigation and hero section*

### 💰 Pricing Page
![Pricing](images/fiyatlar.png)
*Detailed pricing information for different vehicle categories*

### ℹ️ About Us Page
![About](images/hakkında.png)
*Information about our company and services*

### 🔧 Services Page
![Services](images/hizmetler.png)
*Complete list of our rental services and features*

### 📞 Contact Page
![Contact](images/iletişim.png)
*Contact form and location information*

### ⭐ Reviews Page
![Reviews](images/yorum.png)
*Customer testimonials and feedback*

</div>

---

### 📱 Page Navigation
| Page | Description | Screenshot |
|------|-------------|------------|
| **Home** | Main landing page with featured cars | [View](images/anasayfa.png) |
| **Pricing** | Rental rates and packages | [View](images/fiyatlar.png) |
| **About** | Company information and history | [View](images/hakkında.png) |
| **Services** | Available services and features | [View](images/hizmetler.png) |
| **Contact** | Get in touch with us | [View](images/iletişim.png) |
| **Reviews** | Customer experiences | [View](images/yorum.png) |

## 🚗 Features

- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional interface design
- **Interactive Navigation**: Smooth navigation between different sections
- **Car Gallery**: Showcase of available vehicles with high-quality images
- **Service Pages**: Detailed information about rental services
- **Contact Form**: Easy way for customers to get in touch
- **Image Carousel**: Interactive slideshow for displaying car images

## 📁 Project Structure

```
TK CarHire/
├── index.html          # Homepage
├── about.html          # About us page
├── hizmetler.html      # Services page
├── bilgi.html          # Information page
├── contact.html        # Contact page
├── style.css           # Main stylesheet
├── .DS_Store          # System file (macOS)
└── Car Images:
    ├── audi.jpg
    ├── corvette.jpg
    ├── ford.jpg
    ├── mercedes.jpg
    ├── rangerover.jpg
    ├── dealership.jpg
    ├── erkek.jpg
    └── kadın.jpg

images/ (Screenshots)
├── anasayfa.png        # Homepage screenshot
├── fiyatlar.png        # Pricing page screenshot
├── hakkında.png        # About page screenshot
├── hizmetler.png       # Services page screenshot
├── iletişim.png        # Contact page screenshot
└── yorum.png           # Reviews page screenshot
```

## 🎠 Interactive README Carousel

You can also create an interactive carousel for this README using GitHub Pages or any markdown viewer that supports HTML:

```html
<!-- Add this to your README.md for interactive carousel -->
<div style="position: relative; max-width: 800px; margin: 0 auto;">
  <div id="screenshot-carousel" style="position: relative; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.2);">
    
    <!-- Slide 1 -->
    <div class="slide active" style="display: block;">
      <img src="images/anasayfa.png" alt="Homepage" style="width: 100%; height: auto; display: block;">
      <div style="position: absolute; bottom: 0; left: 0; right: 0; background: linear-gradient(transparent, rgba(0,0,0,0.7)); color: white; padding: 20px; text-align: center;">
        <h3 style="margin: 0;">🏠 Homepage</h3>
        <p style="margin: 5px 0 0 0;">Main landing page with navigation and hero section</p>
      </div>
    </div>

    <!-- Slide 2 -->
    <div class="slide" style="display: none;">
      <img src="images/fiyatlar.png" alt="Pricing" style="width: 100%; height: auto; display: block;">
      <div style="position: absolute; bottom: 0; left: 0; right: 0; background: linear-gradient(transparent, rgba(0,0,0,0.7)); color: white; padding: 20px; text-align: center;">
        <h3 style="margin: 0;">💰 Pricing Page</h3>
        <p style="margin: 5px 0 0 0;">Detailed pricing information for different vehicle categories</p>
      </div>
    </div>

    <!-- Navigation buttons -->
    <button onclick="changeSlide(-1)" style="position: absolute; top: 50%; left: 15px; transform: translateY(-50%); background: rgba(0,0,0,0.5); color: white; border: none; padding: 15px 20px; cursor: pointer; border-radius: 5px; font-size: 16px;">❮</button>
    <button onclick="changeSlide(1)" style="position: absolute; top: 50%; right: 15px; transform: translateY(-50%); background: rgba(0,0,0,0.5); color: white; border: none; padding: 15px 20px; cursor: pointer; border-radius: 5px; font-size: 16px;">❯</button>

    <!-- Indicators -->
    <div style="text-align: center; padding: 15px; background: rgba(0,0,0,0.1);">
      <span onclick="currentSlide(1)" style="display: inline-block; width: 12px; height: 12px; background: #fff; border-radius: 50%; margin: 0 5px; cursor: pointer;"></span>
      <span onclick="currentSlide(2)" style="display: inline-block; width: 12px; height: 12px; background: rgba(255,255,255,0.5); border-radius: 50%; margin: 0 5px; cursor: pointer;"></span>
      <!-- Add more indicators for each page -->
    </div>
  </div>
</div>

<script>
let slideIndex = 0;
const slides = document.querySelectorAll('.slide');

function showSlide(n) {
  slides.forEach(slide => slide.style.display = 'none');
  slides[n].style.display = 'block';
}

function changeSlide(n) {
  slideIndex += n;
  if (slideIndex >= slides.length) slideIndex = 0;
  if (slideIndex < 0) slideIndex = slides.length - 1;
  showSlide(slideIndex);
}

function currentSlide(n) {
  slideIndex = n - 1;
  showSlide(slideIndex);
}

// Auto advance every 4 seconds
setInterval(() => changeSlide(1), 4000);
</script>
```

## 🛠️ Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling, animations, and responsive design
- **JavaScript**: Interactive functionality and carousel behavior
- **Responsive Design**: Mobile-first approach

## 📱 Responsive Features

- Flexible grid layout
- Mobile-optimized navigation
- Scalable images
- Touch-friendly carousel controls
- Adaptive font sizes

## 🎯 Learning Objectives

This project helps develop skills in:

- **HTML**: Semantic markup, form creation, page structure
- **CSS**: Flexbox, Grid, animations, responsive design
- **JavaScript**: DOM manipulation, event handling, carousel functionality
- **Web Design**: User experience, visual hierarchy, color theory
- **Project Organization**: File structure, code organization

## 🚀 Getting Started

1. Clone or download the project files
2. Open `index.html` in your web browser
3. Navigate through different pages to explore features
4. Modify the code to experiment with different styles and functionality

## 📈 Future Enhancements

- [ ] Add booking system functionality
- [ ] Implement price calculator
- [ ] Add customer review system
- [ ] Include map integration for pickup locations
- [ ] Add vehicle availability checker
- [ ] Implement search and filter functionality

## 🤝 Contributing

This is a personal learning project, but suggestions and feedback are always welcome!

## 📄 License

This project is for educational purposes and personal skill development.

---

**Note**: This is a learning project focused on improving HTML, CSS, and JavaScript skills. The carousel feature enhances the visual appeal and provides hands-on experience with interactive web components.
