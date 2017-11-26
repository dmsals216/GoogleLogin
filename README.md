# Google Sign-in 구현

#### https://developers.google.com/identity/sign-in/android/sign-in 

## 로그인

1. 아래의 버튼을 레이아웃에 맞춰 넣는다.

![](/image/1.png)

2. Activity 안에서 다음과 같이 생성한다.

![](/image/2.png)

3. 버튼에 OnClickListener를 달아준다.

4. 그 안에 구글에서 제공하는 Intent를 생성해서 startActivityForResult를 해준다.

![](/image/3.png)

5. 아래의 코드를 작성한다

![](/image/4.png)

6. 로그인 성공을 하면 intent를 생성해 자신이 원하는곳으로 이동하게 코딩을 한다.

### 팁 : 위의 account 안에는 구글에서 제공하는 로그인에 대한 정보를 가져올 수 있다.

## 로그아웃

로그인 화면과 다른 액티비티에서 버튼을 만들고 다음과 같은 코드를 넣는다.

![](/image/6.png)