# nutri-comparison

**PITCH**

Concept:
 -> User can select two products and have the application perform a comparative analysis of each products nutrtion information by establishing common serving size.  Main intention is to see side-by-side a direct comparison as to which product may be nutritionally better.
 
Main Screen
  - Nav Header
  - Introduction and application details
  - Tabbed navigation

Product Selection Screen
* Using an api call to a nutrition site, Edamam, to retrieve nutritional data of food products.
 - User inputs to filter/search for products
 - Card Display of selected items
    - When clicking on a Product Card, the application **routes** to the second/third tab to provide more detail on the products nutrition.
    - Possibilities include: ingredients list, other non-common nutrients and others
 - Upon "Compare" submission the application will display two nutrition labels side-by-side and have the serving size be editable
     - These nutrition labels will auto-adjust upon changing of the serving size.

**DEPENDENCIES**
- Work during the week for 1 or 2 hours/night
- Working over Memorial Day Holiday to ensure plan/schedule is met

**PLAN && TASKS**
- Build out layout --> EC: 20210529
   - _TASK:_ Outline Component Structure and confirm CSS Framework (Bootstrap/Material UI)
- Establish GitHub Pages deployment --> 20210531
   - _TASK:_ Create GitHub deployment Pages
   - _TASK:_ Preview Production build to ensure deployment was successful
- Build in API Functionality --> 20210531
   - _TASK:_ Establish API Key
   - _TASK:_ Build out functional components to handle functionality
- Connect UI/API Functionality --> 20210604
   - _TASK:_ Ensure API Functionality and UI are in alignment and work as expected
- QA/User Input updates --> 20210606
   - _TASK:_ Get inputs from "end users" and perform potential updates

**IF TIME ALLOWS**
- Build in user login functionality with FireBase/FireStore to allow users to favorite products and see past comparisons

**WIREFRAME**

Main Screen
![image](https://user-images.githubusercontent.com/82067454/119920780-1c581b80-bf2a-11eb-9bd0-990369f88784.png)


