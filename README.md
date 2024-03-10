<!DOCTYPE html>
<html>

<head>
    <title> Monica's Waterfront Bakery & Cafe</title>
    <!-- Define characterset used-->
    <meta charset="UTF-8">
    <!-- Define page description-->
    <meta name="description" content="this is a page for Monica's Waterfront Bakery & Cafe">
    <!-- Define information about author-->
    <meta name="author" content="Marissa Dunham">
    <!-- other meta-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- style elements for body and table-->
    <style>
        body {
            background-color: rgb(120, 160, 235);
            font-family: serif;
            font-size: 14px;
        }

        table {
            border: 1px solid black;
        }
    </style>
</head>

<body>
    <img src="images/weblogo-scaled.jpg" width="500" height="100" alt="Monica's Waterfront Bakery & Cafe Logo" title="Monica's Waterfront Bakery & Cafe Logo">
    <h1> Contact Us</h1>
    <a href="tel:360 - 698-2991" target="_blank" rel="noopener">360 - 698-2991</a> <br />
    <address>
        Monica's Waterfront Bakery & Cafe <br />
        3472 NW Byron St <br />
        Silverdale, WA 98383 <br />
    </address>

    <p>
        <table>
            <tr>
                <th>Days</th>
                <th>Hours</th>
            </tr>
            <tr>
                <td>Mondays</td>
                <td>Closed</td>
        </tr>
        <tr>
            <td>Tuesdays</td>
            <td>7:00am - 5:00pm</td>
        </tr>
        <tr>
            <td>Wednesdays</td>
            <td>7:00am - 5:00pm</td>
        </tr>
        <tr>
            <td>Thursdays</td>
            <td>7:00am - 5:00pm</td>
        </tr>
        <tr>
            <td>Fridays</td>
            <td>7:00am - 5:00pm</td>
        </tr>
        <tr>
            <td>Saturdays</td>
            <td>8:00am - 4:00pm</td>
        </tr>
        <tr>
            <td>Sundays</td>
            <td>Closed</td>
        </tr>
    </table>
</p>
<form method="post" action="index.html">
    Name:<br />
    <input type="text" id="name" placeholder="enter your name" autofocus>
    <h2>Interested in:</h2>
    <input type="checkbox" name="interested-in" type="interested-in" value="reservations">reservations<br />
    <input type="checkbox" name="interested-in" type="interested-in" value="employment">employment<br />
    <input type="checkbox" name="interested-in" type="interested-in" value="allergy-info">allergy info<br />
    <input type="checkbox" name="interested-in" type="interested-in" value="other">other<br />
    <pr></pr>
    Comments<br />
    <textarea name="Comments" id="Comments" rows="10" col="30">additional information or questions</textarea>
    <p></p>
    Subscribe to our newsletter?
    Yes&nbsp;<input type="Monica's" name="newsletter" type="newsletter" value="Yes">
    No&nbsp;<input type="Monica's" name="newsletter" type="newsletter" value="No">
    </br>
    <input type="Submit" name="Subscribe" value="Subscribe" />
</form>
</body>
</html>
