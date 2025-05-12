  <img src="assets/readme-images/code-institute-img.png" alt="Code Institute Project" width="250">

  <br>
  <br>

<h1 align="center">
  <img src="assets/favicons/favicon-96x96.png" width="28" style="vertical-align: middle; margin-right: 8px;" />
  Milestone Project 1: Heat
</h1>

<h3 align="center">
  <em><strong>A static website created for my band, designed to showcase our music, share upcoming events, and engage with our audience. Developed as part of the User Centric Frontend Development Milestone Project at Code Institute.</strong></em>
</h3>

<br>
<br>

## 👉 [Heat Website](https://drake-designer.github.io/Heat/)

![HEAT Project Intro Pic](assets/readme-images/website-intro.png)

<br>
<br>

## Table of Contents

1. ### [Project Overview](#project-overview) 📄
2. ### [User Experience Design](#user-experience-design) 🎯
   - #### [User Stories](#user-stories) 🧠
   - #### [Structure](#structure) 🧱
   - #### [Design](#design) 🎨
     - ##### [Wireframes](#wireframes) 🗺️
     - ##### [Colour Palette](#colour-palette) 🎨
     - ##### [Typography](#typography) ✍️
3. ### [Features](#features) ✨
4. ### [Technologies Used](#technologies-used) 🛠️
   - #### [Favicon Creation & Integration](#favicon-creation--integration) 🖼️
5. ### [Testing & Bug Fixes](#testing--bug-fixes) 🧪
6. ### [Deployment](#deployment) 🚀
7. ### [Credits](#credits) 🙏

---

## Project Overview

### Intro

Welcome to the official website of Heat: we are a group of friends who play fun and groovy dance-funk music. Our sound is inspired by bands like Daft Punk, Chromeo and Franc Moody.. full of energy, rhythm and good vibes!

We started this band for the love of music and performing live gigs. Over time, we’ve played in local venues, recorded our songs, and grown closer as a team. I made this website to share our music with more people, show where we’re playing next, and make it easy for anyone to book us for a show.

Whether you want to listen, learn more about us, or come see us live: this is the right place!

### Scope

I have built this website as my first Milestone Project 1 for the Full Stack Web Development course at Code Institute. The idea was to create something real and personal, so I have choses to build a site for my band, Heat.

The main goal of this website is to help more people discover our music, check out our upcoming gigs, and get in touch if they want to book a ticket for a gig. Whether you're a fan, a curious listener, or someone looking to book a band, this site is the place to find everything about Heat.

The site gives visitors a clear idea of who we are, what kind of music we play, and where they can see us live. It also allows fans and event organizers to book us directly.

The site includes the following core features:

- A short introduction about the band

- A Music and Video section where users can listen to some of our songs and watch a few live performance clips

- A Photo Gallery to showcase pictures made during our gigs

- A section for Upcoming Gigs, where users can check where and when we’re playing next

- A Contact page to reach out for questions, messages, or booking requests

These features make sure that users can learn about us, enjoy our content, and easily reach out to us.

## User Experience Design

### User Stories

- As a new visitor, I want to learn what kind of music the band plays, so I can decide if I like their style

- As a fan, I want to see upcoming gigs, so I can plan to attend their live shows

- As someone interested in booking the band, I want to find contact details or a booking button easily

- As a curious user, I want to explore photos and videos of past performances, so I can see what the live vibe is like

- As a music lover, I want to listen to samples or clips of the band’s original songs

- As a mobile user, I want the site to be easy to use on my phone or tablet

### Structure

The website has one main index page that includes three key sections, plus two extra pages:

#### Heat (Home)

The homepage is made up of three sections that visitors can easily access through the navbar:

- **The Band** – A short introduction about who we are, how we started, and the kind of music we play
- **Music** – A section where users can listen to some of our original songs and watch live performance videos
- **Gallery** – A photo section with snapshots from our gigs

These sections are all part of the same page and use anchor links to scroll smoothly to the right spot.

#### Upcoming Gigs

This page displays a list of our upcoming concerts, with details like the date, venue name, and location. At the top of the page (in the header), there’s a **"Book your spot!"** modal button that allows users to reserve tickets for future gigs.

I decided to place the button only in the header and used `visibility: hidden` to hide it from the navbar, so it wouldn’t appear twice.

#### Contact

A simple contact page with a message form and our contact info, so people can easily reach out for bookings, questions, or just to say hello.

> The entire site is fully responsive and works well on all screen sizes. The layout is clear, friendly, and reflects the fun personality of the band.

## Design

#### Wireframes

