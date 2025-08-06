StudyTime App

"StudyTime" is a Kotlin-based Android app built using Jetpack Compose to help university students manage their study schedules, assignments, and goals effectively and efficiently.

-> Overview

This app was developed for my university assignment in the Advanced Mobile Technology - CP5307 -  subject. The goal was to demonstrate proper app architecture, persistent storage, user interface design with Jetpack Compose, and use of modern Android APIs such as Room and ViewModel.

-> Core Features

Features/ Description

1. Task Management - Add new tasks with "tile", "deadline" and "priority". 
2. View Tasks - View all saved tasks on the Home screen in a clean card layout. 
3. Delete Tasks - Swipe or tap the delete icon to remove a task. 
4. Persistent Storage - Tasks are stored using "room database" so data persists between app sessions. 
5. MVVM Architecture - Separation of concerns using ViewModel, Repository, DAO, and Entity classes. 

-> App Architecture 

The app follows the **MVVM (Model-View-ViewModel)** pattern:

- Model: 'Task.kt`, `TaskDao.kt`, `TaskDatabase.kt`
- Viewmodel: 'TaskViewModel.kt`
- View: 'HomeScreen.kt`, `AddTaskScreen.kt`, `TaskItem.kt`
- Repository: 'TaskRepository.kt`
  

-> Technologies Used

- Language: Kotlin
- UI Toolkit: Jetpack Compose
- Persistence: Room Database
- Architecture: MVVM
- IDE: Android Studio


-> Version Control and Developement

This repository demonstrates active use of "version control with github":
- Commits were made regularly throughout development.
- Each commit message reflects the progress and feature additions or fixes.
- GitHub issues or branches can be used to track future improvements.


AUTHOR

Keziah Mary Biju
CP5307
Master of Information Technology, JCU Cairns  




