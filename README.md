| Field | Value |
| :--- | :--- |
| Repository URL | https://github.com/bkj05/cse134b-hw3 |
| Part 1 Deployed URL | https://bkj05-cse134b-hw3.netlify.app/part1/cheese.html |
| Part 2 Deployed URL | https://bkj05-cse134b-hw3.netlify.app/ |

# CSE134B HW3 - Benjamin Kettor Jr.

Deployed on Netlify. The links in the table are confirmed live. The remaining
manual browser checks are listed below.

## Structure

- Portfolio: `index.html`, `about.html`, `projects.html`, `beyond-coding.html`,
  `contact.html`, and `experiments.html` at the repository root.
- Shared portfolio stylesheet: `assets/styles.css`.
- Cheese exercise: `part1/cheese.html` and `part1/cheese.css`.
- Netlify publishes the repository root. No build command or framework is used.

## Design choices

The existing client-focused portfolio uses an off-white background, dark text,
blue links, serif headings, and a system font stack for body text. Shared color,
typography, and layout decisions use CSS custom properties. Desktop navigation
uses Flexbox; on narrow screens it becomes a two-column Grid. Home and Contact
use two-column layouts that collapse to one column. All navigation stays visible
without a scripted menu.

## Scope

Copied from HW2 Part 2. HW2's repository and Netlify site are left unchanged.
HTML changes are limited to shared stylesheet links, page classes, the skip-link
class, and moving the existing embedded custom-element CSS into the external
stylesheet. No framework, custom font download, interaction, or JavaScript is
added. The two small pre-existing HW2 canvas and console demonstrations are
retained without modification.

## Checks completed

- The supplied cheese HTML is unchanged apart from the external stylesheet link.
- All seven HTML pages and both stylesheets pass Nu HTML Checker validation.
- The supplied cheese article produces one heading warning. Its original markup
  is retained because the assignment permits only adding the stylesheet link.
- All seven deployed pages, both stylesheets, and referenced local assets load.
- The deployed HTML also has zero validation errors and the same single warning.
- Deployed stylesheets and assets match the committed files. Netlify rewrites
  portfolio links to extensionless URLs; page content and markup otherwise match.
- All seven pages were checked with CSS enabled in Chrome at a 1363px viewport,
  with no page-wide horizontal scrolling.
- Tab navigation shows visible focus through the portfolio navigation, Contact
  fields, and the cheese page's checkboxes, text input, button, and link.

## Manual checks to finish before submission

- Check Home and Contact at approximately 375px and 1280px wide. Confirm that
  content fits, navigation remains accessible, and controls are usable.
- Disable CSS and check all seven pages for readable content, usable links,
  controls, and a meaningful reading order; then re-enable CSS.

These checks are still pending; the desktop checks above do not establish
mobile behavior or CSS-disabled usability.
