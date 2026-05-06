# Sophie Felder Portfolio

## Files
- `index.html` — homepage
- `case-study-gems.html` — AI writing tools case study
- `case-study-guidelines.html` — design system guidelines case study
- `case-study-cms.html` — CMS project case study
- `case-study.css` — shared styles for all case study pages
- `ux-writing-bot.png` — screenshot for Gems case study
- `editing-bot.png` — screenshot for Gems case study

## How to publish on GitHub Pages

1. Go to github.com and sign in
2. Click the + button top right, select "New repository"
3. Name it exactly: `your-username.github.io` (replace with your actual GitHub username)
4. Set it to Public
5. Click "Create repository"
6. On the next screen click "uploading an existing file"
7. Drag all files from this folder into the upload area
8. Click "Commit changes"
9. Your site will be live at `https://your-username.github.io` within a minute or two

## How to update content
- To edit text on any page, open the .html file in any text editor and find the text you want to change
- To add a new case study, duplicate one of the existing case-study files and update the content
- To add the new case study to the homepage, open index.html and add a new list item following the same pattern as the existing three

## To add your CMS visuals when ready
- Save your anonymized image file into this folder
- In case-study-cms.html, find the confidential-note div and replace it with:
  `<img src="your-image-filename.png" alt="description of image" class="cs-image" />`
