# 🎯 Hangman Game

A classic Hangman word guessing game built with **Vue.js 3** and **Vite**. Test your vocabulary skills by guessing hidden words before the hangman is complete!

## ✨ Features

- 🎮 **Interactive Gameplay**: Classic hangman mechanics with visual feedback
- 🖼️ **Visual Hangman**: Progressive hangman illustrations (0-6 stages)
- ⌨️ **Virtual Keyboard**: Clickable letter buttons for easy gameplay
- 💡 **Hint System**: Get helpful hints to guide your guesses
- 📱 **Responsive Design**: Works perfectly on both desktop and mobile devices
- 🎉 **Game States**: Victory and defeat animations with replay functionality
- 🎨 **Modern UI**: Clean, intuitive interface with smooth animations

## 🚀 Getting Started

### Prerequisites

- **Node.js**: Version 20.19.0 or higher (or 22.12.0+)
- **npm** or **yarn** package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd vue-project
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` (or the URL shown in your terminal)

### Build for Production

```bash
npm run build
npm run preview
```

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint with auto-fix
- `npm run format` - Format code with Prettier

## 🏗️ Project Structure

```
vue-project/
├── public/                 # Static assets
├── src/
│   ├── assets/
│   │   ├── images/        # Game images (hangman stages, victory/loss gifs)
│   │   └── main.css       # Global styles
│   ├── components/
│   │   └── Vc.vue         # Main game component
│   ├── App.vue            # Root component
│   └── main.js            # Application entry point
├── index.html              # HTML template
├── vite.config.js          # Vite configuration
└── package.json            # Dependencies and scripts
```

## 🎮 How to Play

1. **Start the Game**: The game begins automatically with a hidden word
2. **Guess Letters**: Click on letter buttons to make your guesses
3. **Watch the Hangman**: Incorrect guesses add parts to the hangman
4. **Use Hints**: Pay attention to the hint provided
5. **Win or Lose**:
   - **Win**: Guess the word before the hangman is complete
   - **Lose**: The hangman reaches 6 incorrect guesses
6. **Play Again**: Click "Play Again" to start a new game

## 🛠️ Built With

- **[Vue.js 3](https://vuejs.org/)** - Progressive JavaScript framework
- **[Vite](https://vitejs.dev/)** - Fast build tool and dev server
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[ESLint](https://eslint.org/)** - Code linting and formatting
- **[Prettier](https://prettier.io/)** - Code formatter

## 📱 Responsive Design

The game is fully responsive and works on:

- 🖥️ **Desktop**: Full layout with side-by-side hangman and game area
- 📱 **Mobile**: Stacked layout optimized for touch devices
- 📱 **Tablet**: Adaptive layout that scales appropriately

## 🎨 Customization

The game uses CSS custom properties for easy theming:

- `--color`: Primary game color (currently #5e63ba)
- `--white`: Background color (#fff)

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Classic Hangman game concept
- Vue.js community for excellent documentation
- Vite team for the amazing build tool

---

**Happy Gaming! 🎮✨**
