# wp-smtp-from-wp-config
SMTP Plugin with values from wp-config.php. Avoid override functions.php that can be changed by theme's updates. No weight to wordpress added.

Add this values in wp-config.php

// SMTP email settings
define( 'SMTP_USER', 'mail@domain.ext' );  // username of host like Gmail
define( 'SMTP_PASS', 'password' );   // password for login into the App
define( 'SMTP_HOST', 'yourhost.smtp' );     // SMTP server address
define( 'SMTP_FROM', 'mail@domain.ext' );   // Your Business Email Address
define( 'SMTP_NAME', 'AwesomeMail' );   //  Business From Name
define( 'SMTP_PORT', '465' );     // Server Port Number
define( 'SMTP_SECURE', 'ssl' );   // Encryption - ssl or tls
define( 'SMTP_AUTH', true );  // Use SMTP authentication (true|false)
define( 'SMTP_DEBUG', 0 );  // for debugging purposes only
