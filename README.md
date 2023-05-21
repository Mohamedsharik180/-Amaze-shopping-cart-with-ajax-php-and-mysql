# razorpay-payment-gateway-integration-in-php
Payment Gateway Method in PHP
Step1: Create Razorpay Account
First we need to create account on Razorpay and generate KeyId and Secret Key. We will keep created Razorpay account in test mode to test payment functionality.

Step2: Update Razorpay Config Details
Here in this example, we will use Test App to integrate Razorpay gateway. So we will update config.php with KeyId and Secret Key from Razorpay.

Step3: Create Form with Item Details
In index.php file, we will create HTML of test item with item details and customer details to send to perform payment. Here we have pay.php on action to handle payment.

Step4: Handle Item Details for Payment
In pay.php file, we will include config.php and Razorpay API files. We will also start session to store razorpay_order_id into session. We will create order data with payment amount and currency to generate Razorpay order id.

Step5: Perfrom Payment with Razorpay
In manual.php file, we will have JSON data to perform payment. We will include Razorpay API checkout.js and handle payment functionality.

