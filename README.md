# Product Table Example

This project demonstrates a simple HTML table that displays a list of products with their respective quantities, prices, and descriptions. The table also includes a summary row that calculates the total price of all products.

## Table Structure

The table consists of the following columns:

1. **Product Name**: The name of the product.
2. **Quantity**: The number of units of the product.
3. **Price per Unit**: The price of a single unit of the product.
4. **Description**: A brief description of the product.
5. **Total Price**: The total price for each product (Quantity × Price per Unit).

The final row in the table displays the sum of the total prices of all products.

## HTML Code

Below is the HTML code used to create the table:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Table</title>
</head>
<body>

<table border="1" cellpadding="5" cellspacing="0">
    <tr>
        <th>Product Name</th>
        <th>Quantity</th>
        <th>Price per Unit</th>
        <th>Description</th>
        <th>Total Price</th>
    </tr>
    <tr>
        <td>Product 1</td>
        <td>2</td>
        <td>10</td>
        <td>This is product 1</td>
        <td>20</td>
    </tr>
    <tr>
        <td>Product 2</td>
        <td>3</td>
        <td>20</td>
        <td>This is product 2</td>
        <td>60</td>
    </tr>
    <tr>
        <td colspan="4">Sum</td>
        <td>80</td>
    </tr>
</table>

</body>
</html>

How to Use
Copy the above HTML code into a .html file (e.g., index.html).
Open the file in a web browser to view the table.