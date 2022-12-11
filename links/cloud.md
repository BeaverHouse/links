# Cloud 관련

## AWS 배포
- https://facerain.club/fastapi-nginx/
- https://velog.io/@server30sopt/EC2-HTTPS%EB%A1%9C-%EC%97%B0%EA%B2%B0%ED%95%98%EA%B8%B0

인바운드 규칙, 포트번호 주의   
대상 그룹의 포트는 실제 서비스 포트여야 함 (ex. FastAPI : 8000)   
**그런데 nginx로 port를 바꿔 놓아서 추후 확인 필요함**