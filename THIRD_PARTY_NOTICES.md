# 외부 구성요소 안내 v0.1

AI Snap의 소스 사용권과 아래 구성요소의 사용권은 별개입니다. 각 구성요소의 저작권·라이선스·고지를 유지해야 합니다. Google SDK 바이너리나 서비스가 AI Snap의 소스 라이선스로 재허가되는 것은 아닙니다.

| 구성요소 | 사용 범위 | 원문 |
| --- | --- | --- |
| .NET / WPF / ASP.NET Core | Windows 실행과 HTTPS 수신 | [dotnet/runtime](https://github.com/dotnet/runtime/blob/main/LICENSE.TXT), [WPF](https://github.com/dotnet/wpf/blob/main/LICENSE.TXT), [ASP.NET Core](https://github.com/dotnet/aspnetcore/blob/main/LICENSE.txt) 및 런타임 ThirdPartyNotices |
| AndroidX Activity/Core/RecyclerView/CameraX/ExifInterface | Android UI·카메라·이미지 회전 | [AndroidX 라이선스](https://android.googlesource.com/platform/frameworks/support/+/androidx-main/LICENSE.txt) 및 각 Maven 패키지의 고지 |
| ZXing core 3.5.3 | QR 인식 | [ZXing 라이선스](https://github.com/zxing/zxing/blob/zxing-3.5.3/LICENSE) |
| Google ML Kit Document Scanner 16.0.0 | 실험적 문서 보정 | [ML Kit 약관·개인정보](https://developers.google.com/ml-kit/terms), [Google APIs 약관](https://developers.google.com/terms) |
| Gradle Wrapper | 소스 빌드 | [Gradle 라이선스](https://github.com/gradle/gradle/blob/master/LICENSE), Wrapper 파일 내 고지 |

`licenses/Apache-2.0.txt`에 원문을, `licenses/MLKit-DocumentScanner-16.0.0.txt`에 Google SDK AAR에 포함된 외부 구성요소 고지 원본을 보존합니다. Windows 패키지는 실제로 게시한 .NET 런타임 버전의 LICENSE와 THIRD-PARTY-NOTICES도 포함합니다.

실제 의존 버전은 `android/app/build.gradle` 및 .NET 프로젝트에 고정합니다. 이 목록만으로 각 구성요소의 원문을 대체하지 않습니다.
