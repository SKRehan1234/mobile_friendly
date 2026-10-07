# Task 4 - Mobile-Friendly Website Using CSS Media Queries

## Objective
Convert a desktop-style website into a mobile-friendly responsive layout using CSS media queries.

## Project Structure

```text
task4-mobile-friendly-website/
├── index.html
├── style.css
└── README.md
```

## How to Run in VS Code

1. Open this folder in Visual Studio Code.
2. Open `index.html`.
3. Right-click `index.html` and choose **Open with Live Server** if the Live Server extension is installed.
4. Alternatively, double-click `index.html` to open it directly in Chrome.

## How to Test Responsiveness

Open the website in Chrome.

1. Press `F12` or `Ctrl + Shift + I`.
2. Click the **Toggle device toolbar** button.
3. Test different mobile and tablet screen sizes.
4. Resize the browser window and check that:
   - Navigation wraps on smaller screens.
   - Hero content stacks vertically.
   - Cards change from columns to a single column.
   - Text remains readable.
   - Buttons fit within the viewport.
   - No horizontal scrolling occurs.

## Responsive CSS Used

The project uses:

- Flexible container widths using `%` and `min()`.
- `clamp()` for responsive heading sizes.
- Flexbox for navigation and hero layout.
- CSS Grid for cards.
- Media queries at:
  - `max-width: 900px`
  - `max-width: 768px`
  - `max-width: 480px`
- Responsive images with `max-width: 100%`.
- The viewport meta tag in `index.html`.

## Task 4 Concepts Covered

- Media Queries
- Responsive Web Design
- Mobile-first concepts
- Viewport
- CSS Units
- Flexbox
- CSS Grid
- Responsive Typography
- Mobile Navigation
- Preventing Overflow

## GitHub Submission

Create a new GitHub repository for this task and upload all project files.

Example Git commands:

```bash
git init
git add .
git commit -m "Complete Task 4 responsive website"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

Then submit your GitHub repository link according to the internship instructions.
