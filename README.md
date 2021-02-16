# HTTP_Volley
<h3>2020.12.08</h3>
안드로이드 Volley라이브러리를 사용하여
모바일환경 HTTP통신 예제코드 작성
<br>
(내부API 테스트용)

<br>
<img src="https://user-images.githubusercontent.com/56987664/101435272-697e0c00-394f-11eb-831a-06bc2f823c88.png" width="30%">

GET, POST방식 구현
<br>
GET방식은 URL만 바꿔서 사용 가능

<h4><2020.12기준 설정 방법></h4>
  
[build.gradle]<br>
implementation 'com.android.volley:volley:1.1.1'

[AndroidMaifest.xml]<br>
uses-permission android:name="android.permission.INTERNET" <br>
uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" <br><br>
application android:useCleartextTraffic="true"

[class파일 추가]<br>
import com.android.volley.RequestQueue;<br>
public class AppHelper {
    public static RequestQueue requestQueue;
}
