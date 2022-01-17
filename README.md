
# Warning
재난문자 푸시알람 

## 기능 상세
- APNs(Apple Push Notification Service)를 통해서 기기에서 알람을 관리 할 수 있습니다. 
- Firebase Console에서 FCM을 통해 특정 또는 불특정 사용자에게 푸시 알람을 보낼 수 있습니다. 

## 활용기술 
- APNs
- Firebase Cloud Messaging 

## DEMO
**empty**

## 배운 내용

#### APN
> Apple Push Notification Service 

- **알림관리**
	
	각 기기의 상태를 확인하여 상태에 따라서 알람을 저장후에 보내주고 최신의 알림 상태를 관리 

- **보안관리**
![스크린샷 2022-01-17 오후 8 51 20](https://user-images.githubusercontent.com/51107183/149765017-f00184c1-8ea5-440a-8f2a-cd09e28d5d44.png)

- Connection Trust 
![스크린샷 2022-01-17 오후 8 54 35](https://user-images.githubusercontent.com/51107183/149765258-290598a8-5d8e-4e46-a0b1-265769b9185b.png)

- Provider-to-APNs connetion Trust 
![스크린샷 2022-01-17 오후 8 56 08](https://user-images.githubusercontent.com/51107183/149765394-74e091e1-f19d-4087-997c-4df305d4d956.png)

- APNs-to-device Connection Trust 
![스크린샷 2022-01-17 오후 8 56 47](https://user-images.githubusercontent.com/51107183/149765480-229b1a06-047e-4f77-8ea9-449c28907ffb.png)

- Divce Token Trust 
 ![스크린샷 2022-01-17 오후 8 57 27](https://user-images.githubusercontent.com/51107183/149765566-4d0a9560-4010-4e44-a243-e72bfc7dbef0.png)
 
 #### Firebase Cloud Messaging 
 
##### 주요기능
 
- **원격 알림 메시지 전송**
	
	사용자에게 표시되는 알림 메시지를 실시간 또는 예약전송 
	
- **다양한 메시지 타겟팅**
 
	단일 기기, 기기그룹, 주제를 구독한 기기
 	
- **발송 메시지 저장, 관리**

	알림 내용, 상태, 플랫폼, 최종 전송 시간, 열람률 관리 
	

