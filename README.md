# Image Slider Project

A responsive and interactive image slider built with HTML, CSS, and JavaScript that allows users to navigate through a collection of images with smooth transitions.

## Features

- **Smooth Transitions**: Elegant sliding animation between images
- **Multiple Navigation Methods**:
  - Previous/Next buttons
  - Keyboard arrow keys
  - Dot indicators for direct access to specific slides
- **Fully Responsive**: Works on all screen sizes
- **Auto-generated Navigation**: Dots are created dynamically based on number of slides
- **Clean UI**: Modern and minimal design with hover effects

## Live Demo

Check out the live demo on [GitHub Pages](https://ahmadubaid061.github.io/image_slider/)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/image-slider.git
```

2. Navigate to the project directory:
```bash
cd image-slider
```

3. Open `index.html` in your browser or use a local server.

## Usage

- Click the left and right arrow buttons to navigate between images
- Use the left and right arrow keys on your keyboard for navigation
- Click on the dot indicators at the bottom to jump to a specific slide
- Replace the placeholder images with your own images by updating the `src` attributes in the HTML

## Customization

### Adding More Slides

Add additional slide elements in the HTML:
```html
<div class="slide">
  <img src="path-to-your-image.jpg" alt="Description" />
</div>
```

### Styling

Modify the CSS variables in the style section to customize colors, sizes, and transitions:
```css
:root {
  --slider-width: 80%;
  --slider-height: 70vh;
  --transition-speed: 1s;
  --primary-color: #333;
  --accent-color: #fff;
}
```

## File Structure

```
image-slider/
│
├── index.html          # Main HTML file
├── style.css           # seperate file for styling
├── script.js           # javascript file
├── README.md           # Project documentation
├── images/             # Directory for slider images (optional)
│   ├── img-1.jpg
│   ├── img-2.jpg
│   └── ...


## Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter) - email@example.com

Project Link: [https://github.com/your-username/image-slider](https://ahmadubaid061.github.io/image_slider/)
