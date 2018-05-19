# 주피터허브 사용법

본 사이트는 국가수리과학연구소에서 제공하는 사이트입니다.

내부적인 구현에 대한 부분은 다음 [링크](https://github.com/jupyternims/docker-image)를 참조하시기 바랍니다.

## 기본적인 사용법

1. [jupyter.nims.re.kr](https://jupyter.nims.re.kr) 사이트 접속

<img width="626" alt="2018-05-19 5 48 52" src="https://user-images.githubusercontent.com/1378925/40266834-1749d542-5b8d-11e8-80ae-7a40b898f3a8.png">

2. 'Sign in with Github' 버튼 클릭하여 Github 계정으로 로그인  
(Github 계정이 없는 경우, 계정 생성하여야 합니다.)  
밑에 [Github 가입하기](https://github.com/skycwy223/jupyterhub-nims/blob/master/How%20To%20Use.md#github-%EA%B0%80%EC%9E%85%ED%95%98%EA%B8%B0) 참조

<img width="352" alt="2018-05-19 5 49 06" src="https://user-images.githubusercontent.com/1378925/40266844-385d1ef6-5b8d-11e8-92e6-75c19768b57e.png">

3. 'Authorize jupyternims' 버튼 클릭

<img width="352" alt="2018-05-14 4 00 33" src="https://user-images.githubusercontent.com/1378925/40267037-f843b0d8-5b90-11e8-9a5a-b213c8fcd004.png">

4. 'Start My Server' 버튼 클릭

<img width="626" alt="2018-05-19 6 23 00" src="https://user-images.githubusercontent.com/1378925/40267093-bd5b9444-5b91-11e8-9ec7-1e8c9f589b73.png">

5. 이후엔 일반적인 주피터 노트북 사용법과 동일합니다.

<img width="626" alt="2018-05-19 6 24 35" src="https://user-images.githubusercontent.com/1378925/40267102-f52abc06-5b91-11e8-935f-6e20bc925b66.png">

## Github 가입하기

Github 가입은 일반적인 사이트에서 회원가입하는 것과 비슷합니다.

[https://github.com](https://github.com) 사이트 접속

![](https://user-images.githubusercontent.com/1378925/40266497-fb452794-5b86-11e8-92c9-5aa99682b418.png)

사용자 이름과 이메일 그리고 비밀번호를 입력하면 가입이 가능합니다.

입력한 뒤에 Sign up 버튼을 누르시면 아래와 같은 화면이 나옵니다.

저희는 개인이 사용할 것이므로 "Choose your personal plan"에 기본 선택되어 있는 Free로 선택을 합니다.

그 후 Continue 버튼을 눌러 다음 스텝을 진행합니다.

![join_step2](https://user-images.githubusercontent.com/1378925/40266731-5a586832-5b8b-11e8-9a10-8de9ff2a6632.png)

Step 3는 간단한 설문조사입니다.

귀찮으신 경우 "skip this step"을 통해 넘어가셔도 무방합니다.

![join_step3](https://user-images.githubusercontent.com/1378925/40266736-8bcd69e4-5b8b-11e8-8130-768c45693cea.png)

여기까지 완료하셨다면 다음과 같은 화면이 나올 것입니다.

![sign up submit](https://user-images.githubusercontent.com/1378925/40266766-d896020e-5b8b-11e8-8672-34571a458074.png)

이제 가입할때 사용하셨던 이메일을 사용해 인증을 해주셔야 합니다.

가입할 때 사용하셨던 이메일에 접속하여 Github로부터 온 메일을 클릭, 메일 안에 있는 링크를 클릭하시면 인증이 완료됩니다.

그리고 제대로 링크를 클릭하셨다면 다음과 같은 이메일 인증이 완료된 화면이 보이게 됩니다.

![sign_up_complete](https://user-images.githubusercontent.com/1378925/40266785-24702272-5b8c-11e8-8135-77bb2d035e54.png)

## 주피터 노트북 사용법

위의 1~4 과정을 거쳐 로그인을 하게 되면 디렉토리 리스트가 보이게 된다.

#### 새로운 파이썬 파일 만들기

오른쪽 상단에 있는 'New' 버튼 클릭 -> 'Python3' 선택

## 서비스 스펙

본 서비스는 국가수리과학연구소에서 제공하는 주피터 노트북/허브의 퍼블릭 서비스

**지원 언어**

C, Julia, Octave, Python3, R, Ruby, SageMath 

**서버 자원**
* CPU : Intel(R) Xeon(R) CPU E5-2630 v3 @ 2.40GHz (2ea, 8 cores/CPU, 2 threads/core, Total 32 Threads)  
* RAM : 64GB Shared  
* HDD : 3.6TB Shared  

## 주의사항

매주 월요일 1:00AM ~ 4:00AM 정기적인 서버 재부팅 있음  
(이 시간에 돌던 프로그램은 멈출 수 있습니다.)

