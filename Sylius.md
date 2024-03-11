I found a stored Cross-site script in Sylius application in 1.12.13 version.

Steps to Reproduce:

Log in to the application as a demo shop user.
Navigate to My Account > Address book.
Insert the payload:

*<IMG """><SCRIPT>alert("XSS")</SCRIPT>">*

into the "Province" field.

Upon clicking edit again, the payload is successfully executed.



Attached are screenshots demonstrating the exploitation of the vulnerability.

![sylius_xss_set_payload](https://github.com/r2tunes/Reports/assets/57819536/61589363-ea91-4514-a7c8-ec27499440ce)


![sylius_xss_exploit](https://github.com/r2tunes/Reports/assets/57819536/44c14514-c3bf-481f-8c37-76192b705186)


