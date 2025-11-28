#  Sydney Film Festival App - FFFinder

A modern iOS application built with **SwiftUI** and **MVVM architecture** that allows users to explore film festivals, browse films, save favorites, receive notifications, and manage their profile settings.  
This project was developed as a collaborative team effort, following clean architecture principles and modular SwiftUI design.

##  Features Overview

###  Film Festivals & Films
- Browse film festivals with dates, descriptions, and event details  
- View award-winning and featured films  
- Explore rich film info: posters, synopsis, awards, director, year, festival association  

###  Favorites
- Save festivals or films as favorites  
- SwiftUI reactive updates ensure smooth UI interaction  

###  Search & Filtering
- Search film festivals by keywords  
- Fast and responsive thanks to MVVM state binding  

###  User Profile System 
- Modern profile page with card-style design  
- Direct access to Settings, Help, Notifications, and About  
- Smooth navigation using SwiftUI’s NavigationStack  

###  Notifications
- In-app notification center  
- Mark notifications as read  
- Structured using reusable SwiftUI components  

###  Settings
- Manage app preferences  
- Logout flow with clean state handling  
- Organized sections using SwiftUI List & Section patterns  

###  Help & Support
- FAQ-style help center  
- Contact support entry  

###  About Page
- App introduction and development team description  


##  Tech Stack

| Category | Technology |
|---------|------------|
| Language | Swift |
| UI Framework | SwiftUI |
| Architecture | MVVM |
| State Management | @State, @Binding, @ObservedObject, @EnvironmentObject |
| OS Target | iOS 16+ |
| Development Tool | Xcode 15+ |

---

##  Architecture (MVVM)

```
FFFinder
├── Models/             # Film, FilmFestival data structures
├── ViewModels/         # Business logic & state management
├── Views/              # SwiftUI UI components & screens
│   ├── Home
│   ├── Festival & Film Detail
│   ├── Profile / Settings / Notifications   
│   └── Components (Buttons, Cards, Rows)
├── Resources/          # Assets, icons, posters
└── FFFinder.xcodeproj
```

Key architectural ideas:
- **ViewModels** handle app logic → clean separation from UI  
- **Views** stay lightweight and declarative  
- **Reusable components** (cards, rows, buttons) ensure UI consistency  
- **NavigationStack** supports deep navigation flows

##  Getting Started

### 1. Clone the Repository

git clone https://github.com/Jasmine709/Sydney-Film-Festival-App.git

### 2. Open in Xcode

Use Xcode 15+

### 3. Run

Select an iPhone simulator (e.g., iPhone 15) → Run (⌘ + R)

## App Screenshots

| Home | Festival Detail | Film Detail |
|------|----------------|-------------|
|<img alt="image" src="https://github.com/user-attachments/assets/edd17400-bf92-4bd7-a56a-12dea14a8057" width="250"/> | <img alt="image" src="https://github.com/user-attachments/assets/a3ac96ba-009d-4556-aa77-1c2a96c92360" width="250"/> | <img alt="image" src="https://github.com/user-attachments/assets/2e6ddccf-21d9-466e-b38f-97e735ad1ef2" width="250"/> |

| Favorites | Profile | Search |
|----------|---------|----------|
| <img src="https://github.com/user-attachments/assets/c9c92005-2d05-4fa7-96df-34bffb8427c6" width="250"/> | <img src="https://github.com/user-attachments/assets/5d6c30b5-b091-4573-8bc7-7e0cfad194be" width="250"/> |  <img width="250" alt="image" src="https://github.com/user-attachments/assets/e0a8648e-f7e6-435b-b0e8-f68ccd418488" />|

| Notifications | Help | About |
|--------------|------|-------|
| <img src="https://github.com/user-attachments/assets/6aee85c8-4588-41dd-b0a0-39aef8dcdc65" width="250"/> | <img src="https://github.com/user-attachments/assets/de4605cd-605d-45f0-a596-fdc4d87505c3" width="250"/> | <img src="https://github.com/user-attachments/assets/2c56f652-d104-4bf8-96bd-72fb1e09ace8" width="250"/> |

##  My Contributions (Jasmine)

I led the implementation of the User Account System, which includes all user-centered functional modules beyond the festival/film browsing features.
My work focused on architecture, navigation, reusable UI design, and MVVM-based state management.

### Profile Page

- Designed a clean profile dashboard with modern card UI

- Built navigation to Settings, Notifications, Help, and About

- Ensured responsive layout and consistent SwiftUI styling

### Notification Center

- Implemented the in-app notification list

- Designed “mark as read” interactions

- Connected view with ViewModel for reactive updates

### Settings Page

- Implemented account preference layout with SwiftUI List + Section

- Built secure Logout system with proper state handling

- Designed modular reusable setting rows/components

### Help & Support

- Created FAQ-style help section

- Added support / contact entry

### About Page

- Added team and app introduction screens

- Designed typography & layout for readability

### Skills Demonstrated

- SwiftUI view architecture

- MVVM logic separation

- Multi-screen navigation

- State management (ObservableObject, @State, etc.)

- Component-driven UI design

- Building complete user flows

##  License

This project is for educational and portfolio purposes.
Film images and metadata belong to their respective owners.

