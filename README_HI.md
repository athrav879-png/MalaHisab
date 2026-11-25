# Mala Hisab Android App

Yeh Android Studio project aapke diye gaye `Mala aur Guchhi Hisab` HTML software ko Android WebView app mein chalata hai.

## App mein
- Jama / Nikasi entry aur 25 Mala = 1 Guchhi hisaab
- Karigar aur Dukandar naam manage karna
- Month-wise report aur register
- WhatsApp report share
- CSV/Excel-compatible export
- JSON backup save aur load
- Hindi voice announcement (device/browser support par nirbhar)

## APK banane ka tareeka
1. Android Studio install karein.
2. `MalaHisabAndroid` folder ko Android Studio mein **Open** karein.
3. Gradle sync complete hone dein (internet zaroori hai, pehli baar Android Gradle Plugin download hoga).
4. **Build > Build Bundle(s) / APK(s) > Build APK(s)** chunein.
5. APK `app/build/outputs/apk/debug/app-debug.apk` mein milega.

Minimum Android: 6.0 (API 23). Project source code hai; is environment mein Android SDK/Gradle installed na hone ke karan ready APK compile nahi kiya gaya.

## Data
Entries app ke WebView local storage mein device par rehti hain. App data clear/uninstall karne se pehle **Save** se JSON backup lein.
