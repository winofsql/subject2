- ### [.NET とは何ですか?](https://docs.microsoft.com/ja-jp/dotnet/core/introduction#net-history)
  - ### [.NET の歴史](https://docs.microsoft.com/ja-jp/dotnet/core/introduction#net-history)
  > 2002 年に、Microsoft によって、Windows アプリを作成するための開発プラットフォームである .NET Framework がリリースされました。
  > 現在、.NET Framework はバージョン 4.8 であり、引き続き Microsoft によって完全サポートされています。
  >
  > 2014 年に、Microsoft によって、.NET Framework のクロスプラットフォームのオープンソースの後継版として .NET Core が導入されました。
  > この新しい .NET の実装では、バージョン 3.1 までは .NET Core という名前が保持されていました。
  > .NET Core 3.1 の次のバージョンからは .NET 5 という名前になりました。  

  [![image](https://user-images.githubusercontent.com/1501327/186354659-f18c546e-5dc9-4656-9225-77ea37672407.png)](https://dotnet.microsoft.com/ja-jp/download/dotnet)

- ### dotnet テンプレート
```bat
> dotnet new --list

テンプレート名                                短い名前             言語        タグ
--------------------------------------------  -------------------  ----------  --------------------------
ASP.NET Core Empty                            web                  [C#],F#     Web/Empty
ASP.NET Core gRPC Service                     grpc                 [C#]        Web/gRPC
ASP.NET Core Web API                          webapi               [C#],F#     Web/WebAPI
ASP.NET Core Web App                          webapp,razor         [C#]        Web/MVC/Razor Pages
ASP.NET Core Web App (Model-View-Controller)  mvc                  [C#],F#     Web/MVC
ASP.NET Core with Angular                     angular              [C#]        Web/MVC/SPA
ASP.NET Core with React.js                    react                [C#]        Web/MVC/SPA
Blazor Server App                             blazorserver         [C#]        Web/Blazor
Blazor WebAssembly App                        blazorwasm           [C#]        Web/Blazor/WebAssembly/PWA
dotnet gitignore ファイル                     gitignore                        Config
dotnet ローカル ツール マニフェスト ファイル  tool-manifest                    Config
EditorConfig ファイル                         editorconfig                     Config
global.json ファイル                          globaljson                       Config
MSTest Test Project                           mstest               [C#],F#,VB  Test/MSTest
MVC ViewImports                               viewimports          [C#]        Web/ASP.NET
MVC ViewStart                                 viewstart            [C#]        Web/ASP.NET
NuGet Config                                  nugetconfig                      Config
NUnit 3 Test Item                             nunit-test           [C#],F#,VB  Test/NUnit
NUnit 3 Test Project                          nunit                [C#],F#,VB  Test/NUnit
Protocol Buffer File                          proto                            Web/gRPC
Razor Class Library                           razorclasslib        [C#]        Web/Razor/Library
Razor Component                               razorcomponent       [C#]        Web/ASP.NET
Razor Page                                    page                 [C#]        Web/ASP.NET
Web 構成                                      webconfig                        Config
Windows フォーム アプリ                       winforms             [C#],VB     Common/WinForms
Windows フォーム クラス ライブラリ            winformslib          [C#],VB     Common/WinForms
Windows フォーム コントロール ライブラリ      winformscontrollib   [C#],VB     Common/WinForms
Worker Service                                worker               [C#],F#     Common/Worker/Web
WPF アプリケーション                          wpf                  [C#],VB     Common/WPF
WPF カスタム コントロール ライブラリ          wpfcustomcontrollib  [C#],VB     Common/WPF
WPF クラス ライブラリ                         wpflib               [C#],VB     Common/WPF
WPF ユーザー コントロール ライブラリ          wpfusercontrollib    [C#],VB     Common/WPF
xUnit Test Project                            xunit                [C#],F#,VB  Test/xUnit
クラス ライブラリ                             classlib             [C#],F#,VB  Common/Library
コンソール アプリ                             console              [C#],F#,VB  Common/Console
ソリューション ファイル                       sln                              Solution
```
