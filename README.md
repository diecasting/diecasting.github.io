# Alumcasting - Professional Die Casting Solutions

Welcome to the Alumcasting GitHub Pages website repository.

## About Alumcasting

Alumcasting is China's leading high-pressure die casting manufacturer. We specialize in:

- **Aluminum Die Casting** - HPDC processes for automotive and industrial applications
- **Magnesium Casting** - Lightweight solutions using AM60B and AZ91D alloys
- **Semi-Solid Casting** - Advanced Rheocasting and Thixocasting technologies
- **CNC Machining & Finishing** - Precision post-processing services
- **Custom Mold Design** - In-house mold development and manufacturing

## Website Features

- **Technical Blog** - In-depth articles on die casting processes, materials, and best practices
- **Category Navigation** - Browse articles by topic (Aluminum, Magnesium, Mold Technology, etc.)
- **Tag Filtering** - Find articles by specific technologies and materials
- **Contact Form** - Reach out for custom casting solutions and quotes

## Building the Site Locally

This site uses Jekyll with the Chirpy theme.

### Prerequisites

- Ruby 3.0+
- Bundler

### Setup

```bash
git clone https://github.com/diecasting/diecasting.github.io.git
cd diecasting.github.io
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000` to view the site.

## Quality Assurance

All internal links are validated using HTML-Proofer. The site must pass validation before deployment.

```bash
bundle exec jekyll build
bundle exec htmlproofer _site
```

## License

This work is published under MIT License.
