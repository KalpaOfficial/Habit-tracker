# Habit-tracker
This Android application is designed to help users maintain and improve their daily personal wellness routines. Built using Android Studio and Kotlin, the app provides an intuitive platform where users can track their habits, record moods, and stay hydrated through timely reminders.
The app follows modern Android development principles using Fragments, SharedPreferences, Intents, and state management techniques, ensuring a smooth and responsive experience across different screen sizes.

The system stores user data locally without using a database, making it lightweight while still retaining user preferences and daily progress. With an optional advanced feature, the app enhances usability and overall user engagement.

## Key Features
1. Daily Habit Tracker
   - Add, edit, and delete daily wellness habits (e.g., drink water, exercise, meditate).
   - Mark habits as complete or incomplete for the day.
   - Displays daily progress with completion indicators or percentage.
   - Data saved using SharedPreferences for persistence.
  
2. Mood Journal with Emoji Selector
   - Users can log their mood with a chosen emoji and timestamp.
   - Stores each mood entry with date/time.
   - Provides a simple list or calendar-like view to review past moods.
   - Supports sharing a mood summary using explicit/implicit intents.

3. Hydration Reminder System
   - Uses Notifications, AlarmManager, or WorkManager to remind users to drink water.
   - Users can set their preferred reminder interval.
   - Notifications work in the background and persist across app restarts.

## Advanced Feature

### Simple Chart (MPAndroidChart)

- Shows weekly mood trend or habit completion chart.
- Enhances visual understanding of user wellness patterns.

# ScreenShots

# Home Page
<img width="396" height="871" alt="Screenshot 2025-10-15 232824" src="https://github.com/user-attachments/assets/30860957-1ef6-40da-90a3-86eae81295da" />

# Simple Chart (MPAndroidChart)

<img width="394" height="874" alt="Screenshot 2025-10-15 232840" src="https://github.com/user-attachments/assets/5cdd994b-7c93-4f5a-9332-9c297f3166bb" />

