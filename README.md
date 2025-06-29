# A5 Apartment - 360° Panoramic View

## 🏢 Project Overview

A5 is an interactive 360° panoramic virtual tour of an apartment located in Queen Towers, Erbil, Iraq. This project provides an immersive experience allowing users to explore the apartment's interior spaces through high-quality panoramic photography.

## 🌟 Features

- **Interactive 360° Panoramas**: Navigate through multiple rooms and spaces
- **Multiple Viewpoints**: Explore different angles and perspectives in each room
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Intuitive controls for panning, zooming, and scene switching
- **Auto-rotation**: Optional automatic rotation for hands-free viewing
- **Fullscreen Mode**: Immersive viewing experience

## 🏠 Available Spaces

The virtual tour includes the following areas:

1. Bathroom
2. Kitchen
3. Hall
4. Boulevard View
5. Bathroom 2
6. Room
7. Balcony
8. Master Bathroom
9. Master Room
10. Master Balcony

## 🛠️ Technology Stack

- **Marzipano**: 360° panorama viewer library
- **HTML5/CSS3**: Modern web standards
- **JavaScript**: Interactive functionality
- **Responsive Design**: Mobile-first approach

## 🚀 Live Demo

Visit the live demo: [A2 Apartment Virtual Tour](https://abdalkaderdev.github.io/A2/)

## 📱 How to Use

1. **Navigation**: Use mouse/touch to drag and explore the panorama
2. **Zoom**: Use scroll wheel or pinch gestures to zoom in/out
3. **Scene Switching**: Click on room names in the sidebar to switch between spaces
4. **Auto-rotation**: Toggle the play button for automatic rotation
5. **Fullscreen**: Click the fullscreen button for immersive viewing

## 🏗️ Project Structure

```
A5/
├── app-files/
│   ├── index.html          # Main application file
│   ├── index.js            # Application logic
│   ├── data.js             # Scene and panorama data
│   ├── style.css           # Styling and layout
│   ├── img/                # UI icons and images
│   ├── tiles/              # Panoramic image tiles
│   │   ├── 0-bathroom/     # Bathroom panorama tiles
│   │   ├── 1-kitchen/      # Kitchen panorama tiles
│   │   ├── 2-hall/         # Hall panorama tiles
│   │   ├── 3-boulevard-view/ # Boulevard view panorama tiles
│   │   ├── 4-bathroom-2/   # Second bathroom panorama tiles
│   │   ├── 5-room/         # Room panorama tiles
│   │   ├── 6-balcony/      # Balcony panorama tiles
│   │   ├── 7-master-bathroom/ # Master bathroom panorama tiles
│   │   ├── 8-master-room/  # Master room panorama tiles
│   │   └── 9-master-balcony/ # Master balcony panorama tiles
│   └── vendor/             # Third-party libraries
│       ├── marzipano.js    # Panorama viewer
│       ├── bowser.min.js   # Browser detection
│       └── screenfull.min.js # Fullscreen API
├── LICENSE.txt             # License file
└── README.txt              # Project documentation
```

## 📍 Location

**Queen Towers, Erbil, Iraq**

This virtual tour showcases an apartment in the prestigious Queen Towers development, offering a glimpse into modern living spaces in Erbil's vibrant cityscape. (Apartment number: A5)

## 🎯 Use Cases

- **Real Estate**: Virtual property tours for potential buyers/renters
- **Interior Design**: Showcase design and layout concepts
- **Marketing**: Interactive property presentations
- **Documentation**: Visual record of apartment features and condition

## 🔧 Development

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/Abdalkaderdev/A5.git
   cd A5
   ```

2. Open `app-files/index.html` in a web browser or serve locally:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve app-files
   ```

3. Visit `http://localhost:8000/app-files` in your browser

### Customization

- **Add New Scenes**: Modify `app-files/data.js` to include additional panoramic scenes
- **Update Images**: Replace tiles in the `app-files/tiles/` directory with new panoramic images
- **Styling**: Customize appearance by editing `app-files/style.css`

## 📄 License

This project is open source and available under the [MIT License](LICENSE.txt).

## 👨‍💻 Author

**Abdalkaderdev** - [GitHub Profile](https://github.com/Abdalkaderdev)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Contact

For questions or support, please open an issue on GitHub or contact the developer.

---

*Experience the future of virtual property tours with A5 Apartment's immersive 360° panoramic view.*
