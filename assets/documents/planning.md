# Purpose

This document will be used to plan the project before we write any code.

# What are we building?

We are building a signup for a pretend social media site called "GrindLife". The page will consist of a signup form and a company logo supported by a background image, please refer to /assets/images/design-ref.png.

# Assets

We have already gathered the necessary assets which include the following:

- Background image
- Brand font
- Brand logo svg

# Project Components

The page will be split vertically on the left side we will for elements layered in the following order:

- Background image
- Transparent banner (Used to make the logo clearer against the noisy background)
- Logo and Brand name

To the right will be the signup form, a description of what the site offers, a submit button and a option to login if you already have a account. The elements will cascade in the following order.

- Site offering
- Signup form
- Submit button
- Existing member login

The login form must have the following inputs:

- First Name
- Last Name
- Email Address
- Phone Number
- Password
- Confirm Password

# Planning

The first challenge is tackling the html structure. We need to make sure that every element is placed correctly with the use of divs, also must be correctly grouped using classes.

# HTML Structure

The first parents will be used to split the page:

Parent A: Background Image,
          Transparent Banner,
          Logo and Brand Name,
          Credits

Parent B: Site Offering,
          Signup form,
          Submit Button,
          Existing Member


Nesting within the first parents is also need and should look something like this

Parent A {
    Background Image {
        Transparent Banner{
            Logo;
            Brand Name;
        }
        Credits
    }
}

Parent B {
    Site Offering;
    Signup Form{
        FirstName;
        LastName;
        Email;
        Phone;
        Password
    }
    Submit Button;
    Existing Users;
}

# Pseudo Code

Since this project is only made with CSS and HTML I don't think creating pseudo code is the correct approach instead I will create a step by step guide.

# Step By Step

## Step 1
Structure divs and give them ID's & classes {
    I don't know if this is the first thing I should do but I feel if I structure the divs and label them
    it is going the be easier to fill in the gaps later 
}

## Step 2

Fill the div with project elements {
    Now fill the div structure with all the required elements forms, images, headers etc
}

## Step 3

Arrange elements with CSS {
    Use flex to arrange all the elements into their correct placement
}

## Step4

Adjust sizes of elements {
    Adjust the sizes of all the elements so they take up the correct amount of space
}

## Step 5

Style all elements {
    Finally style all the elements below is a list of all the elements that will need to be styled{
        - svg logo will need special filter properties to be colored
        - transparent banner will need its opacity decreased
        - form fields will need styles for invalid, valid, focused and required
        - the form will need to be brighter than the body
        - the form will need box shadow so it pops out
        - the submit button will need styled and hover, and click included
        - the Existing user will need a to hover over the anchor
        - Credit anchors will also need hover
    }
}

