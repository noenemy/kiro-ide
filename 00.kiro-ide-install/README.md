
## 워크샵 환경 접속하기


1. 진행자의 안내에 따라 웹 브라우저에서 워크샵 스튜디오 접속 URL에 접속합니다.

2. Email one-time passoword (OTP) 버튼을 클릭합니다.

3. 본인의 사용 가능한 이메일 계정을 작성하고 Send Code 버튼을 클릭합니다.

4. 이메일 수신함에서 제목이 Your one-time passcode 이메일을 확인하고 passcode를 복사합니다. 복사한 passcode를 아래와 같이 붙여넣기 한 뒤, Sign in 버튼을 누릅니다.

5. 로그인이 성공적으로 이루어지면 Review and Join 화면이 보여집니다.

6. 스크롤을 내려 Terms and Conditions 내용을 확인 한 뒤, "I agree with the Terms and Conditions"에 체크하고, Join event 버튼을 눌러 워크샵 이벤트를 시작합니다.

7. 워크샵 화면으로 전환 되었습니다.

8. 좌측 하단의 AWS account assesss 메뉴에서 CLI 환경을 위한 Access Key와 Secret Access Key, Session Token 정보를 복사합니다.

![kiro](https://github.com/noenemy/kiro-ide/blob/main/00.kiro-ide-install/images/get-credentials.png)  


![kiro](https://github.com/noenemy/kiro-ide/blob/main/00.kiro-ide-install/images/credentials.png)  

## Kiro IDE 설치하기
     
  1. kiro.dev (https://kiro.dev)에서 설치 파일을 다운로드합니다.                                            
  2. 다운로드한 파일을 열고 운영체제(Windows, macOS, Linux)에 맞는 설치 안내를 따릅니다.                    
  
  3. Kiro IDE를 열고 코딩을 시작하세요! 

> [!WARNING]
> 로컬에 Kiro IDE 를 설치해서 실습할 경우 AWS CLI 에 구성되어 있는 연결계정으로 사용할 수 있습니다. 또한 로컬의 파일과 환경을 변경할 수 있습니다.

---

## Kiro IDE에서 AWS 명명된 프로파일 설정하기                                                              
                                                                                                            
  ### Step 1: Kiro IDE 실행                                                                                 
  Kiro IDE를 실행합니다. 프로젝트 폴더를 열거나 새 폴더를 생성합니다.                                       
                                                                                                            
  ### Step 2: 터미널 열기                                                                                   
  Kiro IDE 상단 메뉴에서:                                                                                   
  - **Terminal → New Terminal** 클릭                                                                        
  - 또는 단축키: `` Ctrl+` `` (macOS: `` Cmd+` ``)                                                          
                                                                                                            
  하단에 터미널 패널이 열립니다.                                                                            
                                                                                                            
  ### Step 3: AWS CLI 설치 확인                                                                             
  ```bash                                                                                                   
  aws --version
  ```                                                                                             
                                                                                                            
  버전 정보가 나오면 설치되어 있는 것입니다. 나오지 않으면 먼저 AWS CLI를 설치                              
  (https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)합니다.                    
                                                                                                            
  Step 4: 앞에서 워크샵 이벤트 페이지에서 복사한 AWS Access Key 및 Session Token 정보를 터미널에 붙여넣기 합니다. (이 토큰 정보는 현재 Terminal 창에서만 유효합니다. 새로운 터미널에서 사용하려면 다시 붙여넣기 해야 합니다.)
                                  
  Step 5: 연결 확인                                                                                         
  ```bash                                                                                           
  aws sts get-caller-identity                                                                               
```
                                                                                                          
  정상이면 아래와 같이 출력됩니다:                                                                                                 
 ![kiro](https://github.com/noenemy/kiro-ide/blob/main/00.kiro-ide-install/images/kiro-profile.png)  


 이제 Kiro IDE를 이용해서 실습을 진행할 준비가 되었습니다!
 Happy Coding!!!



