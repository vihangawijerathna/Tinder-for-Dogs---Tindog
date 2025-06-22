# TinDog - Tinder for Dogs 🐕

A responsive landing page for TinDog, a fictional dating app for dogs. This project showcases modern web development techniques using Bootstrap and custom CSS animations.

## 📋 Project Overview

TinDog is a fun, modern landing page that mimics a dating app interface but for dogs. The website features a gradient background, responsive design, and smooth animations to create an engaging user experience.

## 🚀 Features

- **Responsive Design**: Mobile-first approach using Bootstrap 5
- **Animated Gradient Background**: Eye-catching animated gradient that cycles through colors
- **Modern UI Components**: Cards, buttons, and icons from Bootstrap
- **Multiple Sections**:
  - Hero section with app download buttons
  - Features showcase with icons
  - Customer testimonials
  - Pricing plans
  - Footer with navigation links

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with animations
- **Bootstrap 5.3.3**: Responsive framework
- **Bootstrap Icons**: SVG icons for UI elements

## 📁 Project Structure

```
├── index.html          # Main landing page
├── solution.html       # Reference solution
├── css/
│   ├── style.css      # Custom styles
│   └── solution.css   # Solution styles
├── images/            # Image assets
│   ├── iphone.png
│   ├── dog-img.jpg
│   └── [company logos]
└── goal images/       # Design references
```

## 🎨 Key CSS Features

### Animated Gradient Background

```css
.gradient-background {
  background: linear-gradient(300deg, #00bfff, #ff4c68, #ef8172);
  background-size: 180% 180%;
  animation: gradient-animation 18s ease infinite;
}
```

### Icon Styling

```css
.icon-square {
  width: 3rem;
  height: 3rem;
  border-radius: 0.75rem;
}
```

## 🚀 Getting Started

1. **Clone the repository** or download the files
2. **Open `index.html`** in your web browser
3. **For development**: Use a live server for better development experience

### Using Live Server (VS Code)

The project is configured with Live Server settings in `.vscode/settings.json`:

```json
{
  "liveServer.settings.port": 5501
}
```

## 📱 Responsive Breakpoints

The design adapts to different screen sizes:

- **Mobile**: Single column layout
- **Tablet**: Adjusted spacing and layouts
- **Desktop**: Multi-column layouts with larger elements

## 🎯 Sections Breakdown

1. **Title Section**: Hero area with app description and download buttons
2. **Features Section**: Three-column layout showcasing app benefits
3. **Testimonial Section**: Customer review with company logos
4. **Pricing Section**: Three-tier pricing cards
5. **Footer Section**: Navigation links and copyright information

## 🔧 Customization

### Colors

The main color scheme uses:

- Primary gradient: `#00bfff` to `#ff4c68` to `#ef8172`
- Bootstrap's semantic colors for text and backgrounds

### Typography

- Uses Bootstrap's typography system
- Custom font weights and sizes for hierarchy

## 📸 Screenshots

The project includes goal images in the `goal images/` folder showing the intended design for each section.

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is for educational purposes. Feel free to use it as a learning resource or template for your own projects.

## 🙏 Acknowledgments

- Bootstrap team for the excellent framework
- Bootstrap Icons for the SVG icons
- Design inspiration from modern dating apps