To plan the layout of my website, I used [Balsamiq](https://balsamiq.com/) to create wireframes for different screen sizes. This helped me decide where to place key elements like the logo, navbar, hero image, and text sections.

I made four wireframes, each showing how the site should look on different devices:

- **Desktop**
- **iPad**
- **iPhone SE**
- **Samsung Galaxy S20 Ultra**

Each wireframe includes the same features:

- A simple navbar with links
- A hero section with text and image
- A short band description
- An image carousel

These designs helped me make sure the site looks good and works well on both desktop and mobile devices.

![Wireframes part 1](assets/readme-images/wireframes/wireframe-1.png)

![Wireframes part 2](assets/readme-images/wireframes/wireframe-2.png)

#### Colour Palette

For this project, I decided to create a custom colour palette by manually picking colours from one of our band photos.

I used an online image color picker to extract the main tones directly from a live performance picture. This helped me build a palette that really feels connected to our style, our stage lights, and the atmosphere of our gigs.

Here are the colours I chose:

```css
/* Colour Palette */
--color-button-accent: #1a75cf; /* Deep blue used for buttons with improved text readability */
--color-border: #26050a; /* Deep burgundy – used for borders and small accents */
--color-navbar-background: #4d2829; /* Rich dark red – used as the main navbar background */
--color-main: #0d0c18; /* Nearly black – used as the main page background */
--color-logo: #ea40e6; /* Bright purple – used in the logo for contrast and pop */
```

![Colour Picker with Photo](assets\readme-images\colour-palette\colour-palette-1.png)

![Custom Colour Palette](assets\readme-images\colour-palette\colour-palette-2.png)

#### Typography

For this project, I used a combination of four different [Google Fonts](https://fonts.google.com/) to give the website a modern, clean, and slightly 'funky' style.

Each font was picked for a specific role:

- **Montserrat** – Used as the main body font for most text content
- **Open Sans** – Used for extra readability where needed
- **Saira Condensed** – Used in headings for a bold and sharp look
- **Audiowide** – Used only for the logo, to give it a unique and musical feel

All fonts are imported from Google Fonts and declared as custom variables in the `:root` selector for easier management across the site.

```css
/* Google Fonts ---> Montserrat + Open Sans + Saira Condensed + Audiowide */

@import url('https://fonts.googleapis.com/css2?family=Audiowide&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Open+Sans:ital,wght@0,300..800;1,300..800&family=Saira+Condensed:wght@100;200;300;400;500;600;700;800;900&display=swap');

/* Typography */
:root {
  --font-primary: 'Montserrat', sans-serif;
  --font-secondary: 'Open Sans', sans-serif;
  --font-headings: 'Saira Condensed', sans-serif;
  --font-logo: 'Audiowide', cursive;
}
```

---

## Features

This website includes the following key features:

- **Fully responsive layout** – Works smoothly on desktop, tablet, and mobile devices
- **Anchor-based navigation** – The homepage uses anchor links to scroll between sections
- **Embedded audio players** – Visitors can listen to our original songs directly on the site
- **Live performance videos** – Watch us in action with video clips from past gigs
- **Photo gallery** – A collection of images from our shows
- **Upcoming gigs section** – A dedicated page listing future shows with dates and venues
- **"Book your spot!" modal button** – A call-to-action to reserve tickets for upcoming concerts
- **Contact form** – Simple form to get in touch for bookings or questions
- **Custom favicon and logo** – Designed to reflect our style and brand
- **Dark theme with custom colour palette** – Inspired by the lights and mood of our live shows
- **Clean, modern typography** – Using a mix of Google Fonts for headings, text, and logo

---

## Technologies Used

This project was built using the following tools and technologies:

- [**HTML5**](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) – For structuring the content of the pages
- [**CSS3**](https://developer.mozilla.org/en-US/docs/Web/CSS) – For styling the layout, colours, fonts, and responsiveness
- [**Bootstrap 5**](https://getbootstrap.com/) – For responsive design and reusable components like navbar, grid, and buttons
- [**GitHub**](https://github.com/) – For version control and project hosting via GitHub Pages
- [**Visual Studio Code**](https://code.visualstudio.com/) – The main code editor used during development

Design & Media Tools:

- [**Balsamiq**](https://balsamiq.com/) – Used to create wireframes for different screen sizes
- [**Google Fonts**](https://fonts.google.com/) – For importing and using custom fonts like Montserrat, Audiowide, etc.
- [**RealFaviconGenerator**](https://realfavicongenerator.net/) – Used to generate a full set of favicons for multiple devices \*
- [**Squoosh**](https://squoosh.app/) – For compressing and optimizing images for faster load times. I used Squoosh to reduce the file size of all images without losing quality. This helped the website load faster, especially on mobile devices. I mostly exported images as `.webp` format and adjusted compression to balance quality and performance.

- [**HandBrake**](https://handbrake.fr/) – Used to compress and convert video files into web-friendly formats. I used HandBrake to reduce the file size of my video clips while keeping good quality. This helped improve page load time without losing the vibe of our live performances.

- [**Online Audio Converter**](https://online-audio-converter.com/) – To convert audio files into `.mp3` format for the music section. I used this online tool to convert `.wav` files into high-quality `.mp3` at 320 kbps, which helped reduce file size while keeping good sound quality.

### \*Favicon Creation & Integration

To create a full set of favicons compatible with all major platforms (desktop, Android, iOS), I have used the online tool [RealFaviconGenerator](https://realfavicongenerator.net).

**Steps:**

1. Uploaded the custom Heat logo.
2. Used default settings for modern browser and mobile support.
3. Extracted files into `assets/favicons/`.
4. Added the generated `<link>` tags to the `<head>` of `index.html`.

<br>

![Favicon Generator Preview 1](assets/readme-images/favicon/favicon-1.png)

![Favicon Generator Preview 2](assets/readme-images/favicon/favicon-2.png)

![Favicon Generator Preview 3](assets/readme-images/favicon/favicon-3.png)

## Testing & Bug Fixes

### ❌ Bug #1 – Anchor links didn't scroll correctly to the right section

When clicking on the navigation links like "The Band", "Music", or "Gallery", the scroll did not work properly. Sometimes the section was too high and hidden behind the navbar, and other times it was too low.

This problem made the site feel broken, especially on small screens or when using the mobile menu. It was hard to understand what caused it. I lost almost a full day trying different ideas and also contacted Tutor Support for help.

In the end, the solution was very simple. I added the following CSS to give the body and section elements enough padding from the top, equal to the height of the navbar (72.89px):

body {
padding-top: 72.89px;
}

section {
padding-top: 72.89px;
}

📸 Screenshots – Before the Fix

![The Band anchor bug](assets/readme-images/bugs/bug-1.png)
![Music anchor bug](assets/readme-images/bugs/bug-2.png)
![Gallery anchor bug](assets/readme-images/bugs/bug-3.png)

📸 Screenshots – After the Fix

![The Band anchor fixed](assets/readme-images/bugs/bug-4.png)
![Music anchor fixed](assets/readme-images/bugs/bug-5.png)
![Gallery anchor fixed](assets/readme-images/bugs/bug-6.png)

### ❌ Bug #2 – Low colour contrast in some areas

While working on the site, I noticed that some text and buttons were not easy to read because the colours didn’t have enough contrast. This was more noticeable on small screens or in dark environments.

To check and fix this, I used [Contrast Grid](https://contrast-grid.eightshapes.com/) to test all the colours I used. This tool helps make sure that text is easy to read and follows the [WCAG 2.0](https://www.w3.org/TR/WCAG20/) accessibility rules.

Here is the result of the test:

![Contrast Grid](assets\readme-images\contrast-grid\contrast-grid.png)

✅ Most colour combinations passed the test (like the bright blue on dark backgrounds)

⚠️ A few very dark combinations didn’t pass, but I only used those in places without text

Thanks to this test, I made sure the important parts of the site are clear and easy to read for everyone.

### ❌ Bug #3 – Low contrast on main button (accessibility issue)

While testing the site for accessibility using the WAVE evaluation tool and the WebAIM Contrast Checker, I noticed that the main call-to-action buttons (like "Book your spot!") didn’t have enough contrast between the background color and the white text.

The original CSS value for the button color was:

```css
--color-button-accent: #00a7e8; /* Bright electric blue */
```

Although this color looked visually nice, it had a contrast ratio of 2.72:1, which is below the minimum required by WCAG 2.1 accessibility standards (4.5:1 for normal text). This made it harder to read for users with vision impairments or when viewing the site in low-light conditions.

🛠️ Fix:

To solve this, I updated the color to a darker and more accessible shade of blue:

```css
--color-button-accent: #1a75cf; /* Accessible blue – ensures good contrast */
```

This new color gives a contrast ratio of 4.61:1, which passes WCAG AA requirements and makes the text on buttons easier to read on all devices and for all users.

📸 Before the fix:

📸 After the fix:

## Deployment

The website was deployed early in the project, right after the home page (HTML and CSS) was set up and tested.

Deployment was done using **GitHub Pages**, directly from the `main` branch of the repository.

### 🌐 Live Site

You can view the live project here:  
👉 [https://drake-designer.github.io/Heat/](https://drake-designer.github.io/Heat/)

### 🔧 How Deployment Was Done

1. Opened the GitHub repository for the project
2. Clicked on the `Settings` tab at the top of the page
3. From the sidebar on the left, selected the **Pages** section
4. In the **Branch** section:
   - Chose `main` as the source
   - Selected `/ (root)` as the folder
5. Clicked **Save**
6. After a few seconds, GitHub provided a live link to the deployed site

---

### 💻 How to Clone This Repository Locally

If you'd like to clone this project and work on it locally, follow these steps:

1. Go to the repository page:  
   👉 [https://github.com/drake-designer/Heat](https://github.com/drake-designer/Heat)

2. Click the green **Code** button

3. Copy the URL shown (it should look like `https://github.com/username/repo-name.git`)

4. Open your terminal and change directory to where you want to store the project

5. Type the following command and press Enter:
   ```bash
   git clone https://github.com/drake-designer/Heat.git
   ```

## Credits
