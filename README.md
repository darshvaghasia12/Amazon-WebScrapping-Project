<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon Web Scraper</title>
</head>
<body>
    <h1>Amazon Web Scraper</h1>
    <h2>Introduction</h2>
    <p>This project is an Amazon Web Scraper built using Python. It allows users to track the price of a specific product on Amazon and receive email notifications when the price drops below a certain threshold.</p>
    <h2>Features</h2>
    <ul>
        <li><strong>Price Tracking:</strong> Tracks the price of a specific product on Amazon.</li>
        <li><strong>Email Notifications:</strong> Sends email notifications when the price of the product drops below a certain threshold.</li>
        <li><strong>Automatic Updates:</strong> Automatically checks the price of the product at regular intervals.</li>
        <li><strong>User-friendly:</strong> Easy-to-use interface with straightforward setup and configuration.</li>
    </ul>
    <h2>Technologies Used</h2>
    <ul>
        <li><strong>Python:</strong> Programming language used for building the web scraper.</li>
        <li><strong>Beautiful Soup:</strong> Python library used for web scraping.</li>
        <li><strong>Requests:</strong> Python library used for sending HTTP requests.</li>
        <li><strong>SMTPlib:</strong> Python library used for sending email notifications.</li>
        <li><strong>CSV:</strong> File format used for storing data.</li>
    </ul>
    <h2>Installation</h2>
    <ol>
        <li>Clone this repository to your local machine:</li>
        <code>git clone https://github.com/your-username/amazon-web-scraper.git</code>
        <li>Install the required Python libraries:</li>
        <code>pip install -r requirements.txt</code>
        <li>Set up your email configuration by modifying the <code>send_mail()</code> function in the <code>scraper.py</code> file.</li>
    </ol>
    <h2>Usage</h2>
    <ol>
        <li>Run the scraper by executing the following command:</li>
        <code>python scraper.py</code>
        <li>The scraper will start monitoring the price of the specified product on Amazon.</li>
        <li>If the price drops below the specified threshold, an email notification will be sent to the specified email address.</li>
    </ol>
    <h2>Configuration</h2>
    <ul>
        <li><strong>URL:</strong> Specify the URL of the product on Amazon that you want to track.</li>
        <li><strong>Threshold:</strong> Specify the price threshold below which you want to receive email notifications.</li>
        <li><strong>Email Settings:</strong> Configure your email settings (SMTP server, port, email address, and password) in the <code>send_mail()</code> function.</li>
    </ul>
    <h2>Example</h2>
    <p>Below is an example of the email notification sent by the scraper:</p>
    <pre>
        Subject: The Shirt you want is below $14! Now is your chance to buy!
        Darsh, This is the moment we have been waiting for. Now is your chance to pick up the shirt of your dreams. Don't mess it up! Link here: [Product Link]
    </pre>
    <h2>Disclaimer</h2>
    <p>Please use this scraper responsibly and in accordance with Amazon's terms of service. Scraping Amazon's website may violate their terms of service, so use at your own risk.</p>
    <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>
</body>
</html>
