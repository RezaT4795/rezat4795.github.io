# Security PIN

It should have a box containing:
1. A title saying "Your security PIN was sent to:"

2. The user's email address.

3. An input field to enter the security PIN, along with a greyed-out text "Security PIN".

4. A "Log in" button. Pressing this button:
a. If the PIN input field is empty, it will show an alert saying "Please enter the PIN sent to your email.".
b. If the PIN is invalid, it will show an alert saying "Incorrect PIN. Please enter the pin you received in the registration email.".
c. If the PIN is valid, it will navigate the user to the next page that will show a spinning animation with a text saying "Please wait, logging you in". After that, it will sign the user in and depending on the userfile's data, it will navigate the user to the next page.

5. A "Resend code" hyperlink button. Pressing it will send another PIN email to the user's email address and will invoke an alert saying "A new security pin has been sent to your email".

