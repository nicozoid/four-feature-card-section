# Four card feature section

**[View live solution](https://nicozoid.github.io/four-card-feature-section)**

This is a solution to a challenge of the same name on [Frontend Mentor](https://www.frontendmentor.io/home).

Built with hand-coded CSS & HTML. No AI. *(Consciously restricting myself to aid my learning).*

### What I learned
if a figma frame is very simple, consistening of just two child elements, it's often simpler just to scrap it and use margins on the children instead (could also be done in Figma itself)
- the equivalent of "ignore auto-layout" (used for positioning the coloured top borders on the card). Need to remember that the parent elements must be `position: relative`.
- `align-self: flex-end` is a nice way to quickly refine elements

### Slightly-refined process
*(Work on mobile design only until final stage)*
1. Create HTML — should correspond with Figma frame hierarchy
1. Create empty CSS classes corresponding with the frames, using BEM naming system
1. Create variables (e.g. color, spacing)
1. Text styles: define classes, add to html, import fonts
1. Define layout/style of all CSS classes
1. Define hover states and transitions
1. Adjust the CSS as needed for tablet and desktop