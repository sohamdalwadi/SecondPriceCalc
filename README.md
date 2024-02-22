# SecondPriceCalc
Estimate the second-hand price of your items with SecondPriceCalc. This user-friendly web application considers factors like original price, years of usage, condition, and market demand adjustments to provide a calculated estimate. Visualize the breakdown of the formula and make informed decisions when selling or buying used items.

## Features

- User-friendly Material Design interface.
- Calculates the second-hand price considering depreciation, condition adjustment, and market demand adjustment.
- Provides a breakdown of the calculation formula and the resulting second-hand price.

## Getting Started

Follow these steps to set up the Second-hand Price Calculator on your local machine.

### Prerequisites

- Ensure you have a modern web browser installed.
- Have Git installed on your machine.

### Installation

1. Clone the repository to your local machine.

    ```bash
    git clone https://github.com/sohamdalwadi/SecondPriceCalc.git
    ```

2. Open the `index.html` file in your preferred web browser.

## Usage

1. Open the web page in your browser.
2. Enter the required details:
   - Original Price (INR)
   - Years of Usage
   - Condition Adjustment (out of 100)
   - Demand Adjustment (out of 100)
3. Click the "Calculate Second-hand Price" button.
4. The estimated second-hand price will be displayed along with a breakdown of the calculation formula.

## Customization

Feel free to customize the base condition and base demand values in the JavaScript code according to your preferences and the characteristics of the item you are calculating for.

```javascript
const baseCondition = 100; // Set your base condition value
const baseDemand = 100;    // Set your base demand value

