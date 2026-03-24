# 📱 Tugas PAM 4 - Profile App (MVVM)

---
NAMA : PRIMA AGUSTA SEMBIRING
NIM  : 123140119

## Deskripsi Aplikasi

Aplikasi **Profile App** ini merupakan pengembangan dari tugas sebelumnya dengan penerapan arsitektur **MVVM (Model-View-ViewModel)**.

Aplikasi ini menampilkan informasi profil seperti:

* Nama
* Bio
* Kontak
* Skill

Serta dilengkapi fitur:
* Edit Profile
* Dark Mode

---

## Fitur Utama

### Implementasi MVVM

* Menggunakan `ProfileViewModel`
* State dikelola dengan **StateFlow**
* UI State menggunakan `ProfileUiState` (data class)

---

### Edit Profile

* Form edit:

  * Nama
  * Bio
* Menggunakan **State Hoisting**
* Tombol **Save** untuk update ViewModel

---

### Dark Mode

* Toggle switch untuk:

  * Dark Mode
  * Light Mode
* State disimpan di ViewModel
* Tampilan berubah secara dinamis

---
## Struktur Folder

com.example.profileapp
│
├── data/
│   └── ProfileUiState.kt
│
├── viewmodel/
│   └── ProfileViewModel.kt
│
├── ui/
│   ├── components/
│   │   ├── ProfileSection.kt
│   │   ├── ProfileButtons.kt
│   │   ├── ContactCard.kt
│   │   ├── SkillSection.kt
│   │   └── MyTextField.kt
│   │
│   └── screen/
│       ├── ProfileScreen.kt
│       └── EditProfileScreen.kt
│
└── MainActivity.kt

---

## Screenshot

### Profile View

![Profile](profile.png)

---

### Edit Profile

![Edit](edit.png)

---

### Dark Mode

![Dark Mode](darkmode.png)

---

## Teknologi

* Kotlin
* Jetpack Compose
* Material 3
* MVVM Architecture
* StateFlow


