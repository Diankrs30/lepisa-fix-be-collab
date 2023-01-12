# <div align="center">Lepisa Tickitz - Backend</div>

<br/>

<div align="center">

[![node](https://img.shields.io/npm/v/node?label=node)](https://nodejs.org/en/)
[![express](https://img.shields.io/npm/v/express?label=express)](https://www.npmjs.com/package/express)
[![posgreSql](https://img.shields.io/npm/v/postgresql?label=postgresql)](https://www.npmjs.com/package/pg)
[![jsonwebtoken](https://img.shields.io/npm/v/jsonwebtoken?label=jsonwebtoken)](https://www.npmjs.com/package/jsonwebtoken)
[![bcrypt](https://img.shields.io/npm/v/bcrypt?label=bcrypt)](https://www.npmjs.com/package/bcrypt)
[![multer](https://img.shields.io/npm/v/multer?label=multer)](https://www.npmjs.com/package/multer)
[![nodemailer](https://img.shields.io/npm/v/nodemailer?label=nodemailer)](https://www.npmjs.com/package/nodemailer)
[![midtrans](https://img.shields.io/npm/v/midtrans?label=midtrans)](https://www.npmjs.com/package/midtrans)


<br/>

</div>

<br/>

Lepisa Tickitz is an online ticket purchase service for cinema.

## Contents

- [API Endpoint](#api-endpoint)
- [Run Application](#run-application)
- [Postman Documentation](#postman-documentation)
- [Related Project](#related-project)
- [Contributors](#contributors

## API Endpoint

### Public

#### Login

Endpoint: `/api/auth/login`

- Body
  | KEY | TYPEDATA |
  | --- | --- |
  | email | `string` |
  | password | `string` |

#### Register

Endpoint: `/api/auth/register`

- Body
  | KEY | TYPEDATA |
  | --- | --- |
  | email | `string` |
  | password_user | `string` |

#### Movie Now Showing

Endpoint: `/api/movie/`

#### Cooming Soon Movie

Endpoint: `/api/movie/film/:month`
  
#### Movie's detail

#### Edit profile

### Customer:

- Create Booking
- Order history

### Admin:

- Add Movie
- Add Schedule

## How to Run the Application

### 1. Clone this repository

Clone this repository by run the following code:

```
$ git clone <this-repo-url>
```

### 2. Install dependency packages

Install dependency packages by run the following code inside project folder:

```
$ npm install
```

### 3. Run `npm run dev`

Runs the app in the development mode.\
Open [local host](http://localhost:8080) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

## Postman Documentation

[Postman documentation link](https://documenter.getpostman.com/view/23804140/2s8YzL3kWx)

## Related Project

[Lepisa Tickitz Github link](https://github.com/farisan/lepisa-fe)
[Lepisa Tickitz App link](https://lepisa-fe.vercel.app/)

## Contributor
<center>
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/imbasri">
          <img width="100" ; src="/home/pratama/monlight-wallet/src/assets/gue.jpg" alt=""><br/>
          <sub><b>Imam Basri</b></sub>
        </a>
        </td>
        <td align="center">
        <a href="https://github.com/farisan">
          <img width="100" ; src="/home/pratama/monlight-wallet/src/assets/gue.jpg" alt=""><br/>
          <sub><b>Muhammad Farisan</b></sub>
        </a>
        </td>
        <td align="center">
        <a href="https://github.com/Diankrs30">
          <img width="100" ; src="/home/pratama/monlight-wallet/src/assets/gue.jpg" alt=""><br/>
          <sub><b>Dian Kartika Ratna Sari</b></sub>
        </a>
        </td>
        <td align="center">
        <a href="https://github.com/rzkiyprtm">
          <img width="100" ; src="/home/pratama/monlight-wallet/src/assets/gue.jpg" alt=""><br/>
          <sub><b>Rizky Putra Pratama</b></sub>
        </a>
        </td>
        <td align="center">
        <a href="https://github.com/rivalalfalah">
          <img width="100" ; src="/home/pratama/monlight-wallet/src/assets/gue.jpg" alt=""><br/>
          <sub><b>Rival Alfalah</b></sub>
        </a>
        </td>
  </table>
</center>


