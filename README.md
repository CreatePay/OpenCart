Setting up the module requires at a minimum a merchantID, a signature/secret key and a gateway URL. If you already have a CreatePay account please contact createcommerce@createpay.com. For all other enquires please contact hello@createpay.com.


# OpenCart
Payment module for OpenCart


Disclaimer: Please note that we no longer support older versions of SDKs and Modules. We recommend that the latest versions are used.


This OpenCart module provides an easy method to integrate with the payment gateway.

Supports Open versions: 3.X

Prerequisites
The module requires the following prerequisites to be met in order to function correctly:
The 'bcmath' php extension module: https://www.php.net/manual/en/book.bc.php
Please note that we can only offer support for the module itself. While every effort has been made to ensure the payment module is complete and bug free, we cannot guarantee normal functionality if unsupported changes are made.

Installing the module.
Zip the upload folder and rename it upload.ocmod so the full filename is upload.ocmod.zip
Navigate to the Extensions dropwon -> Installer
Upload the module useing the installer's upload option
Installing the module option 2
You can also install the module by copying the upload folder into the root OpenCart directory

Configuring the module
Navigate to the Extensions dropdown -> Extensions -> Payment methods -> Cardstream and click 'Activate'
Navigate to the Extensions dropdown -> Extensions -> Payment methods -> Cardstream and click the 'Edit' button
Enter your MerchantID / Secretkey and update the customer/country code
Select what type of integration you would like to use
Set what status you would like to update an order to once paid
Set the Enabled option to true
Click 'Save Changes'
