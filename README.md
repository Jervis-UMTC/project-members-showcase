# Team Members Project

A modern, responsive team showcase website featuring elegant member cards with hover effects, social media links, and a call-to-action section.

## 🌟 Features

- **Responsive Design**: Adapts seamlessly to different screen sizes using CSS Grid
- **Modern UI**: Dark theme with purple gradient accents and glassmorphism effects
- **Interactive Elements**: Smooth hover animations and transitions
- **Team Member Cards**: Individual profiles with photos, roles, descriptions, and social links
- **Call-to-Action Section**: Recruitment section with animated button
- **Font Awesome Icons**: Social media icons from Font Awesome 7.0.0
- **Professional Typography**: System fonts for optimal readability

## 🎨 Design Highlights

- **Color Scheme**: Dark background (#1a1a1a) with purple gradients (#a78bfa to #8b5cf6)
- **Card Design**: Elevated cards with rounded corners and subtle shadows
- **Hover Effects**: Cards lift up on hover with smooth transitions
- **Profile Images**: Circular profile pictures with gradient headers
- **Social Links**: Icon buttons with hover scaling and color changes

## 📁 Project Structure

```
project/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
└── README.md          # Project documentation
```

## 🚀 Getting Started

1. **Clone or Download** the project files
2. **Open `index.html`** in your web browser
3. **Customize** the team member information as needed

## 🛠️ Customization

### Adding New Team Members

To add a new team member, copy the member div structure in `index.html`:

```html
<div class="member">
  <div class="top">
    <img src="profile-image-url" alt="">
  </div>
  <div class="member-details">
    <h3>Member Name</h3>
    <p>Job Title</p>
  </div>
  <div class="member-info">
    <p>Brief description of the team member's role and expertise.</p>
  </div>
  <div class="social-links">
    <!-- Add social media links here -->
  </div>
</div>
```

### Changing Colors

Update the CSS variables in `styles.css`:

```css
:root {
  --primary-color: #a78bfa;      /* Main purple color */
  --primary-dark: #8b5cf6;       /* Darker purple */
  --primary-light: #c4b5fd;      /* Lighter purple */
  --bg-dark: #1a1a1a;            /* Background color */
  --card-bg: #252525;            /* Card background */
}
```

### Profile Images

- Current images use placeholder URLs from randomuser.me
- Replace with actual team member photos
- Recommended size: 100x100px (images are automatically cropped to circles)

## 📱 Responsive Breakpoints

- **Desktop**: Grid layout with multiple columns
- **Tablet**: Adjusted grid with fewer columns
- **Mobile** (< 789px): Single column layout with reduced animations

## 🔗 Dependencies

- **Font Awesome 7.0.0**: Icons for social media links
- **System Fonts**: No external font dependencies

## 🌐 Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS Grid and Flexbox support required
- CSS custom properties (variables) support required

## 📝 Content Guidelines

### Team Member Information

Each team member card includes:
- **Profile Photo**: Professional headshot (100x100px recommended)
- **Name**: Full name of the team member
- **Job Title**: Current role or position
- **Description**: Brief bio highlighting expertise and experience
- **Social Links**: Professional social media profiles

### Social Media Icons

Supported social platforms (with Font Awesome icons):
- LinkedIn (`fab fa-linkedin`)
- Twitter/X (`fab fa-twitter`)
- GitHub (`fab fa-github`)
- Facebook (`fab fa-facebook`)
- Instagram (`fab fa-instagram`)
- Stack Overflow (`fab fa-stack-overflow`)
- Medium (`fab fa-medium`)
- Email (`far fa-envelope`)

## 🎯 Use Cases

Perfect for:
- Company "About Us" pages
- Agency team showcases
- Startup team introductions
- Department staff pages
- Project contributor lists
- Speaker lineup pages

## 🔧 Technical Details

- **HTML5**: Semantic markup with proper accessibility
- **CSS3**: Modern features including Grid, Flexbox, and custom properties
- **No JavaScript**: Pure CSS animations and interactions
- **Performance**: Lightweight with minimal external dependencies

## 📄 License

This project is open source. Feel free to use, modify, and distribute as needed.

## 🤝 Contributing

1. Fork the project
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

---

*Built with modern web standards and attention to user experience.*
