**ootiboo Digital Platform Development Log**

## **06/23/2022**

<br>

_Resources List (Table component)_

- added the missing content fields to Project Resources (Strapi):
  - Project ID
  - Type
  - Age Range
- impl. formatting and rendering of new content fields in resources list/table (was dummy content before)

<br>

_Resource Page_

- created page template for dynamic page route of project resources route `.../profile/school/resource/[ProjectID]`

<br>

_Housekeeping/Optimization_

- impl. `Label` component for faster re-use/insertion of label elements
- impl. `TYPE` property for `Tag` component (makes component more flexible, i.e. allows styling tag element with secondary colors)
- intgr. new `Label` component in applicable page templates + deleted deprecated inline html/jsx

<br>

_Misc._
