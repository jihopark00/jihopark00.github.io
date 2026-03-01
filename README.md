# Personal Academic Website

A personal academic website template based on [Jon Barron's website](https://github.com/jonbarron/jonbarron.github.io)

## Setup

1. Replace `images/profile.jpg` with your profile photo
2. Replace `images/paper1.png`, `paper2.png`, etc. with your paper thumbnails
3. Edit `index.html` to add your information:
   - Name and pronunciation
   - Bio and research interests
   - Links (email, CV, social media)
   - Publications
4. Add your CV to `data/CV.pdf`

## Deployment

### GitHub Pages
1. Create a repository named `yourusername.github.io`
2. Push this code to the repository
3. Your site will be live at `https://yourusername.github.io`

## File Structure

```
.
├── index.html          # Main page
├── stylesheet.css      # Styles
├── images/             # Images folder
│   ├── profile.jpg     # Your profile photo
│   ├── paper1.png      # Paper thumbnails
│   └── ...
├── data/               # Data files
│   └── CV.pdf          # Your CV
└── README.md
```

## Customization

- Edit `stylesheet.css` to change colors, fonts, or layout
- The highlight color is `#ffffd0` (light yellow)
- Link color is `#1772d0` (blue), hover color is `#f09228` (orange)



<!-- cd /home/ljeadec31/opt/page && python3 -m http.server 8001  -->
<!-- pkill -f "python3 -m http.server 8000" -->
