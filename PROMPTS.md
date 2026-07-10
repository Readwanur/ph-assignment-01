
> # Basic prompt to generate the better prompt
>
>I am creating a single page website using HTML5 and CSS. It's named "DevConf2026". Now, I am giving you a basic structure of the page:
>A navbar with logo on the left, Tabs on the center and a Register Now button on the right.
>Then the Hero section with darkish Background image and some heading on top of it and a Register Now button. Then there is Meet the speakers part that has 2x2 grid with speakers name, role, company etc. with a picture of the speakers. After that there is Secure Your spot that has 3 pricing cards with a highlighted card. And finally footer section. 
>Now, I want you to generate me a section between the "Secure your spot" and "footer" section relevant with the current website theme and it's context. for example Sponsors, Venue, FAQ, Newsletter Signup, Hackathon Details, Past Highlights, Job Board or anything relevant to the website.The theme of the website is:
>
>1. Highlighted pricing card bg: #0D1B2A
>2. common buttons bg: #1D4ED8
>3. overall bg of website: white
>4. font-family: Inter 
>
>give me more quality prompt for this so that i can generate a html, css code for the design from chatgpt

> # Main Prompt
>
> **Act as a Senior UI/UX Designer and Professional Frontend Developer.**
>
> I am building a modern, single-page conference website called **"DevConf2026"** using only **HTML5 and CSS3** (no JavaScript).
>
> The website already contains these sections in order:
>
> 1. Navbar
> 2. Hero
> 3. Meet the Speakers
> 4. Secure Your Spot (Pricing)
> 5. *(Your task is to create this new section)*
> 6. Footer
>
> **Create a new section titled:**
>
> **Sponsors & Frequently Asked Questions**
>
> This section should feel like a natural continuation of the website and help convince visitors to register before they reach the footer.
>
> **Part 1 — Sponsors**
>
> Design a clean **Sponsors** section with:
>
> * Heading: **Supported by Industry Leaders**
> * Short subtitle
> * Responsive CSS Grid
> * 6 dummy sponsor cards
> * Each card should contain:
>
>   * Placeholder logo (text only)
>   * Company name
>   * Sponsor tier (Gold / Silver)
> * Cards should have:
>
>   * subtle border
>   * rounded corners
>   * hover elevation
>   * no gradients
>   * equal spacing
>
> **Part 2 — FAQ**
>
> Create a beautiful FAQ section underneath the sponsors.
>
> Requirements:
>
> * Heading
> * Short description
> * 5 realistic developer conference questions
> * Use semantic HTML
> * Use `<details>` and `<summary>`
> * No JavaScript
> * Style the accordion so it looks modern
> * Smooth hover effects
> * Clear spacing
> * Visible focus states
>
> Example questions:
>
> * Who should attend DevConf2026?
> * What's included in my ticket?
> * Will sessions be recorded?
> * Can I transfer my ticket?
> * Are student discounts available?
>
> **Design System**
>
> Typography
>
> * Font Family: **Inter**
>
> Colors
>
> * Website Background:
>
>   * `#FFFFFF`
> * Primary Color:
>
>   * `#1D4ED8`
> * Dark Text / Headings:
>
>   * `#0D1B2A`
> * Secondary Text:
>
>   * `#6B7280`
> * Borders:
>
>   * `#E5E7EB`
>
> **Style Guidelines**
>
> The website should look like a modern conference landing page similar to Stripe, Vercel, GitHub, or Linear.
>
> Use:
>
> * Minimalist layout
> * Plenty of whitespace
> * Rounded corners (12–16px)
> * Flat colors only
> * No gradients
> * No glassmorphism
> * No neumorphism
> * Soft shadows
> * Clean typography hierarchy
> * Consistent spacing
> * Smooth hover transitions (200–300ms)
>
> **Responsive Requirements**
>
> Desktop:
>
> * Sponsors in a 3-column grid
> * FAQ full width
>
> Tablet:
>
> * Sponsors in 2 columns
>
> Mobile:
>
> * Everything becomes a single column
> * Comfortable spacing
> * Touch-friendly sizing
>
> **Code Requirements**
>
> * Semantic HTML5 only
> * CSS3 only
> * No Bootstrap
> * No Tailwind
> * No JavaScript
> * Use Flexbox and CSS Grid where appropriate
> * Write clean, readable, and well-commented code
> * Organize CSS into logical sections
> * Use meaningful class names
> * Avoid unnecessary wrappers
>
> **Output Format**
>
> 1. HTML (single code block)
> 2. CSS (single code block)
>
> The final result should look polished enough to be included in a professional portfolio project.
 