---
layout: essay
type: essay
title: Assignment 3 Checkpoint
date: 2020-12-01
---
<b>Checkpoint A: Describe your design for your site's shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart</b>
<br>
The shopping cart will be a separate page where the user can view and edit their products in the shopping cart. Users can access the shopping cart via the navigation bar or when they are purchasing their products. Currently on my site, when users purchase a product, they put in the quantities that they want and on the bottom there is a submit button that will lead them to the login/registration page and then to the invoice. For this assignment, to implement the shopping cart feature, instead of going to the login/registration first when clicking that submit button on the bottom, it will the send the user to the shopping cart. After they have checked out the rest of the items on my site and want to complete their purchase, on the bottom of that page I will have a button that says "complete purchase" and it will lead the user to the login/registration page and then after they have logged, I am hoping to add a page where they can add their address and payment information in it, then after they add it will go to the invoice which confirms the purchase and displays the items they have purchased and confirmation of their billing address.

<b>Checkpoint B: Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their keys) you will use to manage the shopping cart data and how they will be used in $_SESSION.</b>
<br>
Since I am not requiring the user to login before they add products to their cart, I will be using sessions to save the user's cart information.

<b>Checkpoint C: How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?</b>
<br>
To currently address the security issues for my site and to not allow access to the invoice page by typing it into the URL, I have set up an alert on my invoice page that will send an alert and also redirect the user back to my product's page. This allows users from not being able to access the invoice without logging in first and also protecting other user's sensitive information.

<b>Checkpoint D:Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary):</b>
<br>
As mentioned in checkpoint A, upon logging in, I am hopping to add a page where the user can input their address and payment information, then after that is verified it will send the user to the invoice page that is a confirmation of their purchase. On the invoice page, it will have a personalized message containing their name thanking the user for their purchase and the page will also be displaying their billing address for confirmation.

<b>Checkpoint E: If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?</b> 
<br>
I am working alone and will be building off my existing website from Assignment 1 and 2.  

<b>Checkpoint F: How are you approaching Assignment 3 differently than Assignment 2?</b>
<br>
For assignment 3, I hope it to finish it by the Sunday right before finals week. One change that I will make is to make copies of the code that I am working on and committing the work more frequently to the repo, especially for the codes that I know are functional and works. In the previous assignments, I was constantly testing things out and grabbing code from different places, but then that would end up harming me because I would break the code and end up with errors. So this time around, I will be testing my code more often and ensuring that I save the code that I delete or have original versions of my previous codes. 
