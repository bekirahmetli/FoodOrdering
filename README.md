# 🍔 Food Ordering App

This is a food ordering application developed with Kotlin using MVVM architecture, Jetpack ViewModel, LiveData, ViewBinding, and Navigation Components. It interacts with a RESTful API for fetching and managing food data.

## 📱 Features

### 🏠 Home Screen
- Lists all available foods.
- Search functionality to filter foods.
- Add/remove favorites.
- Navigate to food detail.

### ⭐ Favorites Screen
- Shows foods marked as favorites.
- Favorite status stored locally using SharedPreferences.

### 🛒 Cart Screen
- Displays foods added to the cart.
- Ability to remove items.
- Calculates and shows total price.
- Simulates order confirmation.

### 🔍 Food Detail Screen
- Displays detailed information about selected food.
- Option to increase/decrease quantity.
- Add to cart functionality.

### 🚀 Splash Screen
- Animated splash screen using Lottie.

## 🛠️ Technologies Used

- Kotlin  
- MVVM  
- Jetpack ViewModel & LiveData  
- ViewBinding  
- Retrofit (for API calls)  
- SharedPreferences (for local favorite data)  
- RecyclerView  
- Glide (image loading)  
- Navigation Component  
- Lottie (animations)

## 📸 Screenshots

### Home Screen
<p float="left">
  <img src="home.png" width="250"/>
  <img src="home2.png" width="250"/>
</p>

### Cart Screen
<img src="cart.png" width="250"/>

### Favorite Screen
<img src="favorite.png" width="250"/>
