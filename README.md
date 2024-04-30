# Copilot-todo
Copilot Studio Plugin 을 ASP.NET API 로 구현하여 연결

## 필수 환경
.net 8.0
vscode
vscode Azure Tools extension
git

코드 복사 및 vscode 로 열기
```
git clone https://github.com/dotnetpower/Copilot-todo.git

cd Copilot-todo

code .
```

## API 프로젝트 생성 및 swagger 구성
다음 링크를 참조 해서 완성된 코드가 ./TodoApi 에 있으며, vscode 에서 `F5` 로 실행 하거나 `dotnet run` 명령으로 실행하여 확인 가능
[Tutorial: Create a minimal API with ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-8.0&tabs=visual-studio-code)

![](images/2024-04-30-16-05-31.png)

## Azure Web App 생성
azure web app 생성 후 해당 web app 에 배포
`F1` 키로 Command Palatte 열고 Deploy 로 검색해서 Deploy to Web App 선택하여 배포

![](images/2024-04-30-16-24-51.png)
## 참고





