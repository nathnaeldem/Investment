Here's a sample README for your Investment Calculator project:

---

# Investment Calculator

This is a simple React-based Investment Calculator that helps users estimate the future value of their investments by considering yearly contributions, expected return rate, and the investment duration.

## Features

- **User Input Form**: Allows users to input their current savings, yearly contribution, expected return rate, and investment duration.
- **Investment Projection**: Calculates the yearly growth of savings, including contributions and interest earned.
- **Detailed Table Output**: Displays a year-by-year breakdown of the investment growth, including yearly contributions, interest earned, and total savings at the end of each year.

## Technologies Used

- **React**: The app is built with React, utilizing components and hooks for state management.
- **CSS**: Basic styling is applied for layout and visual presentation.

## Project Structure

- **`App.js`**: The main component that manages the state and handles the core logic for the investment calculations.
- **`Header.js`**: A simple header component for the app.
- **`Form.js`**: A form component where users input their investment details.
- **`Table.js`**: A table component that displays the calculated investment data year by year.

## Installation and Setup

1. **Clone the Repository**: 
   ```
   git clone https://github.com/your-username/investment-calculator.git
   ```
   
2. **Navigate to the Project Directory**:
   ```
   cd investment-calculator
   ```
   
3. **Install Dependencies**:
   ```
   npm install
   ```

4. **Run the Application**:
   ```
   npm start
   ```

   The app should open automatically in your default web browser at `http://localhost:3000/`. If it doesn't, you can manually open this address.

## Usage

1. **Input Your Data**:
   - Enter your current savings.
   - Specify how much you plan to contribute each year.
   - Set your expected annual return rate (as a percentage).
   - Define the number of years you plan to invest.

2. **View the Results**:
   - The app will calculate and display the growth of your investment over time in a detailed table.
   - If no input is provided, a message will appear indicating "NO investment".

## Example

Assuming:
- Current Savings: $10,000
- Yearly Contribution: $2,000
- Expected Return: 5%
- Duration: 10 years

The app will calculate the total savings at the end of each year, factoring in the contributions and the interest earned on the investment.

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request. For major changes, please open an issue to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This README should provide users with a clear understanding of what the Investment Calculator does, how to install and use it, and how they can contribute to the project.
