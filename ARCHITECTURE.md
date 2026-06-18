# System Architecture

```text
User App
    │
    ▼
React Frontend
    │
REST API
    ▼
Express Backend
    │
┌───────────────┐
│   MongoDB     │
└───────────────┘
    │
Socket.IO
    ▼
Driver App

Google Maps API
    ▲
    │
Route & Distance Calculation
```
