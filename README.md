# TESTCASES_ZOMATO
Login/Signup Module:
The login module is critical for user authentication in the Zomato app. Test cases here focus on verifying successful login with valid credentials such as a registered mobile number and correct OTP. Negative scenarios like entering an invalid phone number or keeping the fields blank are also tested to ensure the app responds with proper validation messages. These tests help ensure secure and smooth access for users.

Search Functionality:
Search is a key feature that allows users to find restaurants, dishes, or cuisines. Test cases include checking if the search returns correct results when a valid restaurant or cuisine (like "Burger King" or "Italian") is entered. Additionally, the app should handle invalid inputs (e.g., random characters) gracefully by displaying "No results found." This ensures that the search engine is robust and user-friendly.

Restaurant Listing and Filters:
Once the user searches or opens the app, they should see restaurant listings based on their current location (enabled via GPS). The application must also allow users to sort the listings by ratings, delivery time, or price, and apply filters such as veg or non-veg preferences. Testing ensures that the filtering and sorting mechanisms work accurately, giving users a personalized browsing experience.

Cart and Order Placement:
These test cases verify that users can easily add food items to their cart from a restaurant menu. Once items are added, the checkout flow should allow the user to place an order by selecting a delivery address. A missing address or incorrect details should trigger proper error handling. This module ensures that the cart and order process is intuitive and reliable.

Payment Module:
Payments are crucial in any food delivery app. Zomato supports multiple payment options including cards, UPI, wallets, and cash on delivery. Test cases check the payment success flow using valid data, and error handling in case of invalid or expired card details. It’s important to ensure the user receives accurate feedback for successful or failed transactions.

Order History and Reorder Functionality:
This section tests whether the app correctly records past orders and allows users to view them from their profile. If no order history exists (like for a new user), an appropriate message should be displayed. Additionally, users should be able to reorder previous items, and the app should add those items back to the cart seamlessly. This improves user retention and enhances the experience.

