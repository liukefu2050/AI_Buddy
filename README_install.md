### 环境与构建

#### Flutter 版本

```
flutter --version
```

#### 安装依赖

```
flutter clean
flutter pub get

```

#### 更新依赖

```
flutter pub upgrade

```

#### 构建应用

```
·]>>  cd AI_Buddy

Build Android 不分包:
·]>>  flutter build apk
Build Android 分包:
·]>>  flutter build apk --target-platform android-arm,android-arm64,android-x64 --split-per-abi
Build iOS:
·]>>  flutter build ios
Build Windows:
·]>>  flutter build windows
Build Linux:
·]>>  flutter build linux
Build web:
·]>>  flutter build web
```

打包android
flutter build apk --release

#### SHA1 

keytool -v -list -keystore D:\365me\AI_Buddy\bin\release-keystore.jks
