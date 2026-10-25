| Field | Value |
| :--- | :--- |
| Repository URL | https://github.com/bkj05/cse134b-hw3 |
| Part 1 Deployed URL | https://bkj05-cse134b-hw3.netlify.app/part1/cheese.html |
| Part 2 Deployed URL | https://bkj05-cse134b-hw3.netlify.app/ |

# CSE134B HW3 - Benjamin Kettor Jr.

Status: the HW3 source is in this repository. A new Netlify deployment is still
needed. The deployed URLs in the table use the intended new project name;
confirm them after deployment before submitting the repository link.

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
- The portfolio's internal links and local assets resolve.

## Checks to finish before submission

- Check all seven pages with CSS enabled and disabled.
- Check Home and Contact at approximately 375px and 1280px wide.
- Use Tab to check visible keyboard focus through navigation and form controls.
- Confirm the live URLs and committed files match the new deployment.

Do not submit until the pending setup and browser checks are complete.
