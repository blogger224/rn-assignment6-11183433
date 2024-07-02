## React Native E-commerce UI App

This project is an assignment for the DCIT202 Mobile Application Development course. The goal is to create a mobile application that allows users to view a list of products, add products to their cart, remove products from their cart, and view the items in their cart. The application uses local storage to save selected items on the device.

## Table of Contents

Features

Components

HomeScreen
CartScreen
ProductCard
CartItem
AsyncStorage Implementation

Functionality

Live Demo

## Installation

Clone the repository:

git clone https://github.com/blogger224/rn-assignment6-11183433.git

cd rn-assignment6-11183433

cd rn-assignment6-11254304
Install the dependencies:

npm install
Start the Expo server:

npm start

## Usage

Run the app on an Android or iOS device:

Use the Expo Go app to scan the QR code displayed in your terminal.
Explore the app:

Browse products on the Home screen.
Navigate to the Checkout screen to view the selected products and their total cost.

## Contributing

## License

Features
Display products in a grid layout on the Home screen.
Navigate to the Checkout screen from the Home screen.
Display the list of selected products and their total cost on the Checkout screen.
Bottom tab navigation for the Checkout screen.

## Local Storage Implementation

Local Storage: Utilizes AsyncStorage to store selected items locally on the device.
Products added to the cart are stored persistently using AsyncStorage.
Upon app restart, previously selected items are retrieved from AsyncStorage and displayed in the CartScreen.

## Functionality

The application has the following functionality:
Users should be able to:
View a list of available products.
Add products to their cart.
Remove products from their cart.
View the items in their cart.

## Screenshots

Home Screen

![Screenshot1](/assets/blogger.png)

Checkout Sceen

![Screenshot1](/assets/eben.png)
