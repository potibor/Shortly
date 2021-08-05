# ShortlyApp

![Screenshot_1628162130](https://user-images.githubusercontent.com/26321700/128341541-8b6a0a79-1071-4fb0-a4a8-9e16df42b312.png)

![Screenshot_1628162215](https://user-images.githubusercontent.com/26321700/128341637-f3490574-063a-45c2-98c0-33df001a7c6f.png)

## Architecture

- Single Activity
- MVVM Pattern

**View:** Renders UI and delegates user actions to ViewModel

**ViewModel:** Can have simple UI logic but most of the time just gets the data from UseCase

**UseCase:** Contains all business rules and they written in the manner of single responsibility principle

**Repository:** Single source of data. Responsible to get data from one or more data sources

<img width="677" alt="architecture-diagram" src="https://user-images.githubusercontent.com/26321700/107923530-b0593500-6f82-11eb-99bb-312e149f1757.png">

## Tech Stack

#### Dependencies

- **[Navigation Component](https://developer.android.com/jetpack/androidx/releases/navigation):** Consistent navigation between views
- **[LiveData](https://developer.android.com/topic/libraries/architecture/livedata):** Lifecycle aware observable and data holder
- **[ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel):** Holds UI data across configuration changes
- **[Databinding](https://developer.android.com/topic/libraries/data-binding/):** Binds UI components in layouts to data sources
- **[Coroutines](https://github.com/Kotlin/kotlinx.coroutines):** Asynchronous programming
- **[Room](https://developer.android.com/topic/libraries/architecture/room):** Object mapping for SQLite
- **[Hilt](https://github.com/googlecodelabs/android-hilt):** Dependency injector
