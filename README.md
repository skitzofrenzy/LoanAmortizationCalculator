# Loan Amortization Calculator

The Loan Amortization Calculator is a user-friendly web application designed to help users calculate and visualize their loan repayment schedules. By inputting key loan parameters, users can generate detailed amortization schedules, explore payment summaries, and customize the application's appearance to their preferences.

👉 **Live Site**: [https://skitzofrenzy.github.io/LoanAmortizationCalculator/](https://skitzofrenzy.github.io/LoanAmortizationCalculator/)

## Features

- **Loan Details Input**: Enter loan amount, annual interest rate, loan term, additional monthly payments, and start date.
- **Amortization Schedule Generation**: View a comprehensive table detailing each payment's breakdown into principal and interest components.
- **Payment Summary**: Obtain a concise summary of regular and additional payments.
- **Customization Options**: Adjust themes, text sizes, and fonts to personalize the user interface.
- **Data Persistence**: Automatically saves user inputs using localStorage for convenience in subsequent sessions.
- **Tooltips**: Informative tooltips provide guidance on input fields and key terms.

## Getting Started

To run the Loan Amortization Calculator locally:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/LoanAmortizationCalculator.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd LoanAmortizationCalculator
   ```

3. **Open the Application**:

   Open the `index.html` file in your preferred web browser.

## Usage

1. **Input Loan Details**:

   - **Loan Amount**: Total amount borrowed.
   - **Annual Interest Rate**: Yearly interest rate percentage.
   - **Loan Term**: Duration of the loan in years.
   - **Additional Monthly Payment**: Extra amount paid monthly towards the principal.
   - **Start Date**: Date when the loan repayment begins.

2. **Calculate Schedule**:

   Click on the "Calculate" button to generate the amortization schedule and payment summary.

3. **Customize Appearance**:

   - **Settings**: Access the settings modal to change themes (Light, Dark, Blue), text sizes (Small, Medium, Large), and fonts (e.g., Arial, Times New Roman).
   - **Version History**: View the changelog of the application.
   - **Disclaimer & Privacy**: Read about data usage policies and disclaimers.

## Amortization Schedule

The generated amortization schedule provides a month-by-month breakdown of:

- **Payment Number**: Sequential number of the payment.
- **Payment Date**: Date of the payment.
- **Beginning Balance**: Loan balance before the payment.
- **Scheduled Payment**: Total payment amount for the month.
- **Principal**: Portion of the payment applied to the loan principal.
- **Interest**: Portion of the payment applied to interest.
- **Ending Balance**: Loan balance after the payment.

## Customization Options

- **Themes**: Choose between Light, Dark, and Blue themes to suit your preference.
- **Text Size**: Adjust text size for better readability with options for Small, Medium, and Large.
- **Fonts**: Select from various fonts to personalize the application's appearance.

## Data Persistence

The application utilizes localStorage to remember user inputs, ensuring that your data is available even after refreshing the page or closing the browser.

## Tooltips

Hover over the information icons next to input fields and table headers to get detailed explanations, enhancing user understanding of the terms and functionalities.

## Version History

- **v1.0**: Basic loan calculator with amortization schedule.
- **v2.0**: Added additional monthly payment and cumulative summaries.
- **v3.0**: Integrated localStorage, tooltips, and theme switcher.
- **v4.0**: Introduced modern card layout, 3‑column detail views, and print‑friendly design.
- **v5.0**: Added dynamic text size switcher and version history modal.
- **v6.0**: Moved settings into a modal and converted welcome message to a toast.
- **v7.0**: Enhanced detailed tooltips, converted detail displays into transparent tables, integrated summary data into the amortization table.
- **v8.0**: Added updates to version history and made tooltip icons and text resize dynamically based on text size settings.

## Disclaimer

This project is intended for educational and informational purposes only. The calculations provided by this application are estimates and should not be considered financial advice. Always consult with a financial advisor or lending institution for precise information.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

Special thanks to [skitzofrenzy](https://github.com/skitzofrenzy) for their contributions to this project.

---

By providing a comprehensive and user-friendly interface, the Loan Amortization Calculator aims to assist users in understanding their loan repayment structures and making informed financial decisions.
