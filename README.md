# Formik Ready Fields

Even though Formik provides wonderful functionality for implementing forms in React, there's still a lot of boilerplate.

Maybe that's fine for larger projects, but for small throw-away projects like job interview live/take-home coding tests, extreme speed is a real issue, and you just want basic Formik form components that you can just plop into your app that are guaranteed to work.

This was the motivation behind me creating this library. Reading the source code is also a great way to refresh your memory about how to implement and validate all the different form elements like:

-   Regular text fields
-   Email text fields
-   Confirm email text fields
-   Number text fields
-   Radio buttons
-   Check boxes
-   Drop downs

## Validation

I'm using Yup for validation, although you can override the defaults by supplying a Yup schema as a prop.

## Drop Downs

I'm using React-Select for dropdowns. Hope you dig it.

## Contributions

Enjoyed using the library but want to see it develop further? Please clone and send me a PR.

Happy coding! =)
