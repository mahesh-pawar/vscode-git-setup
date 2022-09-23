# Setup PHP Debugger in VS Code Editor
These are the basic guide to setup PHP debugger in VS code editor.

<b>Step 1.</b> Make a simple test.php file, put a `phpinfo();` statement in there

<b>Step 2.</b> Copy the output and paste it into the Xdebug installation wizard ( https://xdebug.org/wizard.php ). It will analyze it and give you tailored installation instructions for your environment.

<b>Step 3.</b> Download php_xdebug-3.1.5-7.4-vc15-x86_64.dll ( https://xdebug.org/files/php_xdebug-3.1.5-7.4-vc15-x86_64.dll )

<b>Step 4.</b> Move the downloaded file to `C:\xampp\php\ext`, and rename it to `php_xdebug.dll`.

<b>Step 5.</b> Update `C:\xampp\php\php.ini` and add the line:

    [XDebug]
    xdebug.mode = debug
    xdebug.start_with_request = yes
    zend_extension = xdebug
<b>Step 6.</b> Restart the Apache Webserver
