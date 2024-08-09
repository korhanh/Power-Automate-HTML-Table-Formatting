# HTML Table Formatting with Power Automate

This project provides a detailed guide on creating HTML tables in Outlook emails using Microsoft Power Automate. You can easily extract data, convert it into an HTML table, and style it with CSS.

## How It Works

1. Data Retrieval: Use the Get items action to fetch data from your data source.
2. Create HTML Table: Convert the retrieved data into an HTML table using the Create HTML table action.
3. Apply CSS: Style the table with CSS.
4. Send Email: Include the styled HTML table in the email body.
   
## Features

- Dynamic Table Creation: Generates HTML tables based on your data.
- Custom Styling: Personalize the appearance of your table with CSS.
- Outlook Compatibility: Ensures the HTML table displays correctly in Outlook emails.
- Easy Integration: Seamlessly integrates into Power Automate flows.
  
## Requirements

- Microsoft Power Automate subscription
- Basic knowledge of creating Power Automate flows


## Getting Started

1. Import the provided template into your Power Automate flow.
2. Adjust data and styling settings according to your needs.
3. Complete the flow and enable email sending.

## Example HTML Table and eMail Template

Example of how the HTML table and CSS might look:
```plaintext
<head>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
      background-color: #f4f4f4;
    }
    .container {
      border: 1px solid #ccc;
      padding: 20px;
      border-radius: 10px;
      display: inline-block;
      background-color: #fff;
    }
    .container img {
      width: 100px;
      height: 100px;
      margin-bottom: 20px;
    }
    .container h1 {
      color: #4CAF50;
      margin-top: 20px;
    }
    .container p {
      color: #555;
      margin-top: 10px;
    }
    /* Table styles */
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }
    th, td {
      border: 1px solid #ddd;
      padding: 8px;
      text-align: left; 
    }
    th {
      background-color: #f2f2f2;
    }
  </style>
</head>
```
Example of how the eMail Body might look:
```plaintext
<body>
    <h1>HTML Table in Outlook with Power Automate</h1>
@{body('Create_HTML_table')}
</body>
```

![Html-Table](https://github.com/korhanh/Power-Automate-HTML-Table-Formatting/blob/main/Example-HTML_flow.PNG)



## Contributions and Feedback

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://github.com/korhanh/Power-Automate-HTML-Table-Formatting/blob/main/LICENSE).

Feel free to use, modify, and distribute this project according to the terms specified in the license.

## Credits

This project is created and maintained by [korhanh]([link_to_your_github_profile](https://github.com/korhanh)).

If you use this project or find it helpful, consider giving it a star on GitHub!

Happy HTML Table Formatting! :rocket:

