
---

# Spurt! Empire Games Website

This repository hosts the official website for **Spurt! Empire Games** – an educational and entertaining board game that simulates the journey of building a business empire. The website aims to inform potential buyers about the game, highlight its unique features, and provide an easy online purchasing experience.

## Project Overview

The **Spurt! Empire Games** website is built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages. It includes engaging visuals, informative content, and clear calls to action, creating a seamless experience for users interested in strategy and educational games.

### Key Features
- **Dynamic Design**: Vibrant and engaging visuals to showcase gameplay, components, and unique selling points.
- **Responsive Layout**: Optimized for desktop and mobile to ensure an accessible experience across devices.
- **User-Friendly Navigation**: Simple structure with essential sections like About, Features, Purchase, and Contact.
- **Integrated Purchase Page**: Secure purchasing options for visitors to buy the game easily.

## Project Structure

```
spurt-empire-games/
├── _config.yml             # Site configuration
├── _includes/              # Reusable components (header, footer)
├── _layouts/               # Layouts for different pages
├── assets/                 # CSS, images, and other assets
├── index.md                # Home page
├── about.md                # About the Game page
├── features.md             # Features page
├── purchase.md             # Purchase page
└── contact.md              # Contact page
```

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/emediongfrancis/spurt-empire-games.git
   cd spurt-empire-games
   ```

2. **Install Dependencies**:
   Ensure you have [Ruby](https://www.ruby-lang.org/en/) and [Jekyll](https://jekyllrb.com/) installed. Then run:
   ```bash
   bundle install
   ```

3. **Serve the Site Locally**:
   ```bash
   bundle exec jekyll serve
   ```
   The site will be accessible at `http://localhost:4000`.

## Customization

- **Content**: Edit the markdown files (`index.md`, `about.md`, etc.) to update text and images.
- **Styles**: Modify `assets/css/styles.css` to change colors, fonts, and layout.
- **Configuration**: Adjust `_config.yml` for site settings, social links, and navigation.

## Deployment

1. **Push Changes to GitHub**:
   Commit and push changes to the `main` branch.
   
2. **Enable GitHub Pages**:
   Go to the repository settings on GitHub and enable GitHub Pages from the `main` branch.

The live site will be accessible at `https://<your-username>.github.io/spurt-empire-games`.

## License

This project is licensed under the MIT License.

---

This README provides a solid overview for anyone accessing the repository, covering setup, customization, and deployment instructions. Let me know if you'd like to add more sections or details!