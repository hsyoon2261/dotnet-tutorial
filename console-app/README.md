# 릴리즈 빌드 구성 사용

``` dotnet run --configuration Release ```

 bin/Release/net6.0/publish
 
  HelloWorld.deps.json

애플리케이션의 런타임 종속성 파일입니다. 앱을 실행하는 데 필요한 .NET 구성 요소 및 라이브러리(애플리케이션을 포함하는 동적 연결 라이브러리 포함)를 정의합니다. 자세한 내용은 런타임 구성 파일을 참조하세요.

HelloWorld.dll

애플리케이션의 프레임워크 종속 배포입니다. 이 동적 연결 라이브러리를 실행하려면 명령 프롬프트에 dotnet HelloWorld.dll을 입력합니다. 앱을 실행하는 이 메서드는 .NET 런타임이 설치된 모든 플랫폼에서 작동합니다.

HelloWorld.exe(Linux에서는 HelloWorld, macOS에서는 생성되지 않음)

애플리케이션의 프레임워크 종속 실행 파일입니다. 이 파일은 운영 체제마다 다릅니다.

HelloWorld.pdb(배포에 대한 선택 사항)

디버그 기호 파일입니다. 게시된 애플리케이션 버전을 디버그해야 하는 경우에는 이 파일을 저장해야 하지만 그렇지 않으면 애플리케이션과 함께 배포할 필요가 없습니다.

HelloWorld.runtimeconfig.json

애플리케이션의 런타임 구성 파일입니다. 애플리케이션이 실행되도록 빌드된 .NET의 버전을 식별합니다. 구성 옵션을 추가할 수도 있습니다. 자세한 내용은 .NET 런타임 구성 설정을 참조하세요.


## 실행

Windows 또는 Linux에서 실행 파일을 사용하여 앱을 실행합니다.

Windows에서 .\HelloWorld.exe를 입력하고 Enter 키를 누릅니다.

Linux에서 ./HelloWorld를 입력하고 Enter 키를 누릅니다.

프롬프트에 대한 응답으로 이름을 입력하고 아무 키나 눌러 종료합니다.

모든 플랫폼에서 dotnet 명령을 사용하여 앱을 실행합니다.

dotnet HelloWorld.dll을 입력하고 Enter 키를 누릅니다.

프롬프트에 대한 응답으로 이름을 입력하고 아무 키나 눌러 종료합니다.

# 알아둘계냄

```cs
String.IsNullEmpty
String.Empty
```
