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
|<img width="250" alt="image" src="https://github.com/user-attachments/assets/5d4e2f72-2671-408b-a307-38793158be9d" /> | <img width="250" alt="image" src="https://github.com/user-attachments/assets/fe25efe8-9035-406c-81d2-a438793aabd0" /> | <img width="250" alt="image" src="https://github.com/user-attachments/assets/bcffc331-c233-4242-960e-112c95a17001" /> |

| Favorites | Profile | Search |
|----------|---------|----------|
| <img width="250" alt="image" src="https://github.com/user-attachments/assets/a062036e-4431-472f-a5dc-f1b5e576e357" /> | <img width="250" alt="image" src="https://github.com/user-attachments/assets/ec57838b-8c20-480e-aad7-b0acdeaa5762" /> | <img width="250" alt="image" src="https://github.com/user-attachments/assets/366f25c6-84ee-4ce3-a0b5-f4d865b9f8eb" /> |

| Notifications | Help | About |
|--------------|------|-------|
| <img width="250" alt="image" src="https://github.com/user-attachments/assets/277d71dc-9cfd-41b4-8cbb-b32978cf1c1f" /> |<img width="250" alt="image" src="https://github.com/user-attachments/assets/84426ce6-df07-4047-a849-9d02d60e38e9" /> | <img width="250" alt="image" src="https://github.com/user-attachments/assets/3bc3ce4e-0ebc-423b-a1a2-10c0733ab36e" /> |

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

