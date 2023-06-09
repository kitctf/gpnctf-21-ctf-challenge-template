# Old Cage
Welcome to the old cage. Some stuff never gets old and some stuff continues to be insecure.
Find and exploit a flaw in the GitHub Actions workflow of this repository.

To do so, create a **fork** of this repository and then create a pull request from the **fork** against **this** repository.

## Adding Team Members/Collaborators
To add team members/collaborators, create a new issue in this repository with the content `/add @change-me-as-this-user-does-not-exist ...`.

## Testing
Please test your exploit first against your own **fork**, before testing against **this** instance, because GitHub Actions minutes are limited.

## Debugging
If you want to debug the actions, there is a special debug version.
To use this version, enable GitHub Actions in your **fork** and create a pull request from your **fork** against your **fork** repository itself.
The action will then run and afterwards you'll have a chance to use [tmate](https://github.com/mxschmitt/action-tmate/) to SSH into the machine.
