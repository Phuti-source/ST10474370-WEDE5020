# ST10474370-WEDE5020
POE PART 2

# Pretty Crown Barber & Beauty Salon Website

# 1. Project Overview
This repository contains the source code for the **Pretty Crown Barber & Beauty Salon** website, a business based in Polokwane, Limpopo. The website was developed as part of the WEDE5020 Portfolio of Evidence (POE) and is built using **HTML5** for structure and content, and **CSS3** for styling and responsive design.

The purpose of the website is to give the salon an online presence where customers can view the services offered, learn about the business, send enquiries, and find contact details.

# 2. Business Description
Pretty Crown Barber & Beauty Salon is a grooming and beauty destination offering a range of hair and beauty services, including:
- Hair colouring and relaxing
- Natural hair treatments (deep conditioning, scalp hydration, wash and blow-dry, dreadlocks maintenance)
- Manicures and pedicures
- General barbering and beauty services

# 3. Website Pages
The website consists of the following five pages, all linked through a shared navigation menu:

| Page      | File Name      | Description                                                                    |
|-----------|----------------|--------------------------------------------------------------------------------|
| Home      | `index.html`   | Landing page introducing the salon and its brand                               |
| About Us  | `about.html`   | Background information, history, and mission of the salon                      |
| Services  | `services.html`| A full list of services offered, each with an image and description            |
| Enquiry   | `enquiry.html` | A form for customers to enquire about services or make booking requests        |
| Contact Us| `contact.html` | A direct contact form for general messages, along with business contact details|

# 4. Technologies Used
- **HTML5** – used for the structure and content of all pages
- **CSS3** – used for styling, layout, and responsive design
- No external frameworks or libraries were used; the styling was written from scratch to keep the project lightweight and fully understood by the developer

# 5. File Structure

project-root/
│
├── index.html
├── about.html
├── services.html
├── enquiry.html
├── contact.html
├── style.css
├── Mypictures/
│   ├── hairdressingmenandwomen.jpg
│   ├── hairdye.jpeg
│   ├── naturalblow.jpeg
│   ├── redgelnails.jpg
│   └── (additional service and favicon images)
└── README.md

# 6. Styling Approach
All visual styling is contained in a single **external stylesheet**, `style.css`, which is linked to every HTML page inside the `<head>` section using:
html
<link rel="stylesheet" href="style.css">

No inline styling or internal `<style>` blocks are used anywhere on the website. Keeping all styling in one external file means that any design change only has to be made once and will automatically apply across the whole site, in line with good web development practice.

# 7. Design and Colour Scheme
A colour palette was chosen to reflect the identity of a premium barber and beauty salon:

-----------------------------------------------------------------
| Color          | Use                                          |
|----------------|----------------------------------------------|
| Deep Plum      | Header, footer, and heading text             |
| Gold           | Buttons, hover effects, borders, and accents |
| Soft Blush Pink| Background for the enquiry and contact forms |
| Ivory          | General page background                      |
| Charcoal       | Body text                                    |

Typography uses a decorative serif-style font for headings to give the brand an elegant feel, paired with a clean sans-serif font for body text to keep the content easy to read.

# 8. Layout Techniques
- **Flexbox** is used to arrange the navigation menu links neatly in a row.
- **CSS Grid** is used to arrange the service cards on the Services page into clean, evenly spaced columns.

# 9. Interactive and Visual Styling
- Service cards and forms include borders, rounded corners, and soft shadows for a card-like appearance.
- `:hover`, `:focus`, and `:active` pseudo-classes are used on navigation links, buttons, and form fields to give users clear visual feedback when interacting with the site.

# 10. Responsive Design
The website has been designed to work across desktop, tablet, and mobile devices using **media queries** and **relative units** (`rem` and `%`):

- **Desktop (default view):** Services display in a three-column grid; navigation links display in a horizontal row.
- **Tablet (screens up to 1024px):** Services reduce to a two-column grid.
- **Mobile (screens up to 600px):** Services display in a single column, the navigation menu stacks vertically, heading sizes reduce, and buttons expand to full width for easier tapping.

Images on the Services page also use the `srcset` and `sizes` attributes so that an appropriately sized image is loaded depending on the user's screen size, improving load times on mobile devices.

# 11. How to View the Website
1. Download or clone the repository.
2. Ensure the `style.css` file and the `Mypictures` folder remain in the same location relative to the HTML files.
3. Open `index.html` in any modern web browser to view the website.

# 12. Testing
The website was tested using browser developer tools to confirm correct display and functionality across a desktop, and a mobile screen sizes. Screenshot evidence of this testing is included separately as part of the assignment submission.

# 13. Changelog
All updates made to the website, including corrections from Part 1 feedback and the CSS styling additions in Part 2, are recorded in the project changelog, which lists the date, description, and reason for each change.

# 14. Author
Phuti Moketla ST10474370

# 15. Acknowledgements
Developed as part of the WEDE5020 module requirements for the Web Design and Development course.
