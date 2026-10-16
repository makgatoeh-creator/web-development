# Apex Bakery Website

## Project Overview
## Student Information
* Full Name: Elelwani Makgato
* Student Number: ST10538946
* Module: WEDE5020 (Web Development - POE Part 1)
* Institution: Rosebank College

## Website Goals and Objectives
* Provide an online platform for Apex Bakery to showcase products and bakery services.
* Allow customers to make online enquiries and request custom cake orders.
* Help visitors easily locate physical store branches using an embedded Google Map.

Apex Bakery is a multi-page website created for a local bakery business. The website provides information about the bakery, its products and services, and allows visitors to make enquiries or contact the bakery.

The website is built using **HTML5 and CSS3** and uses a shared stylesheet across all pages. It also includes bakery-related images and an embedded Google Maps location.

## Features

The website includes:

* Home page with a welcome section and bakery image
* About Us page containing:

  * Company story
  * Mission and vision
  * Team information
* Products and Services page
* Product and Custom Order Enquiry form
* Contact Us page containing:

  * Branch information
  * General contact form
  * Embedded Google Maps
* Consistent navigation across all pages
* Responsive viewport configuration for different screen sizes
* Shared CSS styling
* Bakery-themed background imagery
* Image styling with borders, shadows, and rounded corners

## Website Pages

### 1. Home

**File:** `index.html`

The home page introduces Apex Bakery and contains:

* Bakery name and tagline
* Navigation menu
* Welcome message
* Image of freshly baked bread
* Short description of the bakery
* Link to the Products and Services page
* Reasons for choosing Apex Bakery
## Timeline and Milestones
* *Phase 1:* Planning, site map layout, and wireframing.
* *Phase 2:* HTML5 core structure creation for all 5 web pages.
* *Phase 3:* CSS styling, responsive menu navigation, and layout adjustments.
* *Phase 4:* Part 1 submission and repository documentation.

## Part 1 Details
* This submission covers **Part 1** of the Portfolio of Evidence (POE). 
* (Note: Part 2 and Part 3 features and enhancements will follow in future submissions/edits).

## Sitemap
* Home (`index.html`)
* About Us (`about.html`)
* Products & Services (`services.html`)
* Custom Enquiry (`enquiry.html`)
* Contact Us (`contact.html`)

### 2. About Us

**File:** `about.html`

The About Us page provides information about:

* The history of Apex Bakery
* The bakery's mission
* The bakery's vision
* Members of the bakery team

### 3. Products & Services

**File:** `services.html`

This page describes the main products and services offered by Apex Bakery:

* Fresh bread

  * Sourdough
  * Wholewheat
  * White loaves
* Custom cakes
* Catering services

### 4. Product Enquiry

**File:** `enquiry.html`

The enquiry page contains a form for customers interested in:

* Custom cakes
* Event catering
* Bulk bread orders

The form collects:

* Full name
* Email address
* Selected product/service
* Enquiry details

### 5. Contact Us

**File:** `contact.html`

The Contact Us page provides information about two bakery branches and includes:

* Main branch address and telephone number
* Suburban branch address and telephone number
* General contact form
* Embedded Google Maps showing the Suburban Mall location in Polokwane

## Project Structure

```text
Apex Bakery Website/
│
├── index.html
├── about.html
├── services.html
├── enquiry.html
├── contact.html
│
├── css/
│   └── style.css
│
└── assets/
    ├── Custom Cakes.jpg.jpeg
    ├── Image 7.jpg.jpeg
    ├── Image 8.jpg.jpeg
    ├── Sourdough  #bergbakes #bread #sourdoogh #baking.jpg.jpeg
    ├── White Loaves.jpg.jpeg
    └── Wholewheat.jpg.jpeg
```

## Technologies Used

### HTML5

HTML5 is used to create the structure and content of the website, including:

* Semantic page sections
* Navigation
* Headings and paragraphs
* Images
* Forms
* Lists
* Articles
* Embedded map

### CSS3

CSS is used for the visual design and layout of the website.

The stylesheet includes:

* Typography
* Background images
* Transparent backgrounds
* Navigation styling
* Hover and focus effects
* Rounded corners
* Image sizing and cropping
* Borders and shadows
* Page spacing and layout
* Responsive navigation wrapping

The shared stylesheet is located at:

```text
css/style.css
```

## Navigation

All pages use the same navigation menu:

* Home
* About Us
* Services
* Enquiry
* Contact Us

The navigation links allow visitors to move between the different sections of the website.

## Images and Assets

The `assets` folder contains the bakery images used by the project.

The home page displays `Image 8.jpg.jpeg`, while `Image 7.jpg.jpeg` is used as the main website background through the CSS stylesheet.

Other bakery images are included in the assets folder for use within the project.

## Forms

The website contains two types of forms.

### General Contact Form

Located on `contact.html`.

The form collects:

* Name
* Email address
* Message

### Product & Custom Order Enquiry Form

Located on `enquiry.html`.

The form collects:

* Full name
* Email address
* Product/service selection
* Enquiry details

Both forms currently use:

```html
action="#"
method="post"
```

This means the project provides the front-end form interface, but no server-side form-processing system is included in the current project.

## Google Maps

The Contact Us page contains an embedded Google Maps iframe for:

**45 Park Drive, Suburban Mall, Polokwane**

The map is embedded directly into `contact.html`.

## Styling

The website uses a bakery-themed visual design with:

* A full-page background image
* Semi-transparent dark content sections
* White/light text
* Rounded navigation buttons
* Rounded image borders
* Drop shadows
* Hover effects on navigation links

The navigation is also configured to wrap onto multiple lines when necessary, helping it accommodate smaller screen widths.
## Changelog
* **v1.0 (October 2026):** Completed initial HTML/CSS implementation and POE Part 1 documentation.

## References
* World Wide Web Consortium (W3C), 2023. *HTML5 Specification*. Available at: <https://www.w3.org/TR/html52/> [Accessed 16 October 2026].
* MDN Web Docs, 2026. *CSS: Cascading Style Sheets*. Mozilla. Available at: <https://developer.mozilla.org/en-US/docs/Web/CSS> [Accessed 16 October 2026].
