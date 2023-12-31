# ABN Javascript Assesment

#### Task:

Create a Javascript application (in a framework of your own preference e.g. Angular/Vue) that fulfills the following requirements (in a new branch):

##### Mortgage Calculator:

1. **HTML Form:**
   - Include an HTML form with the following fields:
     - Selection for 1 or 2 applicants.
     - Input field for "Your Monthly Salary."
     - Input field for "Partner's Monthly Salary." (Only when there is a 2nd applicant)
     - Display the total salary, with the following sum (Salary applicant 1 + (0.7 * Salary applicant 2)
     - Select the 'Length of mortgage in years' (looptijd) (values range from 1-30)
     - A button to trigger the calculation. The result should be displayed in months (divide by 12). (Yearly salary * looptijd * 0.25 (imaginary interest/quote) / 12
     - Add a unittest
     - Make the page multilingual (EN/NL) - Bonus (use i18n package for example)

2. **JavaScript Logic:**
   - Write JavaScript logic to calculate the total costs of the mortgage in months.
   - Use the provided template or create your own structure.

3. **Output:**
   - Display the result on the web page (e.g., below the button).

#### Evaluation Criteria:

- **Code Structure:** Organize your code in a clear and maintainable manner.
- **HTML/JavaScript Best Practices:** Follow best practices for HTML and JavaScript.
- **Error Handling:** Implement basic error handling for input values.
- **Styling:** Consider adding minimal styling for a better user experience.

#### Template:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mortgage Calculator</title>
    <!-- Include your external CSS file if styling is added -->
    <!-- <link rel="stylesheet" href="styles.css"> -->
    <script>
        // Your JavaScript logic goes here
    </script>
</head>
<body>
    <h1>Mortgage Calculator</h1>

    <!-- Your HTML form goes here -->

</body>
</html>
```

Feel free to customize the template and adjust the assessment criteria based on your specific requirements.
