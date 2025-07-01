# AR Shop - Virtual Furniture Store

Welcome to AR Shop! This is a really cool website where you can see furniture in 3D and place it in your room using Augmented Reality (AR). It's like trying furniture in your home before you buy it!

## What is AR Shop?

AR Shop is a virtual furniture store that lets you:
- Look at furniture in 3D on your computer or phone
- Use your phone's camera to place furniture in your real room
- See how furniture looks in your space before buying it
- Browse different types of furniture like chairs, tables, and more

## How to Use AR Shop

### On Your Computer:
1. Open the `index.html` file in a web browser
2. You'll see the AR Shop homepage with furniture items
3. Click on any furniture piece to see it in 3D
4. Use your mouse to rotate and zoom the 3D models

### On Your Phone (AR Mode):
1. Open the website on your phone's web browser
2. Click the "AR" button when viewing a furniture piece
3. Allow the website to use your camera
4. Point your phone at the floor or a flat surface
5. Tap to place the furniture in your room
6. Walk around to see it from different angles!

## What You Need

### For Basic 3D Viewing:
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection to load the 3D models

### For AR Features:
- A smartphone with a camera
- Android phone with ARCore support OR iPhone with iOS 11+
- Chrome browser (works best for AR)

## Technical Stuff (Tech Stack)

This project is built using these cool technologies:

### Frontend (What You See):
- **HTML** - The structure of the website
- **CSS** - Makes everything look pretty
- **JavaScript** - Makes the website interactive
- **Bootstrap** - Helps make the website look good on phones and computers

### 3D Graphics:
- **Three.js** - A powerful library that creates 3D graphics in web browsers
- **WebXR** - Technology that makes AR work in web browsers
- **GLTF Models** - Special 3D file format for furniture models

### 3D Models and Assets:
- **GLB/GLTF files** - 3D furniture models (Furn1.glb, Furn2.glb, etc.)
- **HDR files** - Special lighting for realistic 3D scenes
- **JPEG images** - Preview pictures of furniture

### Libraries Used:
- **GLTFLoader** - Loads 3D furniture models
- **RGBELoader** - Loads realistic lighting
- **ARButton** - Creates the AR button
- **OrbitControls** - Lets you rotate 3D models with mouse

## File Structure

```
AR Shop/
├── index.html          - Main webpage
├── app.js             - Main JavaScript code
├── css/               - Styling files
├── assets/ar-shop/    - 3D models and images
├── libs/              - JavaScript libraries
└── vendor/            - External libraries (Bootstrap, jQuery)
```

## How to Set Up (For Developers)

1. Download all the files to your computer
2. Make sure all folders stay in the same structure
3. Open `index.html` in a web browser
4. If you want to test AR, you need to serve the files from a web server (not just open the file directly)

### Running a Local Server:
If you have Python installed:
```
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser

If you have Node.js installed:
```
npx http-server
```

## Cool Features

- **3D Product Viewer** - See furniture from all angles
- **AR Placement** - Put furniture in your real room
- **Responsive Design** - Works on phones, tablets, and computers
- **Multiple Furniture Items** - Browse different chairs and tables
- **Realistic Lighting** - Furniture looks realistic with proper shadows

## Supported Devices

### Desktop/Laptop:
- Windows, Mac, or Linux computer
- Any modern web browser

### Mobile (for AR):
- **Android**: Phones that support ARCore
- **iPhone**: iOS 11.0 or newer

## Troubleshooting

**AR button doesn't appear?**
- Make sure you're on a supported phone
- Try using Chrome browser
- Check if your phone supports AR

**3D models won't load?**
- Check your internet connection
- Make sure all files are in the right folders
- Try refreshing the page

**Website looks broken?**
- Make sure all CSS and JavaScript files are in the right place
- Check if you opened it from a web server (not just double-clicking the file)

## Future Ideas

- Add more furniture types
- Add color customization
- Add room templates
- Add shopping cart feature
- Add furniture measurements

---

Made with ❤️ using modern web technologies. Have fun exploring AR furniture!
