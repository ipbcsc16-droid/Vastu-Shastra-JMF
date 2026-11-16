JMF Vastu Shastra v2.0 — Android Studio project

এটি APK-ready Android Studio source project, সরাসরি APK ফাইল নয়।
APK তৈরি:
1) Android Studio-তে এই ZIP Extract করে Open করুন।
2) Gradle Sync শেষ হতে দিন (internet লাগবে)।
3) Build > Build Bundle(s) / APK(s) > Build APK(s) চাপুন।
4) APK সাধারণত app/build/outputs/apk/debug/app-debug.apk-এ পাবেন।

ফিচার:
- Bengali + English interface
- PDF upload ও preview
- Automatic PDF text/room-label scan (PDF.js CDN; internet connection দরকার)
- Manual room direction verification
- Preliminary Vastu report এবং TXT report download

সীমাবদ্ধতা:
- Automatic scan PDF text/labels পড়ার চেষ্টা করে; floor-plan drawing থেকে room-এর compass direction বা North arrow নির্ভুলভাবে নিজে নির্ধারণ করে না।
- Scan fail হলে manual entry ব্যবহার করুন।
- Vastu নির্দেশনা ঐতিহ্যগত বিশ্বাসভিত্তিক; engineering, structural safety বা municipal approval নয়।
