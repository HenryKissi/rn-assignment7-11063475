
## Table of Contents
Introduction
Features
Screens
Installation
Usage
Design Choices
Implementation Details
Future Improvements
Contributing
License
Introduction
This is a React Native Shopping App that allows users to browse a collection of products, add them to the cart, and proceed to checkout. The app uses local storage to manage the cart and incorporates a drawer navigation for a better user experience.

## Features
Browse products
Add products to the cart
View cart
Proceed to checkout
Drawer navigation
## Screens
Home Screen: Displays a list of products. Users can add products to the cart and navigate to the product detail or cart screens.
Cart Screen: Displays the products added to the cart. Users can remove products from the cart.
Checkout Screen: Displays the summary of the cart and allows users to proceed with the checkout process.
## Usage
Navigate through the app: Use the drawer navigation to switch between screens.
Add to Cart: Browse products and add them to the cart.
View Cart: View the products in the cart and remove items if necessary.
Checkout: Proceed to the checkout screen to complete the purchase process.
## Design Choices
React Navigation: Used for navigating between different screens and implementing the drawer navigation.
AsyncStorage: Used for local storage to persist the cart data.
FlatList: Used for efficiently rendering the list of products.
TouchableOpacity: Used for handling user interactions like adding products to the cart and navigating between screens.
## Implementation Details
Home Screen
Displays a list of products using FlatList.
Each product has an image, name, description, and price.
Users can add products to the cart by tapping the add button.
## Cart Screen
Displays the list of products added to the cart.
Users can remove products from the cart.
Users can proceed to the checkout screen.
Checkout Screen
Displays a summary of the cart.
Users can confirm their order and proceed with the checkout process.


## Drawer Navigation
Integrated using react-navigation/drawer.
Allows users to easily navigate between the Home, Cart, and Checkout screens.
Local Storage
Implemented using AsyncStorage to persist cart data across app sessions.
## Future Improvements
User Authentication: Implement user login and signup functionality.
Payment Integration: Integrate a payment gateway for processing orders.
Product Filtering: Add filtering options to the product list.
Improved UI/UX: Enhance the user interface and user experience with better styling and animations.
## Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any improvements or bug fixes.

## Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for more information.