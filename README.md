### 1. Dockerfile 
    
- ����ȯ��
    - Dockerfile.dev
- �ȯ��
    - Dockerfile

### 2. Docker-compose 
    
- version
- services
    - frontend
    - backend
    - nginx
    - mysql

### 3. Github Push 
    
- Feature Branch
- Master Branch

### 4. Travis CI 
    
- �׽�Ʈ �ҽ� ����
- �׽�Ʈ ����
- ������ Dockerfile�� �̿��ؼ� Image ����(����)
- �̹��� ���� �� Docker Hub�� ����

### 5. Docker Hub
- Travis CI���� ����� �̹����� ����
- AWS Elastic Beanstalk���� ���������� �Ҷ� ����

### 6. AWS ElasticBeanStalk
- Travis CI���� ����� �̹����� �̿��ؼ� ����


## Nginx�� Proxy�� �̿��� ����


- Client ->
- Nginx(Proxy) ->
- server
    - Frontend(Nginx(Serving) -> JS,HTML,CSS)
    - Server(Backend)+Mysql


