# E-Retail Using Inventory Management System

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### Project Overview
- **Name**: E-Retail Using Inventory Management System
- **Description**: A Flutter project aimed at creating an e-commerce platform with inventory management capabilities.
### Key Features
1. **Product Management**:
   - **Product Listing**: Displays a list of products with details like name, price, and image.
   - **Product Details**: Detailed view of individual products.
   - **Add to Cart**: Functionality to add products to the shopping cart.
2. **Cart Management**:
   - **View Cart**: Displays products added to the cart.
   - **Checkout**: Proceed to order confirmation from the cart.
3. **Category Management**:
   - **Product Categories**: Products are categorized, and users can view products by category.
4. **User Authentication**:
   - **Firebase Authentication**: Integration with Firebase for user authentication.
5. **Database**:
   - **Firestore**: Uses Firestore for storing product and cart data.
### Key Files and Their Roles
- **lib/cart_product.dart**: Manages the cart view and checkout process.
- **lib/product_view_details.dart**: Displays detailed information about a selected product.
- **lib/categorydetail.dart**: Displays products within a selected category.
- **lib/products_grid_view.dart**: Displays products in a grid view.
- **lib/registerproduct.dart**: Handles the registration of new products into the system.
- **lib/productlist.dart**: Manages the list of all products.
- **lib/product_categories.dart**: Manages the display of product categories.
### Configuration Files
- **pubspec.yaml**: Manages project dependencies and assets.
- **android/app/google-services.json**: Configuration for Firebase services.
- **ios/Runner/Info.plist**: iOS configuration file.
### Build and Project Files
- **android/build.gradle**: Gradle build configuration for Android.
- **ios/Runner.xcodeproj/project.pbxproj**: Xcode project configuration.
