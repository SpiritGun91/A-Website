# Photography Portfolio Website Planning

## Site Theme
A personal photography portfolio showcasing nature, urban, and portrait photography collections with a contact form for potential clients.

## Color Palette
- Primary background: #f5f5f5 (off-white)
- Header background: #2c3e50 (dark blue-gray)
- Text color: #333333 (dark gray)
- Accent color: #27ae60 (green)
- Secondary accent: #e74c3c (red)

## Typography
- Headers: 'Montserrat', sans-serif
- Body text: 'Open Sans', sans-serif

## Page Layouts

### Page 1: Home

#### Elements:
- Navigation Bar (nav)
  - Class: main-nav
- Header (h1)
  - Class: page-title
  - Content: "Nature Through My Lens"
- Section 1 (section)
  - Class: intro-section
  - H2: "Welcome"
  - Content: Introduction to the portfolio
- Section 2 (section)
  - Class: about-section
  - H2: "About Me"
  - Content: Brief biography
- Section 3 (section)
  - Class: philosophy-section
  - H2: "My Philosophy"
  - Content: Photography approach and style
- Featured Image (img)
  - Class: hero-image
  - Alt text: "Sunset over mountain range"

### Page 2: Contact

#### Elements:
- Navigation Bar (nav)
  - Class: main-nav
- Header (h1)
  - Class: page-title
  - Content: "Get In Touch"
- Form (form)
  - Class: contact-form
  - Fieldset:
    - Legend: "Contact Information"
    - Input 1: Name (text)
      - Label: "Your Name"
      - Class: form-input
    - Input 2: Email (text)
      - Label: "Email Address"
      - Class: form-input
    - Input 3: Newsletter (checkbox)
      - Label: "Subscribe to newsletter"
      - Class: form-checkbox
    - Textarea: Message
      - Label: "Your Message"
      - Class: form-textarea
    - Button: Submit
      - Class: submit-button
      - Content: "Send Message"

### Page 3: Resources

#### Elements:
- Navigation Bar (nav)
  - Class: main-nav
- Header (h1)
  - Class: page-title
  - Content: "Photography Resources"
- Unordered List (ul)
  - Class: resource-links
  - 5 List items with links to external photography websites
    - Class: resource-item

### Page 4: Gallery

#### Elements:
- Navigation Bar (nav)
  - Class: main-nav
- Header (h1)
  - Class: page-title
  - Content: "Photo Gallery"
- Gallery Container (div)
  - Class: gallery-container
  - 6 Image containers (div)
    - Class: gallery-item
    - Each containing:
      - Image (img)
        - Class: gallery-image
      - Label (p)
        - Class: image-label
