Android Chat Application developed using Android Studio & Firebase.
## Features

- 1-1 Chats
- Full chat history
- Send/receive chat messages
- Offline support enabled



## Built With  🛠
- Java - Best & Most used programming language for Android development.
- Firebase
   - [Firebase Authentication](https://firebase.google.com/docs/auth) - Kowing the identity of the user to securely store the user data in the cloud and provide the same personalized experience across all of the user's devices
   - [Firebase Cloud Firestore](https://firebase.google.com/docs/firestore) - To store data & keep it in sync across client apps & provide offline support
   - [Firebase Storage](https://firebase.google.com/docs/storage) - A storage service to store images, files, videos, audio
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Collection of libraries that help you design robust, testable, and maintainable apps.
  - [LiveData](https://developer.android.com/topic/libraries/architecture/livedata) - Data objects that notify views when the underlying database changes.
  - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Stores UI-related data that isn't destroyed on UI changes. 
  - [ViewBinding](https://developer.android.com/topic/libraries/view-binding) - Generates a binding class for each XML layout file present in that module and allows you to more easily write code that interacts with views.
- [Koin/ Dagger2](https://insert-koin.io) - Dependency Injection Framework
- [Glide](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling.
- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.
- Room Database
- RxJava
- RecyclerView

  ## 👨‍🔧 Architecture
This app uses [***MVVM (Model View View-Model)***](https://developer.android.com/jetpack/docs/guide#recommended-app-arch) architecture.

1) The UI components are kept away from the business logic

2) The business logic is kept away from the database operations

3) It's easy to read (because everything has specific places to live)

4) And if done correctly, you have a lot less to worry about when it comes to lifecycle events (ex: screen rotations)
