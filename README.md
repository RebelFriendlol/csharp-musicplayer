# csharp-musicplayer - Core Logic / Silnik Odtwarzacza

---

## 🇵🇱 Wersja Polska

### O projekcie
Projekt akademicki stanowiący warstwę logiki biznesowej (silnik) dla odtwarzacza muzycznego w języku C#. Odpowiada za obiektową reprezentację utworów, zarządzanie kolejką odtwarzania (Playlista) oraz operacje na plikach dźwiękowych.

### 🔗 Jak ten projekt łączy się z pozostałymi?
Ten projekt to **Serce (Silnik Logiczny)** całego systemu odtwarzacza:
* Dostarcza logiczne struktury danych (np. klasy `Track`, `Playlist`), które są wizualizowane w interfejsie graficznym **`CSHARPGUI / AlbertoPlayer`**.
* Przetwarza dane o utworach, które docelowo są trwale zapisywane i odczytywane z bazy danych w projekcie **`sqlwpf`**.

---

## 🇬🇧 English Version

### About the Project
An academic project serving as the core business logic layer (engine) for a C# music player. It handles the object-oriented representation of audio tracks, playlist queue management, and basic audio file operations.

### 🔗 How this project connects to the others?
This project acts as the **Core Engine** of the entire music player architecture:
* It provides the logical data structures (e.g., `Track`, `Playlist` classes) that are visualized in the graphical user interface **`CSHARPGUI / AlbertoPlayer`**.
* It processes track data that is permanently stored and retrieved from the SQL database in the **`sqlwpf`** project.
