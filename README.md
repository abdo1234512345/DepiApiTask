# Depi API Task 🚀

A Flutter mobile application that demonstrates:

- 🔐 **Authentication** with Firebase Auth (Login & Register using Email/Password)
- 🌍 **API Integration** with [FakeStore API](https://fakestoreapi.com/products)
- 🧭 **Navigation & Animations** (Hero & TweenAnimationBuilder)
- 🗂️ **State Management** using Cubit (`flutter_bloc`)
- 🏗️ **Clean and Modular Code Structure**

---

## ⚡ Features

### Authentication
- Firebase **Email & Password login/register**
- Form validation (email format, password length)
- Authentication states handled by `AuthCubit`

### Navigation & Animations
- Smooth navigation with `Navigator`
- **Hero Animation** → product image transition to detail screen
- **TweenAnimationBuilder** → fade/slide animation for product list items

### Home Screen
- Fetches product list from **FakeStore API**
- Displays **image, title, description, price**
- Pull-to-refresh supported
- Product detail screen with **large image & info**

### API Integration
- REST API calls using `http`
- Loading and error states handled gracefully
- Decoupled service layer (`ApiService`)

### State Management
- **Cubit (flutter_bloc)** for managing Auth & Product states
- Clear separation between logic and UI
- Error & Loading states properly displayed


## 🛠️ Project Structure

