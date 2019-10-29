# Overview
The following details all the projects from the Front End Web Development Techdegree- Tree house
1. [ A Basic Webpage](#unit1)
2. [A Responsive Webdesign](#unit2)
3. [A Responsive Online Registration Form](#unit3)
4. [A Web Style Guide & The use of Sass. ](#unit4)
5. [A Photo Gallery, with jQuery & Javascript](#unit5)
6. [A Game Show App, JS ](#unit6)


<a name="unit1"></a>
# Unit1- A Basic Webpage
This is a basic html & css markup website. 
   


**To Explore the projects:**
  - Github: https://github.com/KennySoh/treehouseFE_unit1_Basic_Webpage/
  - Github Page: https://kennysoh.github.io/treehouseFE_unit1_Basic_Webpage/
  
  
## A sample of the project
![images](https://github.com/KennySoh/treehouse_unit1_Basic_Webpage/blob/master/sample-pic.png)

<a name="unit2"></a>
# Unit2- A Responsive Webdesign, a mobile first approach

A Mobile First Responsive Layout with 3 Different break points (320px , 768px, 1024px)


**Highlights**
- css
  - normalize.css (used to ensure cross browser uniformity) 
  - a Mobile First approach
    - started the css design with the mobile layout. 
    - Uses 2 breakpoints 768px, 1024px| eg: @media (min-width: 768px)
- google font
  - font-family: 'Carter One', cursive;

  
  
  
**To Explore the projects:**
  - Github: https://github.com/KennySoh/treehouseFE_unit2_Responsive_Design
  - Github Page: https://kennysoh.github.io/treehouseFE_unit2_Responsive_Design


## A sample of the project


| Mobile (320px)       | Tablet (768px)         | 
| ------------- |:-------------:| 
| ![images](https://github.com/KennySoh/treehouse_unit2/blob/master/mockups/responsive-website_mobile320.png)  | ![images](https://github.com/KennySoh/treehouse_unit2/blob/master/mockups/responsive-website_tablet768.png) |   

| Desktop (1024px)      |
| ------------- |
|![images](https://github.com/KennySoh/treehouse_unit2/blob/master/mockups/responsive-website_desktop1024.png) |

<a name="unit3"></a>
# Unit3- A Responsive Online Registration Form
A responsive HTML Form coded from scratch. 


**Highlights**
- Form Structure
  - <form> tag contains all inputs, action and method included
  - Field set and legends added for "Contact information" and "Newsletter"
- Form fields and labels
  - Includes the following form fields:
    - text input
    - email input
    - telephone input
    - select menu
    - checkboxes
    - radio buttons
    - textfield
    - submit button
- Mobile-First
   - breakpoint set at 768px


**To Explore the projects:**
  - Github: https://github.com/KennySoh/treehouseFE_unit3_Responsive_Registration_Form
  - Github Page: https://kennysoh.github.io/treehouseFE_unit3_Responsive_Registration_Form

## A sample of the project


|![images](https://github.com/KennySoh/treehouse_unit3_Responsive_Registration_Form/blob/master/sample-pic1.png) |

<a name="unit4"></a>
# Unit4- A Web Style Guide & The use of Sass. 
A style guide is used defined the look and feel of user interface elements on a site. Sass is used to streamline the css creation. 


**Highlights**
- SASS
  - Introduction of vairables 
  ```
  /*Variables*/
  $color-primary:#58e1c1;
  $color-secondary:#51ddfc;
  $color-text:#777;

  $color-default:#51ddfc;
  $color-success:#63cc82;
  $color-error:#e4757a;
  $color-warning:#fd7856;
  $color-info:#927bc1;

  $color-col-1: #927bc1;

  $color-img-frame:#ccc;

  $breakpoint-med:768px;
  ```
  - Seperate Your Stylesheet into Partials
  ```
  //Utilities
  @import 'utilities/variables',
    'utilities/mixins',
    'utilities/functions',
    'utilities/helpers';

  //Base Styles
  @import 'base/reset',
    'base/base';

  //Laout Styles
  @import 'layout/containers',
    'layout/header',
    'layout/card',
    'layout/footer';
  ```
  - The use of mixins to adhere to DRY concepts

**To Explore the projects:**
  - Github: https://github.com/KennySoh/treehouseFE_unit4_SASS
  - Github Page: https://kennysoh.github.io/treehouseFE_unit4_SASS/

## A sample of the project
|![images](https://github.com/KennySoh/treehouseFE_unit4_SASS/blob/master/sample-pic.png) |

<a name="unit5"></a>
# A Photo Gallery, with jQuery & Javascript
A responsive Photo Gallery with a filter funcitonality 


**Highlights**
- The use of a jQuery Plugin 
  - A responsive photo Gallery implmentation 
- Content Filtering
  - Images are filtered in real-time based on user input
- A mobile first reponsive design

**To Explore the projects:**
  - Github: https://github.com/KennySoh/treehouseFE_unit5_Photo_Gallery_With_jQuery
  - Github Page: https://kennysoh.github.io/treehouseFE_unit5_Photo_Gallery_With_jQuery

## A sample of the project

| Photo Gallery        |
| ------------- |
|![images](https://github.com/KennySoh/treehouseFE_unit5_Photo_Gallery_With_jQuery/blob/master/sample-pic1.png)

| Lightbox jQuery Plugin |
| ------------- |
|![images](https://github.com/KennySoh/treehouseFE_unit5_Photo_Gallery_With_jQuery/blob/master/sample-pic2.png)

| Content Filtering JS Script |
| ------------- |
|![images](https://github.com/KennySoh/treehouseFE_unit5_Photo_Gallery_With_jQuery/blob/master/sample-pic3.png)|

<a name="unit6"></a>
# Unit6- A Game Show App, JS 
Multiple Screen Overlay transition and Dynamic word guessing with js. 

**To Explore the projects:**
  - Github: https://github.com/KennySoh/treehouseFE_unit6_Word_Guessing_App
  - Github Page: https://kennysoh.github.io/treehouseFE_unit6_Word_Guessing_App

## A sample of the project

| Start Page    |
| ------------- |
|![images](https://github.com/KennySoh/treehouseFE_unit6_Word_Guessing_App/blob/master/sample-pic1.png)

| Word Guessing    | 
| ------------- |
|![images](https://github.com/KennySoh/treehouseFE_unit6_Word_Guessing_App/blob/master/sample-pic2.png)


| Win| Lose    |
| ------------- |--------------|
|![images](https://github.com/KennySoh/treehouseFE_unit6_Word_Guessing_App/blob/master/sample-pic3.png)|![images](https://github.com/KennySoh/treehouseFE_unit6_Word_Guessing_App/blob/master/sample-pic4.png)|

