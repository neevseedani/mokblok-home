# MokBlok Website

A modern, responsive website for MokBlok with 4 main sections and password protection for exclusive content.

## Features

### 🏠 **Home Page**
- Welcome hero section with call-to-action buttons
- Feature cards showcasing all sections
- Modern gradient design and smooth animations

### 📖 **About Page**
- Company mission and values
- Professional layout with placeholder for company image
- Responsive grid design

### 👥 **Team Page**
- Team member profiles with avatars
- Professional bios and roles
- Hover effects and smooth transitions

### 🎨 **UI/UX Templates Page** *(Password Protected)*
- **Password: `testing123`**
- Template categories (Web Design, Mobile Apps)
- Download buttons for templates
- Professional template previews

### 📱 **Screenshot Library Page** *(Password Protected)*
- **Password: `testing123`**
- Filterable screenshot collection
- Categories: Web Design, Mobile Apps, Branding
- Responsive grid layout

## 🔐 Password Protection

The UI/UX Templates and Screenshot Library pages are protected with the password `testing123`. Once entered correctly, users remain authenticated for the session.

### Security Features:
- Session-based authentication
- Auto-logout after 30 minutes of inactivity
- Password validation with error feedback
- Secure session storage

## 🚀 Getting Started

1. **Clone or download** the project files
2. **Open `index.html`** in your web browser
3. **Navigate** between tabs using the navigation menu
4. **Enter password** `testing123` to access protected sections

## 📁 File Structure

```
mokblok-home/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This documentation
```

## 🎨 Design Features

- **Modern UI/UX**: Clean, professional design with gradients
- **Responsive Design**: Works on all device sizes
- **Smooth Animations**: CSS transitions and JavaScript animations
- **Interactive Elements**: Hover effects and loading states
- **Accessibility**: Keyboard navigation and screen reader friendly

## 🛠️ Technical Details

- **HTML5**: Semantic markup and modern structure
- **CSS3**: Flexbox, Grid, animations, and responsive design
- **Vanilla JavaScript**: No external dependencies
- **Session Storage**: Client-side authentication management
- **Cross-browser Compatible**: Works in all modern browsers

## 🔧 Customization

### Changing the Password
Edit the `correctPassword` variable in `script.js`:
```javascript
const correctPassword = 'your-new-password';
```

### Adding New Content
- Add new tabs in the HTML navigation
- Create corresponding tab content sections
- Update CSS for new elements
- Add JavaScript functionality as needed

### Styling Modifications
- Colors are defined in CSS variables
- Layout uses CSS Grid and Flexbox for easy modifications
- Responsive breakpoints are clearly defined

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Mobile Responsiveness

The website is fully responsive with:
- Mobile-first design approach
- Touch-friendly navigation
- Optimized layouts for small screens
- Responsive typography and spacing

## 🚀 Performance Features

- Optimized CSS animations
- Efficient JavaScript event handling
- Minimal DOM manipulation
- Session storage for authentication state

## 🔒 Security Notes

- Passwords are stored in plain text (for demo purposes)
- In production, implement proper server-side authentication
- Consider HTTPS for secure password transmission
- Add rate limiting for password attempts

## 📞 Support

For questions or customization requests, please refer to the code comments or modify the files as needed.

---

**MokBlok** - Your creative hub for design inspiration and collaboration
