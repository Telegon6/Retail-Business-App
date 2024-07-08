Retail App
A feature-rich Android application implementing the Timbu Retail API to showcase a list of products with an intuitive and adaptive user interface. This app follows the MVVM architecture for efficient UI state management and error handling.
Features
    • Splash Screen: Displays a splash screen for 2 seconds on startup.
    • Product List: Shows a grid list of products with a span count of 2.
    • Product Details: Each product displays a description, available quantity as a progress bar, and a price.
    • Error Handling: Proper UI state management with error handling.
    
Screenshots
Splash Screen
![Screenshot_20240708_232415_Retail Business App](https://github.com/Telegon6/Retail-Business-App/assets/115192722/10c5e022-1779-4d4c-8db2-9dd206b1c091)

Product List
![Screenshot_20240708_232437_Retail Business App](https://github.com/Telegon6/Retail-Business-App/assets/115192722/bb5496ae-323b-4f2f-8631-7f12d74909f2)

![Screenshot_20240708_232503_Retail Business App](https://github.com/Telegon6/Retail-Business-App/assets/115192722/69679b76-77eb-445b-b6fb-d8eeec6babcc)

Getting Started
Prerequisites
    • Android Studio 4.0 or later
    • Gradle 6.5 or later
    • An Android device or emulator running Android 5.0 (Lollipop) or later
Installation
    1. Clone the Repository:
       git clone https://github.com/yourusername/retail-app.git
       cd retail-app
    2. Open in Android Studio:
        ◦ Open Android Studio.
        ◦ Click on File -> Open and navigate to the cloned repository directory.
        ◦ Select the project to open it.
    3. Build the Project:
        ◦ Allow Android Studio to download all the necessary dependencies.
        ◦ Click on Build -> Make Project.
    4. Run the App:
        ◦ Connect an Android device or start an emulator.
        ◦ Click on Run -> Run 'app'.
Usage
Upon launching the app, you will see a splash screen for 2 seconds before being taken to the product list screen. The product list displays products in a grid layout with 2 columns. Each product shows its image, description, price, available quantity, and a favorite button.

Retail API Integration
This app integrates with the Timbu Retail API to fetch product data.
Endpoint:
GET https://api.timbu.cloud/products?organization_id=YOUR_ORGANIZATION_ID&Appid=YOUR_APP_ID&Apikey=YOUR_API_KEY

App Showcase
Experience the app on Appetize.io:
https://appetize.io/app/b_3irp3npdhho7sj6aobttu3y6u4

APK Download
Download the latest APK file from the link below:
https://appetize.io/embed/b_3irp3npdhho7sj6aobttu3y6u4

Project Structure
    • Model: Contains data classes representing the product information.
    • ViewModel: Handles the business logic and data processing.
    • Repository: Manages data operations and provides a clean API for data access to the rest of the app.
    • View: Contains the UI components and displays the data.
Dependencies
    • Retrofit: For API calls.
    • Glide: For image loading..
Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.
License
This project is licensed under the MIT License - see the LICENSE file for details.
