# MVVMNewsAndroidApp 📰🚀

A modern, high-performance News application for Android built with the **MVVM (Model-View-ViewModel)** architectural pattern. This app fetches real-time headlines from the **NewsAPI**, provides offline reading capabilities via a local cache, and features a clean, intuitive user interface.

---

## 🎯 Project Purpose

The core objective of this project is to demonstrate a robust implementation of the **Single Source of Truth** pattern. It focuses on:
* **Separation of Concerns:** Using MVVM to decouple UI logic from business and data logic.
* **Efficient Networking:** Handling API responses, loading states, and error scenarios using a generic `Resource` wrapper class.
* **Data Persistence:** Allowing users to "Save" articles for offline viewing using the **Room Persistence Library**.
* **Modern Android Tools:** Leveraging Jetpack components to reduce boilerplate and improve app stability.

---

## 🌟 Key Features

* **Breaking News:** Stay updated with the latest headlines globally, categorized by top interests.
* **Search Functionality:** Find specific news articles using keywords with an optimized search-as-you-type experience.
* **Saved Articles:** A dedicated "Bookmarks" section to store important stories locally.
* **WebView Integration:** Seamlessly transition from the app to the full news source website within a secure in-app browser.
* **Pagination Support:** Smooth scrolling through large datasets using efficient pagination logic.
* **Offline Access:** Read previously loaded or explicitly saved articles even without an internet connection.

---

## 🏗 Architecture & Tech Stack

The app follows a strict **Clean Architecture-inspired MVVM** flow:

| Category | Technology |
| :--- | :--- |
| **UI Framework** | XML (View-based) / Material Design |
| **Networking** | Retrofit + OkHttp |
| **Local Database** | Room (SQLite abstraction) |
| **Architecture** | MVVM (ViewModel, LiveData, Repository) |
| **Concurrency** | Kotlin Coroutines |
| **Navigation** | Jetpack Navigation Component |
| **Image Loading** | Glide |

---

## 🚀 Improvements & Roadmap

* **Jetpack Compose Migration:** Transitioning the UI from XML to a fully declarative Compose-based interface.
* **Dagger Hilt Integration:** Refactoring manual dependency injection to use Hilt for better scalability.
* **Unit Testing:** Adding JUnit and Mockito tests for the Repository and ViewModel layers.
* **Dark Mode:** Implementing a full night-theme support using Material Design 3 guidelines.

---

## 🤝 Contributing

Contributions to improve the codebase or add new features are highly encouraged!

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/NewFeature`).
3. Commit your changes (`git commit -m 'Add some NewFeature'`).
4. Push to the Branch (`git push origin feature/NewFeature`).
5. Open a Pull Request.

---

### 👨‍💻 Author
**Shubham**
* [GitHub](https://github.com/shubham230523)
