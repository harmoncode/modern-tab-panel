# Modern Tab Panel

An elegant tab panel component with radio button navigation and smooth transitions. Perfect for organizing content into logical sections with a clean, modern interface.

## ✨ Features

- **Radio Button Navigation**: Accessible tab switching with radio buttons
- **Smooth Transitions**: Beautiful animations between tab content
- **Responsive Design**: Works perfectly on all devices
- **Customizable**: Easy to customize colors, layout, and styling
- **Accessible**: Built with ARIA attributes and keyboard navigation
- **Lightweight**: Pure CSS and JavaScript, no dependencies
- **Multiple Styles**: Different tab styles and variations
- **Content Animation**: Smooth content transitions

## 🚀 Live Demo

[View on CodePen](https://codepen.io/harmoncode/pen/KwpKWXp)

## 📁 Files

- `index.html` - Main HTML structure
- `style.css` - All styling and animations
- `script.js` - JavaScript functionality

## 🛠️ Usage

### Basic Implementation

```html
<div class="tab-container">
    <div class="tab-navigation">
        <input type="radio" name="tabs" id="tab1" checked>
        <label for="tab1">Tab 1</label>
        
        <input type="radio" name="tabs" id="tab2">
        <label for="tab2">Tab 2</label>
        
        <input type="radio" name="tabs" id="tab3">
        <label for="tab3">Tab 3</label>
    </div>
    
    <div class="tab-content">
        <div class="tab-panel" id="panel1">
            <h3>Tab 1 Content</h3>
            <p>This is the content for tab 1.</p>
        </div>
        
        <div class="tab-panel" id="panel2">
            <h3>Tab 2 Content</h3>
            <p>This is the content for tab 2.</p>
        </div>
        
        <div class="tab-panel" id="panel3">
            <h3>Tab 3 Content</h3>
            <p>This is the content for tab 3.</p>
        </div>
    </div>
</div>
```

### JavaScript Enhancement

```javascript
// Initialize tab panel with additional features
const tabPanel = new TabPanel({
    container: '.tab-container',
    enableAnimation: true,
    enableKeyboard: true
});
```

## 🎨 Customization Options

- **Colors**: Customize tab colors, backgrounds, and borders
- **Layout**: Modify tab layout and positioning
- **Animations**: Adjust transition effects and timing
- **Typography**: Change fonts, sizes, and weights
- **Indicators**: Customize active tab indicators

## ⚙️ Configuration

```javascript
const config = {
    enableAnimation: true,   // Enable smooth transitions
    enableKeyboard: true,    // Enable keyboard navigation
    animationDuration: 300,  // Animation duration (ms)
    easing: 'ease-in-out',   // CSS easing function
    autoHeight: true,        // Auto-adjust content height
    showIndicator: true      // Show active tab indicator
};
```

## 📱 Browser Support

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- IE11+ ✅

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Created by

**HarmonCode** - [harmoncode.com](https://harmoncode.com)

---

⭐ If you find this useful, please give it a star! 