# Project01_MES-security-System

프로젝트명 : 제철 공정 MES 보안시스템

프로젝트 목적 : 보안이 취약한 스마트팩토리들에 보안모듈을 제공함으로서 보안이슈 해결

개발팀명 : 세콤달콤(secom dalcom)

개발팀원 : 박경인(팀장), 이동희(본인), 김광일( 취업으로 중도 하차 )

사용 기술 : **Java**, gradle, JJWT, Base64, **C#**, winform, Raspberry pi, Arduino, Python, Maria DB

사용 IDE : Visual Studio 2019, MySQL Workbench

사용 DBMS : Maria DB

개발기간 : 21.08 ~ 21.10 (3개월)

맡은 역할 : 사용자UI 클라이언트 설계 및 구현 , DB 설계 , 하드웨어 설계 및 구현

## 프로젝트 설명 및 특이사항

1. 4차산업혁명, 코로나 등의 이슈들로 인하여 기술적인 패러다임의 변혁을 맞이하고 있기에 MES 관련 프로젝트를 진행
2. 학부 수준에서 실제 현업에 사용하는 기기를 접하기는 어려웠기에 라즈베리파이, 아두이노를 이용하여 하드웨어단을 가정하여 진행
3. 기기들 간의 통신에서 비롯되는 여러가지 보안 이슈들 중에서 OWASP에서 선정한 10대 보안점을 중점으로 가지고 이를 보완할 수 있도록 보안모듈이 탑재된 서버를 구현  

## 프로젝트 결과

1. Modbus, OPC 등 스마트팩토리에 사용되는 통신프로토콜은 TCP 기반 기술이며, 본 프로젝트에서 자체적으로  
   구현 프로토콜 또한 TCP 기반이기 때문에 프로젝트에서 고려한 보안점들이 실무에서도 충분히 활용될 수 있을 것으로 기대  
2. 실시간 모니터링, 실시간 제어가 가능하게 되어 편의성을 갖춘 작업환경을 구성할 수 있을 것으로 기대


## 소감 및 느낀점

6개월간 이어진 교육의 최종 프로젝트입니다.  
초기 개발 계획 세웠던것과 많이 달라졌지만 완성시키고 실사용까지 가능하게 했다는것에 의의를 두고싶습니다.  
초기에 5명의 팀원으로 시작해서 2명의 팀원이탈과 1명의 취업으로 인한 중도하차로 2명에서 개발을 진행 했지만  
쉽지만은 않았지만 서로 기운을 북돋아주며 개발을 진행했고 의미있는 결과물이 나와서 만족을 하였습니다.  
보안이라는 핵심주제로 접근하긴 했지만 좀더 mes적인 부분에 중점을 두고 개발 했던거 같습니다.

## 프로젝트 사진들

