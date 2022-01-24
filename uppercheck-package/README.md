# package-tutorial

```
dotnet new sln

dotnet new classlib -o StringLibrary

dotnet sln add StringLibrary/StringLibrary.csproj

dotnet build

dotnet new console -o ShowCase

dotnet sln add ShowCase/ShowCase.csproj


dotnet add ShowCase/ShowCase.csproj reference StringLibrary/StringLibrary.csproj
// 레퍼런스 추가 

dotnet run --project ShowCase/ShowCase.csproj

```

## 단위 테스트 프로젝트 만들기



