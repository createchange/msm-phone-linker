# MSM-Phone-Linker

## Description
Phone Linker app, which turns phone numbers into links and prepends 61 to them.

Not created by me - only modified to take into account the VTN settings in use for the phone system. I forked this and made the required changes, then submitted and was approved in the Chrome Web Store.

## Installation
Extension is located here: https://chrome.google.com/webstore/detail/phone-linker/ekgblhphmkadaalikgpfgikcocefdagg

Can be force installed with a registry edit: 
~~~
reg add HKLM\SOFTWARE\WOW6432Node\Google\Chrome\Extensions\ekgblhphmkadaalikgpfgikcocefdagg /f /v update_url /t REG_SZ /d http://clients2.google.com/service/update2/crx
~~~
