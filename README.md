# sequelize

# 리눅수(우분투) 환경에서 porstgre 셋팅 순서
```
# sudo apt-get install postgresql postgresql-contrib // postgresql 설치
# sudo -u postgres psql // psql 접속
# CREATE USER <유저이름> PASSWORD '<패스워드>' SUPERUSER; // 유저생성
# CREATE DATABASE <데이터베이스 이름> WITH OWNER <유저이름> ENCODING 'UTF8';;
# sudo service postgresql restart // 서비스 재시작
```
# 생성된 DB 및 유저 확인
```
\l // 데이터베이스 목록 출력
\c <데이트베이스 접속>
\d <테이블이름> // 테이블 정보 확인

```
# express 및 sequelize 설치 순서
```
# npm init
# npm i express morgan sequelize sequelize-cli postgres pg
# npm i -D nodemon
# npx sequelize init
```
