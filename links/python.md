# Python 관련

## FastAPI
1. ASGI, WSGI   
https://blog.neonkid.xyz/249   
WSGI에는 gunicorn, ASGI에는 uvicorn이 있다.   
gunicorn + uvicorn worker를 사용할 경우   
gunicorn의 멀티프로세스와 uvicorn의 ASGI 특성을 모두 활용할 수 있다.   
- https://github.com/tiangolo/uvicorn-gunicorn-fastapi-docker#gunicorn     
- https://fastapi.tiangolo.com/deployment/server-workers/

## 기타
2. Python의 정수 overflow   
https://m.blog.naver.com/complusblog/221158544120