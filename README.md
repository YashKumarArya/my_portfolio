# 3D Model Scroll Experience

A scroll-based 3D website featuring the Silver Soldier and Starship models.

## Features

- **Section 1 (Hero)**: Silver Soldier model with smooth rotation
- **Section 2**: Starship model that appears as you scroll
- **Smooth scroll transitions**: Models move up/down based on scroll position
- **Responsive design**: Works on desktop and mobile devices
- **Loading screen**: Shows progress while models load

## How to Run

1. Open `index.html` in a modern web browser (Chrome, Firefox, Safari, Edge)
2. Scroll down to see the transition from Silver Soldier to Starship

### Using a Local Server (Recommended)

For better performance and to avoid CORS issues, run a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (http-server)
npx http-server -p 8000
```

Then open `http://localhost:8000` in your browser.

## Technologies Used

- **Three.js**: 3D rendering
- **GLTFLoader**: Loading 3D models
- **GSAP & ScrollTrigger**: Smooth scroll animations
- **Responsive CSS**: Modern styling

## Customization

You can customize the experience by modifying:

- Model positions: Edit the `position.set()` values
- Animation speed: Adjust the `scrub` value in ScrollTrigger
- Colors: Change the gradient colors in the CSS
- Camera angle: Modify `camera.position.z`
