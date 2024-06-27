# 기본 설치 - 가상환경 ( 포이트리 )
    - 포이트리 설치
    ```bash
    poetry new .
    ```

    - 패키지설치 ( 장고 필로우 클린업 올오스 htmx)
      - django
        - 파이썬 웹 프레임 워크
      - pillow
        - python 이미지 라이브러리
      - django-cleanup
        - django의 파일과 이미지 관리, 모델 인스터스가 삭제되면 관련 파일도 자동삭제 기능
      - django-allauth
        - 소셜 인증과 계정 관리 기능
      - django-htmx
        - htmx를 django 내에서 사용가능하게함.
    ```bash
    poetry add django pillow django-cleanup django-allauth django-htmx
    ```
