# আমার বেতন — GitHub APK Build

এই project-টি GitHub Actions দিয়ে Android APK বানানোর জন্য প্রস্তুত করা হয়েছে।

## GitHub-এ কী করতে হবে

1. ZIP extract করুন।
2. Extract করা folder-এর **ভেতরের সব file/folder** GitHub repository-এর root-এ upload করুন।
3. Commit changes করুন।
4. GitHub repository → **Actions** → **Build Amar Betan APK** খুলুন।
5. প্রথমবার workflow permission চাইলে **Enable workflows** দিন।
6. **Run workflow** চাপুন।
7. Build শেষ হলে workflow run খুলে নিচে **Artifacts** থেকে `Amar-Betan-APK` download করুন।
8. ZIP extract করলে `app-debug.apk` পাবেন।

## গুরুত্বপূর্ণ

- Android Studio আপনার কম্পিউটারে লাগবে না; APK build GitHub Actions-এ হবে।
- এই workflow debug APK বানায়।
- আপনার মূল PWA data local/offline storage-এ থাকে।
