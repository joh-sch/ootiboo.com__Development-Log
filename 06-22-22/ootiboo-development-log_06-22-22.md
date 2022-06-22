**ootiboo Digital Platform Development Log**

## **06/22/2022**

_Resources List (Table component)_

- impl. responsive behavior for resources list element by impl. a new `Table` component with proper responsive styling (scrollbar when element overflows screen)
- researched responsive React tables
- added reset for default browser `table` styles (allow custom styling)

<br>

_Housekeeping/Optimization_

- created template for component stylesheet (`[COMPONENT].module.scss`) for faster component creation in the future
- created template for component classname factory (`[COMPONENT].classnames.js`) for faster component creation in the future

<br>

_Misc._

- checked-in with Amanda to resolve force-publishing of News and Creatives entries
  - added [ISR](https://nextjs.org/docs/basic-features/data-fetching/incremental-static-regeneration) to `/creatives/...` route
