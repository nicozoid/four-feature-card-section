# Four card feature section

**[View live solution](https://nicozoid.github.io/four-card-feature-section)**

This is a solution to a [challenge](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK) on Frontend Mentor.

Built with hand-coded CSS & HTML. No AI. *(Consciously restricting myself to aid my learning).*

### What I learned
- If a figma frame is very simple, consistening of just two child elements, it's often simpler just to scrap it and use margins on the children instead (the same could also be done in Figma itself)
- `position: absolute` is the equivalent of "ignore auto-layout" (I used this for positioning the coloured top borders on the cards). Need to remember that the parent elements must be `position: relative`.
- I used CSS Grid for the first time. Felt like a bit of a slog to get it to do what I want; probably because it's not the standard Figma layout system. However I only introduced Grid after starting the responsive elements, so I suspect it will feel easier if I plan to use it from the start.

### Slightly-refined process
*(Work on mobile design only until final stage)*
1. Create HTML — should correspond with Figma frame hierarchy
1. Create empty CSS classes corresponding with the frames, using BEM naming system
1. Create variables (e.g. color, spacing)
1. Text styles: define classes, add to html, import fonts
1. Define layout/style of all CSS classes
1. Define hover states and transitions
1. Adjust the CSS as needed for tablet and desktop