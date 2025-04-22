# AI Image Recognition App

A modern web application that uses TensorFlow.js and MobileNet to perform real-time image recognition directly in the browser. Built with React, TypeScript, and Tailwind CSS.

![App Screenshot](https://images.unsplash.com/photo-1517849845537-4d257902454a?q=80&w=800)

## Features

- 🤖 Real-time image classification using TensorFlow.js
- 📱 Mobile-friendly responsive design
- 🎨 Modern UI with Tailwind CSS
- 📷 Support for image upload
- 🔄 Demo image functionality
- ⚡ Fast performance with Vite
- 💪 Type safety with TypeScript

## Live Demo

Check out the live demo: [AI Image Recognition App](https://sweet-kangaroo-682f44.netlify.app)

## Technologies Used

- React 18
- TypeScript
- TensorFlow.js
- MobileNet Model
- Tailwind CSS
- Vite
- Lucide React Icons

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-image-recognition.git
cd ai-image-recognition
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:5173`

### Building for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` directory.

## How It Works

1. The application loads the MobileNet model using TensorFlow.js when the page loads
2. Users can either upload their own image or use the demo image
3. The AI model processes the image and returns predictions
4. Results are displayed showing the predicted objects and confidence levels

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [TensorFlow.js](https://www.tensorflow.org/js) for the machine learning capabilities
- [MobileNet Model](https://github.com/tensorflow/tfjs-models/tree/master/mobilenet) for image classification
- [Tailwind CSS](https://tailwindcss.com/) for the styling
- [Lucide React](https://lucide.dev/) for the icons
