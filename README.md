# profile
This is my profile / resume / CV

## Simple Online Profile Creation Guide

This guide provides step-by-step instructions to create a basic online profile page using HTML and host it on GitHub Pages, just like [my profile](https://chanchal-kumar-mandal.github.io/profile/).

## Prerequisites

* A GitHub account.
* Basic understanding of HTML.
* A text editor (e.g., VS Code, Sublime Text, Notepad).

## Steps

1.  **Create a GitHub Repository:**
    * Go to your GitHub account and create a new repository.
    * Name it `profile` (or any name you prefer).
    * Make sure it's public.
    * Initialize it with a `README.md` file (optional, but good practice).

2.  **Create an `index.html` File:**
    * In your text editor, create a new file named `index.html`.
    * Add the following basic HTML structure:

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Your Profile</title>
        <style>
            body {
                font-family: sans-serif;
                margin: 20px;
                line-height: 1.6;
            }
            .profile-image {
                width: 150px;
                border-radius: 50%;
                margin-bottom: 20px;
            }
            .profile-section{
                margin-bottom: 30px;
            }
        </style>
    </head>
    <body>
        <div class="profile-section">
            <img src="your-profile-image.jpg" alt="Your Profile Picture" class="profile-image">
            <h1>Your Name</h1>
            <p>Your Title/Profession</p>
        </div>

        <div class="profile-section">
            <h2>About Me</h2>
            <p>Write a brief description about yourself.</p>
        </div>

        <div class="profile-section">
            <h2>Skills</h2>
            <ul>
                <li>Skill 1</li>
                <li>Skill 2</li>
                <li>Skill 3</li>
            </ul>
        </div>

        <div class="profile-section">
            <h2>Contact</h2>
            <p>Email: your.email@example.com</p>
            <p>LinkedIn: <a href="your-linkedin-profile-url">Your LinkedIn</a></p>
            <p>GitHub: <a href="your-github-profile-url">Your GitHub</a></p>
        </div>
    </body>
    </html>
    ```

3.  **Customize Your Profile:**
    * Replace placeholders like "Your Name," "Your Title," "your-profile-image.jpg," "your.email@example.com," and URLs with your actual information.
    * Add your skills, about me section, and other relevant details.
    * Add an image named your-profile-image.jpg or change the html to match the name of your image.
    * Add styling within the \<style\> tags to change the look of your page.

4.  **Upload to GitHub:**
    * Commit and push your `index.html` file and profile picture to your GitHub repository.
    * If you use a profile picture, make sure it is in the same directory as your index.html file.

5.  **Enable GitHub Pages:**
    * Go to your repository settings on GitHub.
    * Scroll down to the "Pages" section.
    * In the "Source" dropdown, select "deploy from a branch" and choose the main or master branch.
    * Click "Save."
    * GitHub Pages will build your site. This may take a few minutes.
    * Once deployed, you'll see a link to your live profile page (e.g., `https://your-username.github.io/profile/`).

6.  **Access Your Live Profile:**
    * Visit the link provided by GitHub Pages to see your live profile.

## Further Customization

* Add more HTML elements and CSS styles to enhance your profile.
* Include links to your projects, portfolio, or resume.
* Use a CSS framework (like Bootstrap or Tailwind CSS) for faster styling.
* Add a portfolio section.
* Add a contact form.
* Add Javascript to make it more interactive.

## Example Image placement.

If you have an image called `my_profile_pic.png` in the same directory as your index.html file, your image tag would look like this.

```html
<img src="my_profile_pic.png" alt="Your Profile Picture" class="profile-image">
