# 🎵 SKT Flow

> Your intelligent music companion — a personalized, YouTube-powered music streaming experience built for music lovers.

**SKT Flow** is a modern Android music streaming application designed to provide a clean, personalized, and intelligent listening experience.

The app combines YouTube-powered music streaming with personalized recommendations, curated playlists, synchronized lyrics, local music features, playlists, likes, listening history, and a modern Material 3 interface.

---

## ✨ Overview

SKT Flow is built around one simple idea:

**Discover music that fits you and enjoy it in a clean, fast, and personalized experience.**

The application brings together music discovery, personalized recommendations, playlists, lyrics, history, and local music functionality in one place.

SKT Flow is designed especially with Indian music listeners in mind, supporting music discovery across genres and languages including:

- 🎬 Bollywood
- 🎵 Hindi
- 🎧 Punjabi
- 🌿 Bhojpuri
- 🛕 Devotional
- 🌎 International music

The app uses YouTube as its music streaming source and provides an optimized interface focused on discovery and listening.

---

# 🚀 Features

## 🏠 Quick Picks

Discover music based on your listening activity and preferences.

Quick Picks provides a personalized selection of songs so you can quickly find something to listen to without manually searching for every song.

---

## 🔥 Trending Songs

Explore currently popular songs and discover what other listeners are enjoying.

The Trending section makes it easy to discover new music without having to search manually.

---

## 🤖 Personalized Recommendations

SKT Flow learns from your listening activity and uses it to provide more relevant recommendations.

Your listening behavior can help improve:

- Quick Picks
- Trending recommendations
- Recently played content
- Personalized discovery

---

## 🎼 Curated Playlists

Explore playlists created around different themes, moods, genres, and occasions.

Curated playlists are designed to make music discovery easier when you don't have a specific song in mind.

---

## 🎉 Anniversary Specials

Discover special playlists and collections celebrating iconic moments and anniversaries related to Indian music.

This section helps users rediscover memorable songs and artists.

---

## ❤️ Like Your Favorite Songs

Save songs you enjoy by adding them to your liked songs collection.

Your liked songs remain organized inside your Library for quick access later.

---

## 📥 Downloaded Songs

Access your downloaded music from a dedicated section.

Downloaded songs can be managed separately from online streaming content, making it easier to find music saved for offline listening.

---

## 🕘 Recently Played

SKT Flow keeps track of your recently played music so you can quickly return to songs you listened to previously.

This makes it easier to continue listening without searching for the same song again.

---

## 📝 Synced Lyrics

Enjoy synchronized lyrics while listening to supported songs.

SKT Flow supports multi-source lyrics with automatic fallback to improve lyrics availability.

### Lyrics system includes:

- Multiple lyric sources
- Automatic fallback
- Synchronized lyrics
- Lyrics display during playback

---

## ☁️ Cloud Sync

Your important user data can be synchronized across devices.

Cloud synchronization is designed to keep your:

- Playlists
- Likes
- Listening history
- User preferences

available across supported devices.

---

## 🎨 Custom Themes

SKT Flow supports customizable themes with:

- 🌙 Dark mode
- ☀️ Light mode
- 🎨 Adjustable navigation styles

The interface is designed around modern Material 3 principles while allowing users to personalize their experience.

---

## 🔐 Simple Sign-In

SKT Flow provides a simple sign-in experience using Google authentication.

Users can sign in with Google and access features that require an account.

---

## 🔔 In-App Updates

SKT Flow can notify users when a new version becomes available.

The application can check for new releases and prompt the user to update when a newer version is available.

---

# 📦 Installation

SKT Flow is distributed outside the Google Play Store.

You can install the latest APK from the project's GitHub Releases section.

### Installation steps

1. Download the latest APK from **Releases**.
2. Open the downloaded APK on your Android device.
3. If Android asks for permission, allow installation from the required source.
4. Install SKT Flow.
5. Open the application.
6. Sign in with Google to get started.

> **Note:** Android may display a security warning when installing applications from outside the Google Play Store. Only install APK files from a source you trust.

---

# 🔄 Updating SKT Flow

SKT Flow includes an in-app update system.

When a new version is released:

1. SKT Flow checks for a newer release.
2. The application notifies you about the update.
3. You can download the latest APK.
4. Install the new version over your existing installation.

Your existing application data should remain available during a normal update.

---

# 🛠️ Technology Stack

SKT Flow is built using modern Android development technologies.

### Core

- **Kotlin**
- **Jetpack Compose**
- **Material 3**

### Architecture & Android

- Android SDK
- Jetpack libraries
- Declarative UI with Jetpack Compose
- Firebase Authentication
- Cloud synchronization

### Music & Data

- YouTube-powered music streaming
- Multiple lyrics sources
- Local music library
- Offline/downloaded music management

### Networking & Async Processing

- Coroutines
- Flow
- Asynchronous data handling

---

# 🏗️ Architecture

SKT Flow follows a modern Android application architecture focused on maintainability and reactive UI development.

The application uses:

```text
Android
   │
   ├── Jetpack Compose
   │       └── Material 3 UI
   │
   ├── Kotlin
   │       ├── Coroutines
   │       └── Flow
   │
   ├── Firebase
   │       ├── Authentication
   │       └── Cloud Synchronization
   │
   ├── NewPipe Extractor
   │       └── YouTube-powered music backend
   │
   └── Local Storage
           ├── Likes
           ├── Playlists
           ├── History
           └── Downloaded Music



SKT Flow
Your intelligent music companion — tuned to you.
A personalized, YouTube-powered music streaming app built for Indian music lovers.
About
SKT Flow brings together Bollywood, Punjabi, Bhojpuri, and Devotional music into one clean, intelligent listening experience. It learns what you love and surfaces more of it — one song at a time.
Built as a sideloaded companion app (not on the Play Store), SKT Flow streams directly from YouTube and wraps it in a fast, personalized, ad-supported interface designed specifically for how Indian listeners discover and enjoy music.
Features
Quick Picks and Trending — Personalized recommendations based on your listening habits
Curated Playlists — Featured playlists and Anniversary Specials celebrating iconic Indian music
Offline Downloads — Save your favorite tracks in high-quality audio
Synced Lyrics — Multi-source lyrics with automatic fallback
Cloud Sync — Your playlists, likes, and history follow you across devices
Custom Themes — Light and Dark modes with adjustable navigation styles
Simple Sign-In — One-tap secure login with Google
In-App Updates — Get notified the moment a new version drops
Installation
SKT Flow is distributed outside the Play Store. To install:
Head to the Releases page of this repository
Download the latest .apk file
Enable "Install from Unknown Sources" on your Android device
Install and sign in with Google to get started
Once installed, SKT Flow will automatically check for new releases and prompt you to update.
Built With
Kotlin and Jetpack Compose — modern, declarative UI
Material 3 — design system
Firebase — Authentication and Cloud Firestore sync
Room — local persistence and offline library
NewPipe Extractor — YouTube streaming backend
Coroutines and Flow — async data handling
Developer
Sumit Kumar Tiwari
Independent Android developer, building SKT Flow from the ground up — design, backend, and everything in between.
Made with love, for music lovers.
