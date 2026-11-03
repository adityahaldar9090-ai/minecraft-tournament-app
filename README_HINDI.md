# Minecraft Tournament Android App — Starter

यह Android-only Flutter starter project है।

## अभी क्या मौजूद है
- White + Green theme
- Login screen
- Signup screen: First Name, Last Name, Username, Mobile Number, Email, Password, Referral Code
- Login/Signup buttons अभी prototype हैं

## अभी क्या नहीं जुड़ा है
- Firebase Authentication / Firestore
- Notifications
- Discord invite URL
- Tournament backend
- Admin panel
- APK build

## APK बनाने के लिए
1. Computer पर Flutter SDK और Android Studio install करें।
2. इस folder को extract करें।
3. Terminal में इस folder के अंदर चलाएँ:
   `flutter pub get`
   `flutter create .`
   `flutter run`
4. APK बनाने के लिए:
   `flutter build apk --release`

ध्यान दें: `flutter create .` Android platform files बनाएगा। Firebase जोड़ने से पहले Firebase project और Android app configuration की जरूरत होगी।

**Package name:** अभी Flutter का default/example package name इस्तेमाल होगा। Publish करने से पहले इसे अपने unique package ID में बदलना होगा।

यह starter project है, तैयार या प्रकाशित APK नहीं।
