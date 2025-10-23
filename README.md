#Video Feed

*Video Feed** is an open-source to allow video rendering.


To keep performance sharp and resource usage minimal, the project uses an LRU (Least Recently Used) caching strategy for video preloading and disposal.

> ⭐️ If you find this project useful, consider giving it a star on GitHub — it helps others discover it too!

## 🏗 Project Structure

The project follows a clean architecture approach:

```
lib/
├─ core/
│  ├─ constants/
│  ├─ di/
│  ├─ init/
│  ├─ interfaces/
├─ data/
│  ├─ repository/
├─ domain/
│  ├─ models/
├─ presentation/
│  ├─ views/
│  ├─ blocs/
│  ├─ design_system/
│  ├─ l10/
├─ main.dart
```

