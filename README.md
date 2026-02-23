# Resume

A professional resume website built with Jekyll and hosted on GitHub Pages.

## Quick Start

### 1. Update Your Information

Edit the `_data/data.yml` file with your personal information, work experience, education, and skills.

### 2. Add Your Profile Picture

Add a profile picture (100x100px recommended) to `assets/images/` and name it `profile.png`, or update the filename in `_data/data.yml`.

### 3. Configure Site Settings

Update `_config.yml`:
- Change `url` to your GitHub Pages URL (e.g., `https://yourusername.github.io`)
- Change `baseurl` to your repository name (e.g., `/resume`) or leave empty if using `yourusername.github.io`

### 4. Enable GitHub Pages

1. Go to your repository Settings
2. Navigate to Pages section
3. Under "Source", select your branch (usually `main`)
4. Click Save

Your site will be available at `https://yourusername.github.io/resume/` (or your custom domain)

## Local Development

To run the site locally:

```bash
# Install dependencies
bundle install

# Run the development server
bundle exec jekyll serve

# Visit http://localhost:4000/resume/ in your browser
```

## Customization

- **Data**: Edit `_data/data.yml` to update all resume content
- **Theme**: The site uses the [online-cv](https://github.com/sharu725/online-cv) theme
- **Styling**: You can customize colors and styles by creating custom CSS files

## Adding a PDF Version

Place your PDF resume in the `pdf/` folder and update the `pdf` link in `_data/data.yml` to enable the PDF download button.

## License

This project uses the online-cv theme. Check the theme repository for license information.
