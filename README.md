# study_geolocation_kakaomap

어제 배달의 민족을 시켰는데
지도에 배달기사님 위치가 
실시간으로 뜨는게 너무 신기해서
흉내라도 내보고싶은 마음에 찾아보았습니다
목표는 배민처럼 위치를 움직일 수는 업서도 그냥 
내위치 정도만 표시하는게 목표였습니다

html에 navigator.geolocation라는 기능으로 
손쉽게 위치를 얻어올 수있었던게 의외였습니다
그리고 카카오지도로 연동했습니다
너무 편리하게 연동되어서 카카오와 상위 개발자님들에게 감사합니다
다만
일단 웹으로 테스트해서 그런지 오차가 엄청나기도하고
이게 현업에서 쓰일까..? 라는생각이듭니다
(물론 여기서 더 튜닝을 하겠다 라는 생각은 합니다)

navigator.watchPosition를 사용하면
추적까지 가능하다는걸 알고 다시 적용했습니다

https로 만들고 포트포워딩후 핸드폰으로 테스트한결과
상당히 오차범위도 줄었고 카카오택시 처럼 나타나는걸 알았습니다
정말 신기합니다




