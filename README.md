# Sudoku Solver Visualizer

![Sudoku Solver Screenshot](https://user-images.githubusercontent.com/22812597/133980764-5ad36ade-84ae-4566-88c0-0fb7d163cb94.png)

An interactive web-based Sudoku solver that visualizes the backtracking algorithm in action. Watch step by step how the algorithm works to solve Sudoku puzzles.

## 🌟 Features

- 📊 Interactive Sudoku grid
- ⚡ Adjustable solving speed
- 📝 Array input support for quick puzzle setup
- 👁️ Visual representation of the backtracking process
- 🎨 Modern and clean user interface

## 🚀 Live Demo

Try it out: [Sudoku Solver Visualizer](https://punit-cp.github.io/Sudoku-solve/)

## 🛠️ Getting Started

### Prerequisites

- Node.js (v12.0.0 or higher)
- npm (v6.0.0 or higher)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Punit-CP/Sudoku-solve.git
   cd Sudoku-solve
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and visit:
   ```
   http://localhost:8080
   ```

### Building for Production

To create a production build:
```bash
npm run build
```

The built files will be available in the `dist` directory.

## 📖 Usage

1. **Manual Input**: 
   - Click on any cell in the grid
   - Enter numbers 1-9 to set up your puzzle

2. **Array Input**: 
   Use the textarea to input a 9x9 Sudoku grid as a 2D array. Example:
   ```javascript
   [
     ["5","3",".",".","7",".",".",".","."],
     ["6",".",".","1","9","5",".",".","."],
     [".","9","8",".",".",".",".","6","."],
     ["8",".",".",".","6",".",".",".","3"],
     ["4",".",".","8",".","3",".",".","1"],
     ["7",".",".",".","2",".",".",".","6"],
     [".","6",".",".",".",".","2","8","."],
     [".",".",".","4","1","9",".",".","5"],
     [".",".",".",".","8",".",".","7","9"]
   ]
   ```

3. **Speed Control**: 
   - Adjust the visualization speed using the "Speed (ms)" input
   - Lower values = faster visualization
   - Higher values = slower, more detailed visualization

4. **Solve**: 
   - Click the "Solve" button to start the visualization
   - Watch the backtracking algorithm in action!

## 🔧 Technology Stack

- JavaScript (ES6+)
- Webpack 5
- CSS3
- HTML5

## 🔍 Additional Information

- The solver uses a backtracking algorithm to find the solution
- An optimized version without visualization is available in the 'optimized' branch
- The project is built with pure JavaScript without any UI frameworks

## 📄 License

This project is licensed under the ISC License.

## 👏 Acknowledgments

- Built with pure JavaScript without any UI frameworks
- Uses backtracking algorithm for Sudoku solving
- Inspired by visualization tools for algorithmic problem-solving

## 🤝 Contributing

Feel free to contribute to this project. Any improvements or bug fixes are welcome!
