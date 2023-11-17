# ZENCAPTCHA for Drupal
<a href='https://www.zencaptcha.com/docs/de/zencaptcha-drupal'>🇩🇪 Installation (auf Deutsch)</a> • 
<a href='https://www.zencaptcha.com/docs/fr/zencaptcha-drupal'>🇫🇷 Installation (en Français)</a>

Protects forms from abuse by bots and unfair users. Reduces spam, blocks fake and disposable email addresses and increases your user base quality without the use of cookies. Fully GDPR compliant.
Protect your Drupal forms and stay GDPR compliant.
Full documentation and code support: https://git.drupalcode.org/project/zencaptcha

# Installation
Install the ZENCAPTCHA module as you would normally install a contributed Drupal module. <a href="https://www.drupal.org/node/1897420">Visit Installing Modules</a> to learn more about installing modules on Drupal.
<br><br>
**3 methods to install ZENCAPTCHA:**
* 1. Go to the official <a href="https://www.drupal.org/project/zencaptcha">Drupal.org - ZENCAPTCHA</a> page to download the ZENCAPTCHA module.<br>
* 2. Or use ```composer require 'drupal/zencaptcha:^1.0'```
* 3. Or simple <a href="https://ftp.drupal.org/files/projects/zencaptcha-1.0.0.zip">click here</a> to download the .zip of the ZENCAPTCHA module.

* ⚠️ Then also download and activate <a href="https://www.drupal.org/project/captcha">CAPTCHA</a> (another module) ```composer require 'drupal/captcha:^2.0'``` . ZENCAPTCHA needs the CAPTCHA module to work.

# Configuration

**1. Go to the "Extend" section in the Administration panel and activate the module.**<br>
Administration > Extend

**2. Access "Configuration" in the Administration panel, then proceed to "People" and choose "CAPTCHA settings." Click on "ZENCAPTCHA."**<br>
Administration > Configuration > People > CAPTCHA settings > ZENCAPTCHA

**3. Enter the site and secret keys into the ZENCAPTCHA settings.**<br>

**4. In the "CAPTCHA settings" under "People" in the Administration panel, specify the locations where you wish to display the ZENCAPTCHA form.**<br>
Administration > Configuration > People > CAPTCHA settings

# Issues
Use https://git.drupalcode.org/project/zencaptcha to add your issues.
