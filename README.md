# Kotlin_ToDoApp

# 📝 ToDoApp

A stylish and modern to-do list app developed with Kotlin. Users can easily add, update, delete, and search tasks. Built using modern Android development tools such as MVVM, Hilt, Room, and ViewModel.

---

## 🚀 Features

- ✅ List all tasks
- ➕ Add new tasks
- ✏️ Edit existing tasks
- 🗑️ Delete tasks
- 🔍 Filter tasks via search bar
- 🧭 Navigation with Safe Args
- 💉 Dependency injection with Hilt
- 🗄️ Local database with Room

---

## 🧩 Libraries Used

// Navigation
classpath("androidx.navigation:navigation-safe-args-gradle-plugin:2.5.3")

// Hilt
classpath("com.google.dagger:hilt-android-gradle-plugin:2.56.2")
implementation("com.google.dagger:hilt-android:2.56.2")
kapt("com.google.dagger:hilt-android-compiler:2.56.2")

// ViewModel & Lifecycle
implementation("androidx.lifecycle:lifecycle-viewmodel:2.5.1")
implementation("androidx.lifecycle:lifecycle-runtime-ktx:2.9.0")

// Room (Database)
implementation("androidx.room:room-runtime:2.7.1")
kapt("androidx.room:room-compiler:2.7.1")
implementation("androidx.room:room-ktx:2.7.1")

// Others
implementation("androidx.activity:activity-ktx:1.6.1")
implementation("androidx.fragment:fragment-ktx:1.6.2")


🛠 Architecture
Based on MVVM (Model - View - ViewModel)

Dependency injection with Hilt

Room for local data persistence

Navigation component for screen transitions


## 📸 Screenshots

### 🏠 Home Screen
![Home Screen](/app/src/main/assets/ssMainFragment.png)

### ➕ Add Task Screen
![Add Task](/app/src/main/assets/ssCreateFragment.png)

### ✏️ Edit Task Screen
![Edit Task](/app/src/main/assets/ssUpdateFragment.png)


## 🛠 How to Run

1. Clone the repository
2. Open with Android Studio
3. Sync Gradle
4. Run on emulator or physical device

