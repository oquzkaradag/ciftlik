# Koyun Çiftliği: Android projesi

Bu klasör, oyunu (app/src/main/assets/index.html) bir Android uygulamasına saran hazır projedir. Uygulama internetsiz çalışır ve ilerlemeyi telefonda otomatik kaydeder.

## Yol A: Android Studio ile (bilgisayar)
1. Android Studio’yu kurun: developer.android.com/studio
2. File > Open ile bu klasörü açın. İlk açılışta Gradle senkronizasyonu için internet gerekir.
3. Build > Build Bundle(s) / APK(s) > Build APK(s)
4. APK dosyası: app/build/outputs/apk/debug/app-debug.apk

## Yol B: GitHub ile (bilgisayara program kurmadan)
1. Ücretsiz bir GitHub hesabı açıp yeni bir depo (repository) oluşturun.
2. Bu klasörün içindekileri, .github klasörü dahil, depoya yükleyin.
3. Actions sekmesinde "APK" işi kendiliğinden çalışır. Bitince Artifacts bölümündeki koyun-ciftligi-apk dosyasını indirin.

## Kurulum ve paylaşma
APK dosyasını telefona gönderip açın (Bilinmeyen kaynaklardan kuruluma izin vermeniz istenir). Aynı dosyayı başkalarına gönderebilirsiniz.

Google Play’de yayınlamak için imzalı sürüm (release) ve Google Play geliştirici hesabı gerekir.

## Oyunu değiştirmek
app/src/main/assets/index.html dosyasını düzenleyip APK’yı yeniden üretin.
