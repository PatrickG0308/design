# D'Arcy Driving School

## A website for a Driving School based in East Meath covering the Louth Meath areas of Ireland

### Creator - Patrick Grant

![am I responsive screenshot](assets/images/features/Responsive.jpg)

## **[Live site](https://patrickg0308.github.io/design/index.html)**

---

## **[Repository](https://github.com/PatrickG0308/design)**

---

## Table of contents

1. [UX Design](#ux-design)
2. [Features](#features)
3. [Features Left](#left)
4. [Technology used](#technologies)
5. [Testing](#testing)
6. [Bugs](#bugs)
7. [Deployment](#deployment)
8. [Credits](#credits)
9. [Content](#content)
10. [Acknowledgements](#acknowledgements)

<a name="ux-design"></a>

# UX design

## Strategy Plane

### To determine the best approach to this project I started with to determine the user and business needs

## User

> As a user I want to be able to find a driving school in my local area.  
> As a user I want to be able to contact the driving school online.  
> As a user I want to be able to book lessons online.  
> As a user I want to be able to read testimonials about the driving school .  
> As a user I want to be able to order a gift voucher.

## Business Owner

> As the site owner I want to be able to showcase the lessons available.  
> As the site owner I want to highlight the services on offer.  
> As the site owner I want to create leads and provide students a way to book online and/or request quotes.  
> As the site owner I want to use this website to attract students in the Meath & Louth area.
> As the site owner I want to provide customers the ability to obtain Gift Vouchers.

# Scope Plane

> The website should have a Navigation menu that is consistent across all pages and devices.  
> The website should have a information message for the student explaining to them who we are and what we provide and the area we cover.  
> The website should neatly and appropriatly list the lessons we provide to the students.  
> The website should give the student proof of work completed through testimonials.  
> The website should give the student a way to contact the business for quotes or vouchers through a form.  
> The website should give the user more contact methods including phone number, e-mail, instagram page.

# Structure Plane

> To acheieve the goals of the above the website should include at least 5 pages consisting of: Home, Lessons, Testimonials, Gift Vouchers, Contact.

**Home Page**

> Navigation with links  
> Welcome message with call to action to take user to contact form through use of Submit Button.  
> Service card section showcasing the services offered.
> Footer section with details of phone number, email and instagram link

**Lessons**

> The lesson page should outline the lessons available to the student.  
> The lesson page should allow for the ability to book a lesson directly under the description.
> The lesson page should also have an informational video on RSA approved EDT lessons.

**Testimonials**

> The portfolio page should show images of successful students and comments they have made about D'Arcy Driving school.

**Gift Vouchers**

> The Gift Voucher page should allow customers the ability to order a gift voucher through the use of a dropdown menu in a form.

**Contact**

> The contact page should have a contact form for the student to make an enquiry or request quote.  
> The form should collect contact details for the customer so that the owner can contact them.
> The form should have a dropdown menu offering the choice of lesson available.
> The contact form should give user feedback on submission.

<a name="features"></a>

# Features

## index.html

#### Navigation Bar

![Navigation Bar](assets/images/features//NavBar.jpg)

> Logo on left side with 5 nav links on right with hover styling.

#### Intro

![Intro Section](assets/images/features//intro.jpg)

> Intro and image side by side with call to action book now button. This button will take user to contact.html

#### Services Section

![Services Section](assets/images/features/services.jpg)

> Services showcased through the use of images.

#### Footer

![Footer](assets/images/features/footer.jpg)

> Contact information for business highlighted in "Traffic light" green.

## lesson.html

#### Lesson Type

![lesson type](assets/images/features/type.jpg)

> Outline lesson type with description and click to action button which takes user to contact page.

#### EDT Video

![EDT Video](assets/images/features/EDT.jpg)

> You Tube video outlining EDT training requirements plays in page.

## testim.html

![Testimonials](assets/images/features/testimonials.jpg)

> Testimonials from successfull students

## gift.html

![Gift Form](assets/images/features/giftform.jpg)

> Collects user data through compulsory fields, offers a choice of amounts through dropdown menu. Upon submission this page is redirected to thankyou.html page for better user experience.

## contact.html

![Contact Form](assets/images/features/contactform.jpg)

> Main traffic page were all click to action "Book Now" buttons are redirected. Collects data through compulsory fields and offers a dropdown menu with choice of lessons available. Offers an enquiry field for general enquiries.Upon submission the user is redirected to thankyou.html

## thankyou.html

![Contact Form](assets/images/features/thanks.jpg)

> Submitted requests from gift.html and contact.html will receive this response for better user experience.

<a name="left"></a>

# Features Left to Implement

> As a future enhancement, the contact form will be updated with javascript to send an email to D'arcy Driving School with the contact information.

> Add more social media to footer

> Use javascript to minimize navlinks to 3 bar setting on responsive screen

<a name="technologies"></a>

# Technologies

- HTML
  - The structure of the Website was developed using HTML as the main language.
- CSS
  - The Website was styled using custom CSS in an external file.
- CodeAnywhere
  - The website was developed using Visual Studio Code IDE <https://app.codeanywhere.com/>
- GitHub
  - Source code is hosted on GitHub and delpoyed using Git Pages.
- Font Awesome
  - Icons obtained from <https://fontawesome.com/> were used as the Social media links in the footer section.
- Tinypng
  - <https://tinypng.com/> was used to reduce the size of the images used throughout the website
- Cloudconvert
  - webp files were created at <https://cloudconvert.com/>
- SimpleImageResizer
  - Resize image files <https://www.simpleimageresizer.com/>

<a name="testing"></a>

# Testing

**Testing for links and Form**
| Test |Outcome |
|--|--|
|All links on Navigation lead to their correct pages| Pass |
|All Book Now buttons leads to contact form on contact us page| Pass
|Footer social links all lead to their respective social media sites |Pass|
|Contact form submits when all criteria is filled correctly| Pass |
|User prevented from submitting form without correct elements| Pass|
|Form Validation presents when incorrect input type is entered |Pass|
|Thank you page appears upon submission of Gift and Contact forms |Pass|

**Testing for responsiveness**
| Test |Outcome |
|--|--|
|Home page, about, portfolio, contact us displays correctly on screens larger than 700px|Pass |
|Home page, about, portfolio, contact us displays correctly on screens smaller than 700px |Pass

**User responsive testing**

> Asked friends and family to view the website on their mobile devices and/or PC's to provide any feedback on errors or page overlapping issues.

| Test            | Result |
| --------------- | ------ |
| Issues Reported | None   |

## Google Lighthouse Testing

### index.html

![Google Lighthouse index.html](assets/images/validation/lightindex.jpg)

### lesson.html

![Google Lighthouse lesson.html](assets/images/validation/lightlesson.jpg)

### testim.html

![Google Lighthouse testim.html](assets/images/validation/lighttestim.jpg)

### gift.html

![Google Lighthouse gift.html](assets/images/validation/lightgift.jpg)

### contact.html

![Google Lighthouse gift.html](assets/images/validation/lightcontact.jpg)

### thankyou.html

![Google Lighthouse gift.html](assets/images/validation/lightthankyou.jpg)

## HTML Validation

### index.html

![W3 index.html Check](assets/images/validation/indexhtml.jpg)

#### Result: No Errors

### lesson.html

![W3 lesson.html Check](assets/images/validation/lessonhtml.jpg)

#### Result: No Errors

### testim.html

![W3 testim.html Check](assets/images/validation/testimhtml.jpg)

#### Result: No Errors, 1 warning about the section missing a heading. Page heading appears for the portfolio above and requires no additional content

### gift.html

![W3 gift.html Check](assets/images/validation/gifthtml.jpg)

#### Result: No Errors

### contact.html

![W3 contact.html Check](assets/images/validation/contacthtml.jpg)

#### Result: No Errors

### thankyou.html

![W3 contact.html Check](assets/images/validation/thankyouhtml.jpg)

#### Result: No Errors

## CSS Validation

### index.html

![W3 index.html Check](assets/images/validation/validcss.jpg)

#### Result: No Errors

<a name="bugs"></a>

## **Bugs**

> Font awesome only showing squares even though script in place **fixed**
>
> Issues with image sizing **fixed**
>
> Issues with responsiveness **fixed**
>
> Issues after running validation **fixed**
>
> Contrast issues with Book Now buttons and background colors **fixed**
