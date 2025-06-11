# Sign-up Form Project

A responsive sign-up form implementation for The Odin Project's Intermediate HTML and CSS course. This project demonstrates the use of modern CSS features, form validation, and responsive design principles.

## Features

- Clean and modern UI design
- Responsive layout that adapts to different screen sizes
- Form validation with visual feedback
- Custom styling for form inputs and buttons
- Semi-transparent overlay for logo section
- Credit attribution for background image
- Custom font implementation (Norse Bold for logo)

## Technologies Used

- HTML5
- CSS3
  - CSS Variables (Custom Properties)
  - Flexbox
  - Media Queries
  - Pseudo-classes
  - CSS Transitions
- External Fonts (Norse Bold)

## Project Structure

```
Sign-up-Form/
├── assets/
│   ├── background-img.jpg
│   └── logo.png
├── index.html
├── style.css
└── README.md
```

## Implementation Details

### Form Validation
- Password requirements:
  - Minimum 8 characters
  - At least one uppercase letter
  - At least one lowercase letter
  - At least one number
  - At least one special character
- Email validation
- Phone number validation
- Name validation (letters only, minimum 2 characters)

### Styling Features
- Custom color scheme using CSS variables
- Responsive design with mobile breakpoints
- Input states:
  - Default: Light border (#E5E7EB)
  - Focus: Blue border with subtle box shadow
  - Invalid: Red border
  - Valid: Green border
- Semi-transparent overlay for logo section
- Custom button styling with hover effects

### Responsive Design
- Desktop: Split layout with background image
- Mobile: Stacked layout with adjusted dimensions
- Breakpoint: 768px

## Credits

- Background Image: Photo by [Joshua Earle](https://unsplash.com/photos/a-train-rolls-through-the-busy-city-railroad-tracks-4aR04Hkahhk) on [Unsplash](https://unsplash.com/)
- Font: Norse Bold from [CDN Fonts](https://fonts.cdnfonts.com/css/norse)

## Future Improvements

- Add JavaScript validation for matching passwords
- Implement form submission functionality
- Add loading states for form submission
- Enhance mobile responsiveness
- Add dark mode support

## Setup

1. Clone the repository
2. Open `index.html` in your browser
3. No build process required - it's a static website

## License

This project is part of The Odin Project curriculum and is created for educational purposes.