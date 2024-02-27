<h1 align="center">Pojo Wallpaper</h1>

<p align="center">
  <a href="https://android-arsenal.com/api?level=23"><img alt="API" src="https://img.shields.io/badge/API-24%2B-brightgreen.svg?style=flat"/></a>
  <a href="https://kotlinlang.org"><img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-1.9.xxx-a97bff"/></a>
  <img alt="Clean Architecture" src="https://img.shields.io/badge/Clean-Architecture-white"/>
  <img alt="MVVM" src="https://img.shields.io/badge/MVVM-Architecture-orange"/>
</p>

<p align="center">  
Pojo Wallpaper is a delightful wallpaper app crafted using Jetpack Compose and adhering to the principles of Clean Architecture. It’s designed to elevate your device’s aesthetics by offering a curated collection of stunning wallpapers.
</p>
</br>

<p align="center">
<img src="https://ik.imagekit.io/zyvpmxkx6/phone/Frame%201171274953.jpg?updatedAt=1709032815888"/>
</p>

## About the project
🚀 Is a modern Android app, built with Jetpack Compose. It's Powered by Hilt, Coroutines, Flow, Jetpack (Retrofit, ViewModel, Navigation), Lottie, and Material3 Design. The app is structured based on Clean architecture and MVVM architecture and modulized by features.

## API
-[Ktor](https://ktor.io/) i created the api with ktro framwork, you can check the code source for backend from here: [Pojo_Backend_Wallpaper](https://github.com/ahmadhashembatal77/Backend-Pojo-Wallpaper)

## Features:
<p align="left"> Stunning Wallpapers: Explore a curated collection of high-quality wallpapers to adorn your device screen.</p>
<p align="left"> Smooth Navigation: Intuitive navigation flow ensures a delightful user experience.</p>
<p align="left"> Minimalist Design: The app’s clean and minimalistic design lets the wallpapers take center stage.</p>
<p align="left"> Efficient and Scalable: Built using Clean Architecture principles, the app is easy to extend and maintain.</p>
<p align="left"> Jetpack Compose Magic: Leverage Jetpack Compose’s declarative UI to create beautiful wallpaper previews.</p>
<p align="left"> Customization Options: Users can set wallpapers directly from the app or download them for later use.</p>

#### 🔗 Download
Go to the [Releases]() to download the latest APK. It works on a free server named [render]() so it will take 50-120 sec tell work in the beginning, the free database will expire on 30/3/2024 so the application will not work after that date 

#### 🏗️ Project Architecture
PojoWallpaper follows the Clean Architecture structure and MVVM. <br> 
- The domain layer contains UseCases that encapsulate a single, specific task that is part of the application's business logic. <br>
- The data layer implements the repository interface defined in the domain layer, providing a single source of truth for data. <br>
- The UI layer and ViewModel layers, use all the components and classes related to the Android framework to get the data from the ViewModel layer and display it on the device.
<img src="https://koenig-media.raywenderlich.com/uploads/2019/06/Clean-Architecture-graph.png" width="500" />
          
## 🔧 Tech stack & Open-source libraries
- Minimum SDK level 23
- [Kotlin](https://kotlinlang.org/) based, [Coroutines](https://github.com/Kotlin/kotlinx.coroutines) + [Flow](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/) for asynchronous.
- [Jetpack Compose](https://developer.android.com/jetpack/compose) is Android's recommended by Google modern toolkit for building native UI.
- Jetpack
  - Lifecycle: Observe Android lifecycles and handle UI states upon the lifecycle changes.
  - ViewModel: Manages UI-related data holder and lifecycle awareness. Allows data to survive configuration changes such as screen rotations.
  - DataStore: Saving tokens and other stuff...
  - [Hilt](https://dagger.dev/hilt/): for dependency injection.
  - [Navigation](https://developer.android.com/guide/navigation/navigation-getting-started) - Used to navigate between fragments
  - [Material3-Components](https://github.com/material-components/material3-components-android) - Material design components
- [Lottie](https://lottiefiles.com/) Effortlessly bring the smallest, free, ready-to-use motion graphics for the web, app, social, and designs.
- [DownloadManager](https://lottiefiles.com/) Download Wallpapers

## :heart: Find this repository useful?
Support it by joining __[stargazers](https://github.com/ahmadhashembatal77/Pojo-Wallpaper/stargazers)__ for this repository. :star: also, __[follow me](https://github.com/ahmadhashembatal77)__ on GitHub for my next creations! 🤩

# License
```XML
Designed and developed by 2024 Ahmad Batal

Licensed under the Apache License, Version 2.0 (the "License");
You may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
