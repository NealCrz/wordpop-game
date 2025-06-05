# WordPop! 🎮

A dynamic 2D word puzzle game that challenges players to strategically manipulate falling letter blocks to create words. Combines vocabulary skills with spatial reasoning through an engaging, real-time word formation mechanic.

## 🎯 Game Features

- **Tetris-Style Gameplay**: Letters fall from the top and stack at the bottom
- **Word Detection**: Create words horizontally and vertically (3+ letters)
- **Scrabble Mechanics**: Authentic letter distribution and scoring system
- **Mobile Controls**: Touch-friendly arrows for mobile gameplay
- **Expanded Dictionary**: 1,422+ validated words
- **Progressive Difficulty**: Speed increases as you advance
- **Special Bonuses**: 7+ letter words clear the board for massive points
- **Visual Effects**: Fireworks and animations for successful words

## 🎮 How to Play

1. **Movement**: Use arrow keys (desktop) or touch controls (mobile) to move falling letters
2. **Drop**: Press spacebar (desktop) or down arrow (mobile) to hard drop letters
3. **Form Words**: Create words horizontally or vertically with 3+ letters
4. **Score Points**: Longer words = more points (7+ letters clear the board!)
5. **Survive**: Keep the board from filling up to the top

## 🎯 Scoring System

- **3-letter words**: 5 points
- **4-letter words**: 10 points
- **5-letter words**: 15 points
- **6-letter words**: 20 points
- **7+ letter words**: 100 points + board clear

## 🛠️ Technology Stack

- **Frontend**: React + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Animations**: Framer Motion
- **Audio**: HTML5 Audio API

## 🚀 Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/NealCrz/wordpop-game.git
cd wordpop-game
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5000`

## 📱 Mobile Support

- Responsive design optimized for mobile devices
- Touch controls positioned under the game board
- Optimized for iPhone and Android devices

## 🎨 Game Components

- **Game Board**: 10x15 grid for letter placement
- **Letter Distribution**: Authentic Scrabble letter frequencies
- **Word Validation**: Comprehensive dictionary with 1,422+ words
- **Mobile Controls**: Left/Right arrows and drop button
- **Visual Feedback**: Highlighting, animations, and effects

## 🔧 Development

The game is built with modern React patterns and TypeScript for type safety. Key files:

- `client/src/components/Simple2DBlocks_fixed.tsx` - Main game logic
- `client/src/lib/stores/` - Game state management
- `client/src/lib/dictionary.tsx` - Word validation
- `client/src/lib/letterDistribution.tsx` - Scrabble letter system

## 🏆 Game Mechanics

- **Letter Bag**: 98 letters following Scrabble distribution
- **Word Detection**: Advanced algorithm finds words in continuous sequences
- **Gravity**: Letters fall and stack naturally
- **Collision**: Proper block placement and stacking
- **Game Over**: Triggered when letters reach the top

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to contribute to WordPop! by:
- Adding more words to the dictionary
- Improving mobile responsiveness
- Adding new visual effects
- Optimizing performance

---

**Enjoy playing WordPop!** 🎉