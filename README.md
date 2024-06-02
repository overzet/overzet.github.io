# Site settings
title: Jan Overzet
description: >
  <h3>This is my portfolio</h3>
  <p>Top UK YouTube Influencers 2024</p>
logo: /assets/logo.png  # Ensure you upload your logo to the assets folder in your repository
show_downloads: true

# URL settings
# baseurl: "" # The subpath of your site, e.g. /blog
url: "https://overzet.github.io" # Your GitHub Pages URL

# Theme settings
remote_theme: pages-themes/cayman@v0.2.0
plugins:
  - jekyll-remote-theme

# Markdown settings
markdown: kramdown
highlighter: rouge

# Build settings
exclude:
  - Gemfile
  - Gemfile.lock
  - node_modules
  - vendor/bundle
  - vendor/cache
  - vendor/gems
  - vendor/ruby

# Jekyll configuration
jekyll:
  theme: cayman
  plugins:
    - jekyll-remote-theme

# Custom configurations
header_includes:
  - <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css" integrity="sha384-dy00bVm7IE7lthZtZL7ILF8VdGU90K4Rs2e1cdEOLysZ0LO0l7nCgK6Wj8F2oXK8" crossorigin="anonymous">
  - <style>
      body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        background-color: #f4f4f4;
      }
      .container {
        max-width: 960px;
        margin: auto;
        padding: 20px;
      }
      h1, h2, h3 {
        color: #333;
      }
      p {
        color: #555;
      }
    </style>

# Social media links
social_links:
  - name: GitHub
    link: https://github.com/yourusername
    icon: fab fa-github
  - name: LinkedIn
    link: https://www.linkedin.com/in/yourusername
    icon: fab fa-linkedin
  - name: Twitter
    link: https://twitter.com/yourusername
    icon: fab fa-twitter

# Custom sections (e.g., for influencers)
influencers:
  - name: Influencer 1
    link: https://www.youtube.com/channel/UC123456789
    description: Description of Influencer 1
  - name: Influencer 2
    link: https://www.youtube.com/channel/UC987654321
    description: Description of Influencer 2
  - name: Influencer 3
    link: https://www.youtube.com/channel/UC555555555
    description: Description of Influencer 3
