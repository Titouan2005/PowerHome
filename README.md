# PowerHome ⚡

An Android app (Java) for tracking how much energy a household uses. Residents can sign in, see the homes ("habitats") in their building and their appliances, and set notifications and preferences.

> Team project (BUT Informatique, Université Paris Cité): **Titouan Le Neun**, Maxence, Osman.

## Features
- Splash screen, login, registration and password reset
- Session management (stays logged in)
- List of habitats with their residents and appliances (RecyclerView + custom adapter)
- "My habitat" page showing my own appliances
- Notifications and user preferences
- Edit profile
- Navigation drawer with fragments

## Tech stack
| Part | Choice |
|---|---|
| Language | Java |
| Platform | Android (AppCompat, Material Components, Navigation component) |
| Networking | Ion (HTTP requests to the back-end API) |
| JSON | Gson |
| IDE / build | Android Studio, Gradle |

## Project structure
```
app/src/main/java/com/example/powerhome/
├── SplashActivity, LoginActivity, RegisterActivity, ForgotPasswordActivity
├── MainActivity                  navigation drawer host
├── HabitatsFragment, MyHabitatFragment, NotificationsFragment, PreferencesFragment
├── Habitat, Appliance            data models
├── HabitatAdapter                RecyclerView adapter
└── SessionManager, Constants
```

## Run it
1. Clone the repo and open it in **Android Studio**.
2. Let Gradle sync.
3. Run on an emulator or an Android device.

## My role
<!-- TODO Titouan: 1–2 lines on what you built (e.g. login/session, habitat list...) -->
