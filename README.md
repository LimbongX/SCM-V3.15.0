# SCM V3.15.0
-------
Changes
-------

1.0
---
First release version

1.2
---
IPN Bug Corrections
Added ipn Logs on admin
Correction on index redirect after login/register
Correction on redirect after logout

1.3
---
Rework on contact form
Clean code
Footer statistics
Admin pagination data
Settings migrated to DB
Admin settings page
Plans page with image selector

1.4
---
Bug fix on registration
Install wizard

1.5
---
Bug fix on purchase page
Bug fix on withdraw affiliate comissions page

1.6
---
Bug correction on wallet address on index

1.7
---
Bug correction on payment page
Bug correction on account withdraw table

1.8
---
Bug correction on withdraw affiliate page
Bug correction on admin plans page

1.9
---
Bug correction on admin withdraw request update
Removed USD convertion on payments page
New time left counter on dashboard page
Bug correction on validation field on index page
Little change on tables of account page
Change on wallet address validation(20-34 characters and allow hifen and underscores)

1.9.1
-----
Correction for payment page
Payment page now show confirmations required and Timeout to user make payment
Change on creation of transactions to avoid problems with IPN
Change on IPN to update pending transactions to waiting status
Correction of affiliate withdraws conflict with main balance
List pending deposits on account page
List affiliate withdraws on account page

1.9.2
-----
Bug fix on ipn integration

2.0
----
Bug correction on Profit Calculator.xlsx
Bug correction on admin login
Changes on plans management on admin
New admin theme
Social Links
Hide referral address
Add/Edit/Delete Blockchain URL's on admin
Automatic Blockchain url to TXID on payments page
Include http/https on referral link
Changes on install wizard
Change min/max characters of user wallet address on admin
Rename script from DogeMiner to SCM - Simple Cloud Mining Script

2.1
---
Bug fix on affiliate withdraws
Bug fix on ipn

2.2
---
Important bug fix to avoid negative balances on user accounts

2.3
---
Bug fix on admin pagination
Change on Coinpayments to avoid expired transactions
Correction on purchase page

2.4
---
Fix on withdraw affiliate
Fix on withdraw
Fix on admin pagination links

2.4.1
-----
Fix on purchase page to fix a problem with Coinpayments API

2.4.2
-----
Fix bug on user balance when use Block.io addon

2.5
---
Added Addon management on admin
Fixed small bug on manage user on admin
Added total profit calculation on admin dashboard
Added information about plan create/edit on admin
Changed encryption method on admin passwords

2.6
---
Fixed bug to avoid mass address creation(spam)

2.7
---
Change on Coinpayments integration

3.0
---
System Rebuilt in Codeigniter Framework
Enhanced security with xss and sql injection protection
IPN bug fix
Site style fixes to make it more responsive
Fixes for other minor bugs
Added: Admin Management
Added: Theme Change System
Added: Pending Transaction Limiting System
Added: Choose payment operation method (api or gateway)
Changed: New install wizard, with transaction hash generator and option to change admin url
Changed: Affiliate Balance Integrated with Master Balance
Changed: Free plan can now also expire
Added: User registration now requires password
Added: User must enter an email to be able to purchase upgrades
Added: Password Recovery System
Added: Payment page for pending transactions
Changed: Documentation with more information and tips

3.1
---
Bug fix on payments page
Bug fix on admin settings page
Removed the ID column of the payments page

3.2
---
Bug fix with date/time difference

3.3
---
Bug fix with date/time difference to fix negative balances

3.4
---
Security update of the Coinpayments settings storage method

3.5
---
Fixed errors when install Block.io and FaucetPay addons

3.6
---
Fixed bug on admin login page

3.7
---
Added option to disable Blockchain URL on Payouts page
Fixed "no input file specified" error
Fixed bug on amount column on user withdrawal table

v3.8 10-08-20
-------------
Fixed url bug on admin header logo
Added Online Days Feature

v3.9 24-09-20
-------------
Fixed price display on the website according to the decimal place setting

v3.10 04-11-20
--------------
Fixed duplicate transactions history when using Coinpayments Gateway mode

v3.11 29-11-20
--------------
Bug fix on the Withdrawal Requests page
Change in the layout of form fields on the Plans and Withdrawal Request pages

v3.12.0 07-03-21
----------------
Added Semantic Versioning
Improvements in the default template

v3.13.0 08-03-21
----------------
Fixed: Error logs on assets urls
Changed: Statistics separation between the site and the admin to optimize response time
Added: Caching of data from statistics, plans and other database data to optimize response time
Added: Clear cache button on Settings page
Added: Log Viewer on Admin
Added: Coinpayments Error logs when using API Mode(see the error messages on Log Viewer page)
Added: Animation when clicking the Confirm Withdrawal button
Added: Canceled status option for withdrawals

v3.13.1 20-03-21
----------------
Changed: Coinpayments IPN to ignore currency conversion notifications and avoid creating error logs
Fixed: Removed console log from dogeminer template

v3.13.2 06-04-21
----------------
Fixed: Validation error when updating user account data

v3.13.3 09-04-21
----------------
Fixed: Displaying the purchase amount on the payment page

v3.13.4 05-08-21
----------------
Added: Required libraries to Block.io addon

v3.14.0 25-04-22
----------------
Updated: Codeigniter to 3.1.13 to add compatibility with PHP 8/8.1
Fixed: Theme code to work with PHP 8/8.1
Added: Option to use admin/user email for Coinpayments email field on API mode

v3.15.0 29-04-22
----------------
Fixed: Bug in Ajax Login when using PHP 8
Added: Check for script/addon updates on the admin panel
Added: Change site slogan on the admin panel
Added: Change texts of Affiliate Program, Payouts, Contact Us page on the admin panel
Added: Insert additional css/javascript code on template via admin panel
Added: Create and edit F.A.Q.s on the admin panel
Added: Tip on how to find the blockchain explorer url of a specific currency
Added: Supported currency tips on settings page
Fixed: settings() helper
Added: Profit calculator on create/edit plans page in admin panel
Changed: Adjustments to user management pages
Added: Transaction details on IPN Logs view page
Added: Pagination counters on admin panel
Added: Withdrawal History list/view pages on admin panel
Fixed: Cache Blockchain URL to avoid unnecessary DB queries
Changed: Pre-populated host port field in the Installation Wizard
Fixed: HTTPS check on Installation Wizard
