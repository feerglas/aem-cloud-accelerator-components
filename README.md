# aem-cloud-accelerator-components

These are the base webcomponents which will be used by the aem-cloud-accelerator frontend template.

## Current Issues / Todo's
- Doc's Tab is missing in Storybook
- Live Reload:
  - If a .stories file is changed, live reload works. If the component files are changed, storybook does not automatically reloads.
- @pxblue/storybook-rtl-addon is not working
- how do we handle global styles? do we use css custom properties?
- mixins issue: if 2 web components use a mixing, the same mixin is included in both components. We should find a way of using it globally
- SERVER SIDE RENDERING: we should only use web components, if we find a way to server-side render them.