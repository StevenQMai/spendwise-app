# SpendWise - GitHub Pages Showcase

This is the GitHub Pages showcase website for the SpendWise project, built with Jekyll.

## Getting Started

### Prerequisites

- Ruby (version 2.7 or higher)
- Bundler gem

### Installation

1. Clone this repository
2. Install dependencies:
   ```bash
   bundle install
   ```

### Running Locally

To run the Jekyll site locally:

```bash
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

### Building for Production

To build the site:

```bash
bundle exec jekyll build
```

The built site will be in the `_site` directory.

## Project Structure

```
.
├── _config.yml          # Jekyll configuration
├── _data/
│   └── navigation.yml   # Navigation menu data
├── _includes/           # Reusable HTML components
├── _layouts/            # Page layout templates
├── _sass/               # Sass stylesheets
├── assets/
│   ├── css/            # Compiled CSS
│   └── images/         # Images and screenshots
├── index.md            # Home page (Introduction)
├── design.md           # Design & Architecture page
├── ui.md               # User Interface page
├── functionality.md    # Functionality page
├── conclusions.md      # Conclusions & Reflections page
├── contributors.md     # Contributors page
└── Gemfile             # Ruby dependencies
```

## Adding Content

### Screenshots

1. Add your screenshots to `assets/images/`
2. Update the image paths in `ui.md`
3. Recommended format: PNG or JPG, optimized for web

### Video Demonstration

1. Upload your video to YouTube, Vimeo, or similar platform
2. Get the embed code
3. Replace the placeholder in `functionality.md` with the embed code

### UML Diagrams

1. Create your diagrams using tools like PlantUML, draw.io, or Lucidchart
2. Export as PNG or SVG
3. Add to `assets/images/`
4. Update references in `design.md`

### Team Information

1. Add team member photos to `assets/images/`
2. Update `contributors.md` with actual team member information
3. Include roles, contributions, and links

## Deployment to GitHub Pages

### Automatic Deployment

1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select the branch (usually `main` or `gh-pages`)
4. GitHub will automatically build and deploy your site

### Manual Deployment

If you need to deploy manually:

```bash
bundle exec jekyll build
# Then push the _site directory contents to gh-pages branch
```

## Customization

### Changing Colors

Edit `_sass/main.scss` and modify the color variables:
- `$brand-color`: Primary brand color
- `$text-color`: Text color
- `$background-color`: Background color

### Adding Pages

1. Create a new `.md` file in the root directory
2. Add front matter with layout and title
3. Add navigation link to `_data/navigation.yml`

### Modifying Layout

Edit files in `_layouts/` and `_includes/` to customize the site structure.

## License

[Add your license information here]

## Contact

For questions or contributions, please contact the SpendWise team.

