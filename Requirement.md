Critical Questions for Testing New Features:
1. Product Rating System.
Requirement: Users should be able to rate products with a 5-star system and have the option to add written feedback.

Functionality:

Could users submit a star rating without adding written feedback? If so, how is it displayed?
Is it possible to submit multiple reviews for the same product? If not, how is this prevented?
How does the system handle edge cases, such as partial star ratings (e.g., 3.5 stars)?
User Interface (UI):

Does the star rating system display correctly on all devices and screen sizes?
Is there a character limit or validation for the written feedback field?
Are error messages displayed if required fields are left blank or improperly filled?
Backend/Performance:

Are ratings and feedback stored securely and correctly linked to the product in the database?
Can the system handle simultaneous reviews from multiple users on the same product?
Does the system detect and prevent spam or inappropriate feedback?
2. Age Verification for Alcoholic Products
Requirement: Alcoholic products require age verification. A modal should appear when navigating to the alcoholic products category asking if the user is 18+. Users must input their age before accessing the alcoholic products.

Critical Questions
Functionality:

Does the age verification modal always appear when accessing the alcoholic products category?
Can users bypass the modal and access alcoholic products without inputting their age?
How does the system respond to invalid inputs, such as non-numeric characters or ages below 18?
User Interface (UI):

Is the modal visible and responsive across different devices and screen sizes?
Do you know if instructions for age verification are clear and user-friendly?
Can users close the modal without completing the verification, and what happens in such cases?
Compliance and Security:

Does the system remember the user’s verified status for the session, and is this process secure?
Are there mechanisms to ensure compliance with local laws regarding age verification?
Is there a way to monitor or report users who attempt to falsify their age?
3. Shipping Cost Changes
Requirement: Free shipping for orders above a certain amount. Orders below this amount will incur a shipping fee.

Critical Questions
Functionality:

Is free shipping automatically applied when the order total exceeds the threshold?
Is the correct shipping fee displayed for orders below the free shipping threshold?
How does the system handle cases where an order is edited and crosses the free shipping threshold?
User Interface (UI):

Is the shipping cost displayed during the checkout process?
Are changes to the shipping cost dynamically updated as items are added or removed from the basket?
Are regional settings, such as currency and shipping thresholds, displayed correctly?
Backend/Performance:

Does the system accurately calculate shipping costs for large and complex orders?
Can the system handle a sudden surge in orders without errors in applying free shipping?
Are free shipping thresholds and fees managed correctly for different regions or currencies?
