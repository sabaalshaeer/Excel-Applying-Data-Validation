# Excel-Applying-Data-Validation
Enable and configure the data validation settings.
    Make sure that the North American worksheet is selected and that cell B3 is selected.
    Select Data→Data Validation.
    In the Data Validation dialog box, select the Settings tab if necessary, and from the Allow drop-down list, select List.
    Select the Source field, then select Formulas→Use in Formula and select Reported_By.
    Verify that the Source field displays =Reported_By.

Configure the input message for data validation.
    In the Data Validation dialog box, select the Input Message tab.
    Verify that the Show input message when cell is selected check box is checked.
    Select the Title text box and type Expense Reporter
    Press Tab and in the Input message text box, type Select the person reporting the expense.
    Verify that your settings look like this image.

Configure the error alert for data validation.
    In the Data Validation dialog box, select the Error Alert tab.
    Verify that the Show error alert after invalid data is entered check box is checked. Verify that the Style drop-down list has Stop selected.
    Select the Title text box and type Reported By Error
    Select the Error message text box and type Please select a user from the list.
    Verify that your settings look like this image.
    Select OK.

View the data validation input message and error alert.
    Verify that cell B3 is selected and that the Input Message is displayed.
    Type your first name in cell B3 and press Enter.
    In the Reported By Error dialog box, select Cancel.

Apply data validation to the expense values.
    Select Data→Data Validation.
    In the Data Validation dialog box, select the Settings tab, and from the Allow drop-down list, select Decimal.
    In the Data drop-down list, verify that between is selected.
    Select the Minimum field and type 100
    Select the Maximum field and type 1000
    Select the Input Message tab and uncheck the Show input message when cell is selected check box.
    Select the Error Alert tab, then from the Style drop-down list, select Warning.
    Select the Title text box and type Invalid Expense
    Select the Error message text box and type Enter a value between 100 and 1000.
    Select OK.

Test data validation.
    Select cell B3 and select the drop-down arrow that appears to the right of the cell.
    Select Claire Gibbs.
    Select cell E6, type 525.75 and press Enter.
    In cell E7, enter 10,000
    Verify that the error alert Invalid Expense appears.
    Note: An error alert with a Style set to Warning will allow for non-standard or invalid data entry.
    Select Yes to ignore the warning.
