# OpenInviter

Open source OpenInviter is a free import contacts (addressbook) script from email providers and social networking site. It s a free self hosted solution that does not use a third party gateway (or API) to import contacts.

Requirements: Your server will need to have PHP5 installed with DOMDocument support and either cURL or WGET.

## Installation

* Upload the files to your webserver (subfolder is highly advised).
* Run postinstall.php (http://yourdomain/openinviter_dir/postinstall.php)

    **You may encounter the following errors:**  
    i) The cookie storing folder if not writable. (Change the cookie folder or modify it's permisions.)  
    ii) Php DOM extension is not installed. (Install dom extension for php)  
    iii) You don't have curl or wget installed. (Install curl or wget)
  
    **You may encounter the following warnings:**  
  i) A plugin does not work properly. (Your server has either a firewall or there is a connectivity error)

    **Note:** You have to fix all the errors or openinviter will probably not work.

    **Note*:** You can't run postinstall.php again for 2 minutes.

* Edit config.php to suit your needs.
* Delete postinstall.php
* Run example.php (http://yourdomain/openinviter_dir/example.php) and try to fetch your contacts.