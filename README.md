# Damanna_Backend

## π Damanna App μκ°

&nbsp;&nbsp;&nbsp;&nbsp;κ΄μ¬μ¬κ° κ°μ μ¬λλ€λΌλ¦¬ λͺ¨μ¬ λνλ₯Ό ν  μ μλ μ νλ¦¬μΌμ΄μμλλ€
<br>
<br>

<p align='center'>
    <img src="https://img.shields.io/badge/Swift-v5.0-FA7343?logo=Swift"/>
    <img src="https://img.shields.io/badge/SpringBoot-v2.45-6DB33F?logo=SpringBoot"/>
    <img src="https://img.shields.io/badge/MongoDB-47A248?logo=MongoDB"/>
    <img src="https://img.shields.io/badge/Heroku-430098?logo=Heroku"/>
    <img src="https://img.shields.io/badge/Gradle-6.8.3-02303A?logo=Gradle"/>
</p>
<br>

> ## π¨ μ¬μ©ν API
>
> <br>

<div align='center'>
    <img src="https://user-images.githubusercontent.com/44153216/124066304-67a6a200-da73-11eb-915c-b655746fba86.png" width="15%"></img>&nbsp;&nbsp;&nbsp;
    <img src="https://user-images.githubusercontent.com/44153216/124066463-accad400-da73-11eb-94ef-a31ff9573eda.png" width="15%"></img>&nbsp;&nbsp;&nbsp;
    <img src="https://user-images.githubusercontent.com/44153216/124066636-003d2200-da74-11eb-9951-6eea240fdc27.png" width="20%"></img>
</div>
<br>

## π§βπ» Member

| μ΅μΈμ  <img src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1582581609/noticon/cczbpahp5od6voerbvwr.svg" width="12px;"/> | μ΄μ μ°¬ <img src="https://user-images.githubusercontent.com/44153216/124068070-7beb9e80-da75-11eb-8bad-dcc6ebd3c3ce.png" width="12px;"/> |
| ---------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| [@injeChoi](https://github.com/injeChoi)                                                                                                 | [@yuchanleeme](https://github.com/yuchanleeme)                                                                                          |

<br>

# π νλ‘μ νΈ μν€νμ²

<div align='center'>
    <img src="https://user-images.githubusercontent.com/44153216/124071817-e8b56780-da7a-11eb-8a5a-908ec5a6bf22.png" width="50%"/>
</div>
<br>

## API URI

| λ²νΈ | μ ν    | URI                        | μ€λͺ                                       |
| :--- | :------ | :------------------------- | :----------------------------------------- |
| 1    | GET     | /room/read                 | MongoDBμ Databaseμ μλ λ°©μ μ λ³΄λ₯Ό μ‘°ν |
| 2    | POST    | /room/save                 | λ°©μ μ λ³΄λ₯Ό MongoDBμ μ μ₯                 |
| 3    | Message | /topic/{roomID}            | {roomID}λ₯Ό κΈ°μ€μΌλ‘ κ΅¬λ                   |
| 4    | Message | /chat/sendMessage/{roomID} | {roomID}κ΅¬λμμκ² λ©μΈμ§λ₯Ό μ μ‘           |

<br><br>

# ππ»ββοΈ μ€ν λ°©λ²

> ## Frontend Installation & Build

[@Damanna_Frontend](https://github.com/Damanna/Damanna_FrontEnd) <br><br>

> ## **Backend Configuration**

## &nbsp;&nbsp;&nbsp;&nbsp;./src/main/resources/application.properties

```properties
β¦
spring.data.mongodb.uri=${MONGODB_URI}              // MongoDB URI
spring.data.mongodb.database=${MONGODB_DATABASE}    // Target MongoDB Database Name
β¦
```

> ## **Backend Installation & Build**

### 1. git clone

```bash
$ git clone https://github.com/Damanna/Damanna_Backend.git
```

### 2. move directory & build

```
$ cd Damanna_Backend
$ ./gradlew build && java -jar build/libs/damanna-0.0.1-SNAPSHOT.jar
```
