## Vercel ##

https://user-images.githubusercontent.com/63283076/186577310-13f9df31-1dbc-4e96-a4ed-0e67cbd27317.mov


내 작업 
- ver1
   영상
    -  구현방법
        백그라운드 크기를 2배로 늘리고 백그라운드를 이동시킨다
        생각보다 많이 부자연스러웠다 (실패)

- ver2
    영상
    -   구현 방법
        글자 위에 동일 한 글자를 올려서 opacity를 조정한다 
        아마 vercel에서 이런식으로 구현한듯 하다
        (개발자 도구 element를 보면 span태그 두개를 겹쳐 두었다)
    
    -
    
    
    ##### 학습 #####
    
    1. background-clip
        백그라운드 클립은 배경을 어떤 영역에 채울지
        
    2. linear-gradient(방향, 색상1, 색상2 ....)
    linear-gradient를 활용하면 그라데이션 배경을 만들 수 있다.
    background, background-image 모두 적용 가능하다

        ```
            p{
                background-image: linear-gradient(to right, #7928ca, #ff0080);
            }   
            
            p{
                background: linear-gradient(to right, #7928ca, #ff0080);        
        ```
        
    3. background-size
    배경 사이즈를 요소에 맞춰서가 아닌 css에서 조정 할 수 있다.
    또한 이를 통해 애니메이션을 구현할수도 있다.
    
    4. webkit
    웹 브라우저를 만드는 데 기반을 제공하는 오픈 소스 응용 프로그램 프레임워크
    css에서는 크로스 브라우징을 위해 필요하다
    
        webkit 이외에도
    webkit = 크롬, 사파리
    moz = 파이어폭스
    o = 오페라
    ms = 익스플로러
    
        다양한 프레임 워크가 있다. 
        
    
##### 참조 #####
https://vercel.com/
https://developer.mozilla.org/ko/docs/Web/CSS/background-size
https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Images/Using_CSS_gradients
https://webclub.tistory.com/621



