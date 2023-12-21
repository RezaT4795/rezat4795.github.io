# Signup With Email

![SignupWithEmail](../_media/Onboarding/SignupWithEmail.png)

### Frequency

Once, after Signup Page, User can also navigate back from here.

### Dependencies

[Signup Page](docs/onboarding/SignupPage.md)

### Pre-conditions

User must have pressed "Continue with Email" on the "Signup" page.

### Expected Behaviour

1. The page should have a title saying "Sign up to WordUp".

2. Under the title, there should be an paper icon. 

3. Under the paper icon, there should be at least 3 input fields:
   - Email: This is the field that user should type their email address in. It also has a greyed-out text inside: "Your email". This field is mandatory.
   - First name: This is the field that user should type their first name in. It also has a greyed-out text inside: "First name". This field is mandatory.
   - Last name: This is the field that user should type their last name in. It also has a greyed-out text inside: "Last name". This field is optional.
   - Year of birth: This is the field that user should type their birth year in. It also has a greyed-out text inside: "Year of birth". This field will be shown only if the user have chosen "8 - 12" or "13 - 17" group on the "Select Age Group" page, and if it shows up, it will be mandatory.

4. It should have a "Next" button at the bottom of the page. Pressing this button:
   - If the email field is empty or invalid, it will show an alert saying "Please enter a valid email address."
   - If the first name field is empty, it will show an alert saying "Please enter a valid name."
   - If the year of birth field is shown and empty, it will show an alert saying "Please provide your correct year of birth."
   - If the year of birth field is shown and its value doesn't match the chosen age group, it will show an alert saying "Your age and age group does not match!"
   - If the email address is valid but already registered, will show a popup saying "This email already registered with WordUp before." with an "OK" button.
   - If the email address is valid and not registered, it will send an email containing a security pin to the entered email, and will take the user to the "Security PIN" page.

5. Under this button, there should be a small text saying "By creating an account, you agree to our terms and privacy policy.".