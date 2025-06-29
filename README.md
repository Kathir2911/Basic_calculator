# Basic Calculator

A simple, responsive calculator web application built with HTML, CSS, and JavaScript for performing basic arithmetic operations.

## 🌐 Live Demo

**[View Live Calculator](https://kathir2911.github.io/Basic_calculator/)**

## 📋 Features

- **Basic Arithmetic Operations**: Addition (+), Subtraction (-), Multiplication (*), Division (/)
- **Clear Function**: Reset the display with the 'C' button
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Error Handling**: Displays "Error" for invalid calculations
- **Clean UI**: Modern, intuitive interface with hover effects
- **Keyboard-like Layout**: Familiar calculator button arrangement

## 🛠️ Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling, grid layout, and responsive design
- **JavaScript**: Calculator logic and DOM manipulation

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or dependencies required

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Kathir2911/Basic_calculator.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd Basic_calculator
   ```

3. **Open the calculator**
   - Simply open `index.html` in your web browser
   - Or use a local server for development

### File Structure

```
Basic_calculator/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 💻 Usage

1. **Numbers**: Click on number buttons (0-9) to input values
2. **Operations**: Use +, -, *, / buttons for arithmetic operations
3. **Calculate**: Press '=' to get the result
4. **Clear**: Press 'C' to clear the display and start over

### Example Calculations

- `7 + 3 = 10`
- `15 - 8 = 7`
- `6 * 4 = 24`
- `20 / 5 = 4`

## 🎨 Design Features

- **Grid Layout**: CSS Grid for organized button arrangement
- **Responsive**: Adapts to different screen sizes
- **Visual Feedback**: Hover effects on buttons
- **Color Coding**: Operators highlighted in orange
- **Clean Typography**: Easy-to-read Arial font

## 🔧 Technical Implementation

### JavaScript Functions

- `appendToDisplay(value)`: Adds clicked values to the display
- `clearDisplay()`: Resets the calculator display
- `calculateResult()`: Evaluates the mathematical expression using `eval()`

### CSS Features

- CSS Grid for button layout
- Flexbox for overall positioning
- Hover transitions for better UX
- Box shadows for depth

## 🐛 Known Limitations

- Uses `eval()` function for calculation (security consideration for production apps)
- No advanced mathematical functions (sin, cos, log, etc.)
- No memory functions (M+, M-, MR, MC)
- Limited to basic arithmetic operations

## 🤝 Contributing

This project was created as part of the Fnext internship program. If you'd like to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Kathir2911**
- GitHub: [@Kathir2911](https://github.com/Kathir2911)
- Project Repository: [Basic_calculator](https://github.com/Kathir2911/Basic_calculator)

## 🎯 Project Purpose

This calculator was developed as part of the **Fnext Internship** program to demonstrate:
- Frontend web development skills
- Clean, maintainable code structure
- Responsive design principles
- User interface/experience design

---

⭐ **If you found this project helpful, please give it a star!**