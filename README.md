
# PACS data autolabeling project ๐ก

[![์๊ฐ์์](https://img.youtube.com/vi/ToVcqdqfQKM/0.jpg)](https://youtu.be/ToVcqdqfQKM)  
(YouTube)  

- 2021 ๋๊ตญ๋ํ๊ต ์ ๋ณดํต์ ๊ณตํ๊ณผ ์บก์คํค๋์์ธ ํ๋ก์ ํธ
- ๋ฌด๋ฃ ๋ฐ ์นํ์ด์ง๋ก ์ ๊ณต๋๋ ํตํฉ ๋ผ๋ฒจ๋ง ์ํฌํธ ์์คํ  
- ์๋ ๋ผ๋ฒจ๋ง ๋ฐ ์คํ  ๋ผ๋ฒจ๋ง(prototype) ์ ๊ณต  

## How to Use โ

[![์ค๋ช์์](https://img.youtube.com/vi/TdMTETOsOtw/0.jpg)](https://youtu.be/TdMTETOsOtw)  
(YouTube)  

## Installation Guide ๐ป

> ๋ณธ ํ๋ก์ ํธ๋ chrome browser์ ์ต์ ํ๋์ด ์์ต๋๋ค.  

### <_windows_>

-   Docker desktop, git, chrome์ ์ค์นํฉ๋๋ค.

- ์์ค์ฝ๋๋ฅผ clone ํฉ๋๋ค. [GitHub repository](https://github.com/sonagi784/PACS_autolabeling_project).
```sh
git clone https://github.com/sonagi784/PACS_autolabeling_project
cd cvat
```
- ์ด๋ฏธ์ง๋ฅผ ์์ฑํ๊ณ  docker container๋ฅผ ์คํํฉ๋๋ค.
```sh
docker-compose -f docker-compose.yml -f docker-compose.dev.yml build
docker-compose up -d
```
- ์๋์ command๋ก ์ํผ์ ์ ๋ฅผ ์ถ๊ฐํ  ์ ์์ต๋๋ค.

```sh
winpty docker exec -it cvat bash -ic 'python3 ~/manage.py createsuperuser'
```
-  ํฌ๋กฌ ๋ธ๋ผ์ฐ์ ๋ฅผ ์ด๊ณ  localhost:8080์ผ๋ก ๋ค์ด๊ฐ ๋ก๊ทธ์ธํ์ฌ ์ฌ์ฉํฉ๋๋ค.


## Built With ๐

### <_Team_>

๐จ [๊น๋ํ](https://github.com/ghkdnswl)  
- ๋ฐ์ดํฐ ์์ง ๋ฐ ๋ณด๊ณ   

๐จ [์ ์งํ](https://github.com/sonagi784)  
- ์น ๊ฐ๋ฐ  

๐จ [์ด์ถฉํ](https://github.com/ChungHwan0428)  
- ์น ๊ฐ๋ฐ, ์คํ ๋ผ๋ฒจ๋ง ๋ชจ๋ธ ๊ฐ๋ฐ  

๐จ [์ด์ง์](https://github.com/ljs-ai)  
- ๋ผ๋ฒจ๋ง ๋ฐ์ดํฐ ์ ์  

### <_Mentorship_>

๐ด [๋ฐ์์ฐฌ](https://kr.linkedin.com/in/%EC%9D%80%EC%B0%AC-%EB%B0%95-a9a65b146)  
- ๋๊ตญ๋ํ๊ต ์ ๋ณดํต์ ๊ณตํ๊ณผ ๊ต์  

๐ด [์์์ด](https://kr.linkedin.com/in/javaoracle/ko)  
- (์ฃผ)๋ฐ์ด์ค๋น CEO 

