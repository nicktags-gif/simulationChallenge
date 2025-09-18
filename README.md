# 🎲 Simulation Challenge - Monte Carlo Analysis

A comprehensive Quarto document demonstrating investment strategy simulations using Monte Carlo methods.

## 📊 Live Demo

View the interactive analysis: [https://nicktags-gif.github.io/simulationChallenge/index.html](https://nicktags-gif.github.io/simulationChallenge/index.html)

## 🎯 Challenge Overview

This project simulates two investment strategies:

1. **Single Coin Flip Strategy**: One flip with +50% win or -40% loss
2. **Multiple Coin Flips Strategy**: Multiple flips with the same win/loss percentages

## 🛠️ Technologies Used

- **Quarto**: For document generation and rendering
- **Python**: For simulation logic and analysis
- **NumPy & Pandas**: For numerical computations and data manipulation
- **Matplotlib & Seaborn**: For data visualization
- **GitHub Pages**: For hosting and deployment

## 📈 Key Features

- Monte Carlo simulation with 1,000+ iterations
- Statistical analysis of investment outcomes
- Interactive visualizations and charts
- Comprehensive risk assessment
- Counter-intuitive findings presentation

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/nicktags-gif/simulationChallenge.git
   cd simulationChallenge
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Render the document:
   ```bash
   quarto render index.qmd
   ```

## 📁 Project Structure

```
simulationChallenge/
├── index.qmd          # Main Quarto document
├── index.html         # Rendered HTML output
├── requirements.txt   # Python dependencies
├── .gitignore        # Git ignore rules
└── README.md         # This file
```

## 🔬 Simulation Parameters

- **Initial Balance**: $1,000
- **Win Probability**: 50% (fair coin)
- **Win Multiplier**: 1.5 (+50% gain)
- **Loss Multiplier**: 0.6 (-40% loss)
- **Simulations**: 1,000 iterations

## 📊 Results

The simulation reveals interesting insights about investment strategies and risk management, demonstrating the power of Monte Carlo methods in financial analysis.

---

*This project was created as part of a simulation challenge demonstrating generative models and Monte Carlo simulation techniques.*
