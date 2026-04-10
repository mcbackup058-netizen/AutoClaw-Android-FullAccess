# AutoClaw - Android APK (Full Device Access)

## Deskripsi

AutoClaw adalah build modifikasi dari **OpenClaw** (project open source oleh Zhipu AI) yang dikonfigurasi dengan **90+ permissions** untuk akses penuh ke seluruh perangkat Android.

## Informasi Build

| Info | Detail |
|------|--------|
| **Package** | `ai.openclaw.app` |
| **Version** | 2026.4.10 |
| **Min SDK** | 31 (Android 12) |
| **Target SDK** | 36 (Android 16) |
| **Flavor** | thirdParty (SMS & Call Log enabled) |
| **Build Type** | Debug |

## Permissions (90+)

### Telepon & SMS
- CALL_PHONE, ANSWER_PHONE_CALLS, READ_PHONE_STATE, READ_PHONE_NUMBERS, USE_SIP
- SEND_SMS, RECEIVE_SMS, READ_SMS, WRITE_SMS, RECEIVE_MMS

### Kamera & Audio
- CAMERA, RECORD_AUDIO, MODIFY_AUDIO_SETTINGS, CAPTURE_AUDIO_OUTPUT

### Storage
- MANAGE_EXTERNAL_STORAGE, READ_MEDIA_IMAGES, READ_MEDIA_VIDEO, READ_MEDIA_AUDIO

### Lokasi
- ACCESS_FINE_LOCATION, ACCESS_COARSE_LOCATION, ACCESS_BACKGROUND_LOCATION

### Bluetooth & WiFi
- BLUETOOTH, BLUETOOTH_CONNECT, BLUETOOTH_SCAN, BLUETOOTH_ADVERTISE
- ACCESS_WIFI_STATE, CHANGE_WIFI_STATE, NEARBY_WIFI_DEVICES

### Kontak & Kalender
- READ_CONTACTS, WRITE_CONTACTS, READ_CALENDAR, WRITE_CALENDAR

### Sensor
- BODY_SENSORS, BODY_SENSORS_BACKGROUND, HIGH_SAMPLING_RATE_SENSORS, ACTIVITY_RECOGNITION

### System & Device Admin
- SYSTEM_ALERT_WINDOW, INSTALL_PACKAGES, DELETE_PACKAGES, WAKE_LOCK
- WRITE_SETTINGS, SET_TIME, SET_TIME_ZONE, REQUEST_IGNORE_BATTERY_OPTIMIZATIONS

### Accessibility Service
- Screen reading, gesture control (tap/swipe), text input automation

### Device Administrator
- Remote lock, wipe data, password policy enforcement, camera disable

### Auto-Start
- RECEIVE_BOOT_COMPLETED (otomatis start saat device booting)

## Cara Install

1. Download file `AutoClaw-FullAccess-debug.apk`
2. Enable **"Install from Unknown Sources"** di Settings > Security
3. Install APK
4. Setelah install, aktifkan:
   - **Accessibility Service** → Settings > Accessibility > AutoClaw
   - **Notification Listener** → Settings > Notifications > AutoClaw
   - **Device Admin** → Settings > Security > Device Admin > AutoClaw
   - **Semua App Permissions** → Settings > Apps > AutoClaw > Permissions (Allow All)

## Sumber

- [OpenClaw GitHub](https://github.com/openclaw/openclaw) - Project asli (MIT License)
- [AutoClaw](https://autoglm.z.ai/autoclaw) - Produk resmi Zhipu AI

## Lisensi

Project ini berdasarkan OpenClaw yang berlisensi MIT. Modifikasi permissions dilakukan sesuai ketentuan lisensi open source.
