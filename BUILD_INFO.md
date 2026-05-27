# QuranMaker Debug APK

## Build Info
- **App**: NurMontage - Quran Video Maker
- **Package**: hazem.nurmontage.videoquran
- **Version**: 6.7.1-nurmontage4kb-debug
- **Version Code**: 21000106
- **Build Type**: Debug
- **Min SDK**: 24 (Android 7.0)
- **Target SDK**: 35 (Android 15)
- **Compile SDK**: 35
- **APK Size**: ~38MB

## What's Included
- ✅ All resources (layouts, drawables, fonts, Quran text)
- ✅ Base classes (QuranMakerApp, BaseActivity, EdgeToEdge)
- ✅ Models (16 data classes)
- ✅ Custom Views (12 views)
- ✅ Utils (6 utility classes)
- ✅ Constants (Common, IpadType, ResizeType)

## What's NOT Included (Phase 0 stub - no real functionality)
- ❌ Activity implementations (only stubs declared in Manifest)
- ❌ Fragment implementations
- ❌ FFmpeg engine
- ❌ Billing system
- ❌ Quran search engine
- ❌ Audio processing

## Note
This APK will crash on launch because Activities referenced in the Manifest 
have no implementation classes yet. This is a Phase 0 build to verify 
that resources compile correctly.

## How to Install
```bash
adb install app-debug.apk
```
