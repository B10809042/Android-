# Android-
登入、註冊
  
	登入和註冊這邊我是用Fragment來做的，然後註冊是連接room的資料庫，因為我一開始沒看好要用firebase來去做認證，我就直接自己做一個會員的資料庫了，註冊後會在下面的recylerview顯示有註冊過的帳號，防止相同註冊，和提示註冊成功，而在登入畫面我沒做得很好，我沒成功讓他去連接資料庫變成可以去驗證身分，但時間有點不夠了，所以我最後是讓登入鍵按下去就會intent到另一個activity。
		

![image](https://user-images.githubusercontent.com/84411177/207587895-78e97512-750f-4d9c-82b3-b31987cc1681.png)
![image](https://user-images.githubusercontent.com/84411177/207587903-5a339026-69d1-4f9a-889f-b4be154d3986.png)



![image](https://user-images.githubusercontent.com/84411177/207587953-f30c3b84-6588-458a-b64a-78165a740dca.png)
在開啟程式的時候會要求使用者開始藍芽並允許程式使用定位的功能。






主頁
  ![image](https://user-images.githubusercontent.com/84411177/207587969-c2545359-4268-4a93-8a2e-3bf390d8d0a1.png)
![image](https://user-images.githubusercontent.com/84411177/207587974-f7111d5a-0db9-4f8f-bb64-c7361970d951.png)

	進入之後就會開始偵測裝置附近的藍芽設備，並且可以按下停止掃描，停止使用，在進入的時候APP就會通知程式正在啟動。
