# rn-assignment6-11288670

This React Native Shopping App showcases a simple e-commerce application where users can browse products, add them to a cart, and view the cart with a total price.

Features
Product Listing: Displays a list of products with images, names, and prices.
Add to Cart: Users can add products to their cart.
View Cart: Users can view the items in their cart and see the total price.
Persistent Storage: Cart data is stored using AsyncStorage, so it persists across app restarts.
Design Choices
Component-Based Architecture: The application is divided into reusable components to improve readability and maintainability. Each screen (Home and Cart) is a separate component.
State Management with Hooks: React hooks (useState, useEffect) are used to manage the state and lifecycle of the components.
Navigation: The app uses React Navigation for handling navigation between the Home and Cart screens. This provides a smooth user experience.
AsyncStorage for Persistent Storage: AsyncStorage is used to store the cart data, ensuring it persists even if the app is closed and reopened.
Implementation Details
Home Screen
The Home Screen displays a list of products using a FlatList. Each product is rendered with its image, name, price, and an "Add to Cart" button. The cart state is managed using the useState hook, and the data is persisted using AsyncStorage.

Cart Screen
The Cart Screen displays the items in the cart using a FlatList. Users can remove items from the cart, and the total price is calculated and displayed. The cart state is loaded from AsyncStorage on component mount.

Navigation
The navigation between the Home and Cart screens is handled using React Navigation. The NavigationContainer and createStackNavigator are used to set up a stack navigator.

SCREENSHOTS.
![WhatsApp Image 2024-07-03 at 22 54 14_b30606c7](https://github.com/2004-russell/rn-assignment6-11288670/assets/151689516/9c18ab52-8ec9-4171-b7e5-1dff70cf7260)
![WhatsApp Image 2024-07-03 at 22 54 23_3079989c](https://github.com/2004-russell/rn-assignment6-11288670/assets/151689516/0fc37465-ee7e-4de9-a09f-20110191181b)
![WhatsApp Image 2024-07-03 at 22 54 30_1fc1a797](https://github.com/2004-russell/rn-assignment6-11288670/assets/151689516/a5597f44-cda2-48ef-95a7-b5d7d92068a7)
![WhatsApp Image 2024-07-03 at 22 54 34_e3c9a171](https://github.com/2004-russell/rn-assignment6-11288670/assets/151689516/f23df7b1-e6f0-4ce0-83b3-d2162c139d53)



