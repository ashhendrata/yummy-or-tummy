# YUM OR TUM

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

Detects allergies from menus and ingredient lists at the back of packaged product. Steamlines ordering at restaurants and grocery shopping.

### App Evaluation

[Evaluation of your app across the following attributes]
- **Category:** Health
- **Mobile:** Back camera, location tracking, personalization
- **Story:** Helps people feel safe eating out, decrease risk of medical emergencies, streamlines shopping and ordering process.
- **Market:** 20 million people have food allergies in the U.S., allergies can cause tummy aches to death
- **Habit:** Everytime someone goes to eat out or goes shopping (realistically a few times a week for the app to be used), Create allergy lists or warning lists
- **Scope:** I think it is doable to aim for 100% completion, A stripped-down version with just the scanning and yes/no detection is still cool

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* [DONE] User can add allergies
* [DONE] User can use the back camera to scan the product
* [DONE] User can scan ingredient lists at the back of packages
* User can find out if that product has allergens
* User can store what dishes at a specific restaurant has allergens
* User can scan menus and find out what dishes has allergens
* User can delete allergies

**Optional Nice-to-have Stories**

* User can log in
* User can log out
* User can have a warning list of maybe allergies
* User can share allergy list to someone else (for a child to a babysitter)

### 2. Screen Archetypes

- [ ] Login Screen
* User can log into their account, which has personalized information
- [ ] Registration Screen
* User can state their name and choose their password
- [x] My Allergies Screen
* User can create, read, update, delete allergies
- [x] Camera Screen
* User can scan an ingredient list
* User can scan a menu, highlight a menu item, and store it as being "allergy-safe" or "contains allergies"
- [ ] Allergy List Screen
* User can see a list of potential allergens that a given food item after a scan of an ingredient list
- [ ] Cell view of all restaurants Screen
* User can see a list of restaurants and the associated foods that have been identified as "allergy-safe" or "contains allergies"

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Camera Tab to Camera Screen: If a photo is taken, it automatically gets sent to the Allergy List Screen
* My Allergies Tab to My Allergies Screen: Contains personal allergies
* Restaurants Tab to Restaurants screen: Cell view of restaurants, and the associated foods that have been identified as "allergy-safe" or "contains allergies"

**Flow Navigation** (Screen to Screen)

- [ ] Camera Screen (main screen) to Allergy List Screen
* User can take a picture of an ingredient list and be directed to the list of allergies it may contain
- [ ] Cell view of all restuarants screen to individual restaurant screen
* User can click on a restaurant and see which dishes are "allergy-safe" or "contain allergies"
- [ ] My allergies screen

## Wireframes

![IMG_1752](https://github.com/ashhendrata/yum-or-tum/assets/134671782/6a8468e3-a45b-4586-b2b5-700214c13abe)

## Update: April 17


Phone is laggy so please be patient!


https://github.com/ashhendrata/yum-or-tum/assets/134671782/985c4a98-b065-40a7-b9be-5e879adac818

Update:


https://github.com/ashhendrata/yum-or-tum/assets/134671782/c77bad05-8436-46c5-8c3d-61262eb07af5




Challenges faced: starting was the hardest! And learning how to use the back camera was a journey

What's next: Detecting text in the photos taken

Update: has not been incorporated with camera BUT i implemented the text reading feature tested with images
i am so sorry its all over the place and the features are not linked but hopefully you get an idea! life has been lifeing so its been hard to make progress




https://github.com/ashhendrata/yummy-or-tummy/assets/134671782/428a29eb-f78f-4b60-aa22-03a8a7af3e70





### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 

[This section will be completed in Unit 9]

### Models

[Add table of models]

### Networking

- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
