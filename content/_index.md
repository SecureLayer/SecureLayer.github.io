---
title: 'Home'
date: 2025-01-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Improve Your Cybersecurity with SecureLayer
      text: 🧱 EASY. FREE (OPEN SOURCE). 🧱
      primary_action:
        text: Get Started
        url: https://github.com/SecureLayer/cybersecurity-starter-kit
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: https://github.com/SecureLayer/cybersecurity-starter-kit/blob/main/README.md
      announcement:
        text: "Announcing the release of our starter kit."
        link:
          text: "Read more"
          url: "/blog/"
    design:
    #   spacing:
    #     padding: [0, 0, 0, 0]
    #     margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "4000+"
          description: |
            security events  
            in France in 2024
        - statistic: "+15%"
          description: |
            of attacks
            compared to 2023
        - statistic: "37%"
          description: |
            of ransomware 
            are SMBs
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Features
      text: Build your cybersecurity with ease
      items:
        - name: Audit 
          icon: magnifying-glass
          description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
        - name: Fast
          icon: bolt
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Easy
          icon: sparkles
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
#       - name: No-Code
#         icon: code-bracket
#         description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
#       - name: Highly Rated
#         icon: star
#         description: Rated 5-stars by the community.
#       - name: Swappable Blocks
#         icon: rectangle-group
#         description: Build your pages with blocks - no coding required!
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Build a resilient, secure organization
          text: Secure your processes in 3 clear steps
          feature_icon: check
          features:
            - "Team-first — manage security responsibilities collaboratively"
            - "Single workflow — run your security program from one toolkit"
            - "No prerequisites - follow clear steps to secure your organisation"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Get Started
            url: https://github.com/SecureLayer/cybersecurity-starter-kit
        - title: Community
          text: Join our GitHub community — open issues, discuss, and collaborate asynchronously
          feature_icon: bolt
          features:
            - "Open issue tracker for questions"
            - "A large, active GitHub community of contributors and reviewers"
            - "Share your repo or configs and get practical feedback via PRs and discussions"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.png
          button:
            text: Join Github
            url: https://github.com/SecureLayer/cybersecurity-starter-kit
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Astrid Jean-Baptiste"
          role: "Operation Manager in a startup"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Fantastic — incredibly easy to follow. The ready-made security playbooks saved our team countless hours and let us focus on fixing real risks."
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Build a resilient, secure organization
      text: Secure your processes in 3 clear steps
      button:
        text: Get Started
        url: https://github.com/SecureLayer/cybersecurity-starter-kit
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300"
        css_style: ""
---
