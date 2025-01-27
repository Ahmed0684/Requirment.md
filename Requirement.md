Market Mate:   
Critical Questions for Testing New Features:

1. Product Rating System.

New features

1. Age Restriction for Account Creation.

Vague Requirement:

-> Users should be able to rate products with a 5-star system and have the option to add written feedback.

Questions:

Could users submit a star rating without adding written feedback? If so, how is it displayed?
Is it possible to submit multiple reviews for the same product? If not, how is this prevented?
How does the system handle edge cases, such as partial star ratings (e.g., 4.5 stars)?

Detailed requirements:

Users can rate a product by selecting between 1 and 5 stars, rating options should be interactive and visually intuitive.
Users can also submit a rating without leaving written feedback.

2. Age Verification for Alcoholic Products

Vague Requirement:

-> Alcoholic products require age verification. A modal should appear when navigating to the alcoholic products category asking if the user is 18+. Users must input their age before accessing the alcoholic products.

Questions:

Does the age verification modal always appear when accessing the alcoholic products category?
Can users bypass the modal and access alcoholic products without inputting their age?
Is the modal visible and responsive across different devices and screen sizes?
Can users close the modal without completing the verification, and what happens in such cases?
Detailed requirement:

Age Verification for Alcoholic Products.
The purpose is to ensure compliance with legal regulations by verifying a user’s age before granting access to alcoholic products. Prevent underage users from browsing or purchasing restricted products.
3. Shipping Cost Changes:

Vague Requirement:

-> Free shipping is available for orders above a certain amount. Orders below this amount will incur a shipping fee.

Questions:

Is the correct shipping fee displayed for orders below the free shipping threshold?
Is free shipping automatically applied when the order total exceeds the threshold?
Are changes to the shipping cost dynamically updated as items are added or removed from the basket?
Detailed Requirement:

Set a configurable threshold amount for free shipping (e.g., $50).
Orders with a total value (before shipping) equal to or greater than the threshold will qualify for free shipping.
Orders below this threshold will incur a standard shipping fee.