---
<Factory 초기 모델링>
![KakaoTalk_20220531_201052544_06](https://user-images.githubusercontent.com/59175200/171160724-bbf256de-79c6-455d-b774-cd4b9fb7f867.jpg)

<실제 최종 결과물>
![KakaoTalk_20220531_201052544_03](https://user-images.githubusercontent.com/59175200/171160866-8bc2f7aa-a6a3-4282-8e4e-39b587483672.jpg)

<수상판넬>
![KakaoTalk_20220531_201052544](https://user-images.githubusercontent.com/59175200/171160954-c660bf8a-3eba-47f4-9675-c54727cd321e.jpg)

<참가명찰>
![KakaoTalk_20220531_201052544_01](https://user-images.githubusercontent.com/59175200/171161024-13331b03-ac61-47ad-84dc-71ea2954cbfe.jpg)


## PPT
![슬라이드1](https://user-images.githubusercontent.com/59175200/170818772-c929a3e5-c678-4194-9879-90725b893990.PNG)

![슬라이드2](https://user-images.githubusercontent.com/59175200/170818775-c7bac814-6885-4a81-9512-806ac71af30f.PNG)

![슬라이드3](https://user-images.githubusercontent.com/59175200/170818780-66ec1a2b-4aab-4725-b2bd-dd835aab919a.PNG)

![슬라이드4](https://user-images.githubusercontent.com/59175200/170818783-ebff3dac-95f6-4f16-bd33-88f2e4868c4d.PNG)

![슬라이드5](https://user-images.githubusercontent.com/59175200/170818788-16fbcae3-698d-4e80-a09c-265002ee3db3.PNG)

![슬라이드6](https://user-images.githubusercontent.com/59175200/170818789-7defe112-ec42-4e5d-b91b-3643b30d1d25.PNG)

![슬라이드7](https://user-images.githubusercontent.com/59175200/170818790-1fd457e0-b746-4722-85d3-a5d269305852.PNG)

![슬라이드8](https://user-images.githubusercontent.com/59175200/170818795-2c8cd9e3-6243-4e6b-b523-8b09b3962edf.PNG)

![슬라이드9](https://user-images.githubusercontent.com/59175200/170818798-7fb1870f-251d-4eab-97b3-0d408ca9fab1.PNG)

![슬라이드10](https://user-images.githubusercontent.com/59175200/170818801-2a7a4c94-6cff-47f5-9aa3-a782f4694ea9.PNG)

![슬라이드11](https://user-images.githubusercontent.com/59175200/170818807-e70b75c7-1483-4c66-8af1-4f43d18afe72.PNG)

![슬라이드12](https://user-images.githubusercontent.com/59175200/170818809-a7d1743f-3d38-4bbd-868f-1a5d618b0fd6.PNG)

![슬라이드13](https://user-images.githubusercontent.com/59175200/170818812-241a2dfc-10b6-424b-a13d-f3baae0f3d03.PNG)

![슬라이드14](https://user-images.githubusercontent.com/59175200/170818815-1f7161b9-04b8-4c26-b35c-0486a6d51d2e.PNG)

![슬라이드15](https://user-images.githubusercontent.com/59175200/170818819-e3a9beb0-4d18-449b-91e5-1589aff2dd22.PNG)

![슬라이드16](https://user-images.githubusercontent.com/59175200/170818827-26e3b70a-c3d9-4ab5-ae14-53fa1bdd65f3.PNG)

![슬라이드17](https://user-images.githubusercontent.com/59175200/170818829-fa30e3e8-4867-4b63-a252-a711bae8d7e6.PNG)

![슬라이드18](https://user-images.githubusercontent.com/59175200/170818830-b17f4fed-3fd6-4812-abb1-2b223cf852ca.PNG)

![슬라이드19](https://user-images.githubusercontent.com/59175200/170818832-c2f93c2d-9639-43c5-b75c-2cab9858e654.PNG)

![슬라이드20](https://user-images.githubusercontent.com/59175200/170818834-435f52d1-2a7a-4308-865e-2f9c1a4891a7.PNG)

![슬라이드21](https://user-images.githubusercontent.com/59175200/170818837-13a75d22-863b-4210-beb0-7ebcf7e5f9d7.PNG)

![슬라이드22](https://user-images.githubusercontent.com/59175200/170818838-5534124d-0755-4fd5-a226-7e6c8664b501.PNG)
![슬라이드23](https://user-images.githubusercontent.com/59175200/170818839-ebd8b694-ba0d-4f7e-8503-d74229bcdfbf.PNG)
![슬라이드24](https://user-images.githubusercontent.com/59175200/170818843-2476aab8-6b25-4f0e-bb63-9feef57b46ef.PNG)
![슬라이드25](https://user-images.githubusercontent.com/59175200/170818844-b46f51a6-5eea-46c2-a9a8-eb07909725ca.PNG)
![슬라이드26](https://user-images.githubusercontent.com/59175200/170818846-aae3383b-5911-41db-8952-a16ac3d45622.PNG)
![슬라이드27](https://user-images.githubusercontent.com/59175200/170818847-cf5b0373-1de0-4848-8aed-a7329699fef3.PNG)
![슬라이드28](https://user-images.githubusercontent.com/59175200/170818848-f25e0bc0-8670-4c51-abe4-c82421354d93.PNG)
![슬라이드29](https://user-images.githubusercontent.com/59175200/170818850-06fa74dd-d466-4cf1-9fbe-b4d7c85e6a18.PNG)
![슬라이드30](https://user-images.githubusercontent.com/59175200/170818851-7caf159b-8dfc-43cb-83ed-438680e9f6e5.PNG)
![슬라이드31](https://user-images.githubusercontent.com/59175200/170818854-55d1bcf8-6354-41d1-a853-5c87f3b102bd.PNG)
![슬라이드32](https://user-images.githubusercontent.com/59175200/170818855-369d237e-43f5-4969-b17c-6c3c67d36753.PNG)
![슬라이드33](https://user-images.githubusercontent.com/59175200/170818858-babf94ad-7078-4be7-9556-f6cdff6c8b51.PNG)


https://user-images.githubusercontent.com/59175200/170818997-4d317ca3-1de1-4d2d-9aaa-77838b4da9b9.mp4


![슬라이드34](https://user-images.githubusercontent.com/59175200/170818859-dbb01d45-637f-43be-b95f-d002d078aab1.PNG)
![슬라이드35](https://user-images.githubusercontent.com/59175200/170818861-97a4658b-a4e8-46e0-b4e0-f3a62d08e503.PNG)
![슬라이드36](https://user-images.githubusercontent.com/59175200/170818862-f2f920b6-933a-491b-9865-637c04d38943.PNG)
![슬라이드37](https://user-images.githubusercontent.com/59175200/170818864-5926a9ee-8b47-41ea-bb9d-81817e3ac13f.PNG)










