# BeReal Clone Tasks Manager Backend


<div align="center">

<div align="center">

## BackEnd

<a href="https://github.com/jinjunoh">Jin Jun Oh<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"></a>

</div>
  
<div align="center"><h1>STACKS</h1></div>

<div align="center">BACKEND</div>
<div align="center">
  <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"><br/>
  <img src="https://img.shields.io/badge/SQL-FFA500?style=for-the-badge&logo=sql&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
</div>

<h2>ERD diagram</h2>
<img src="https://github.com/jinjunoh/BeReal-Clone-Tasks-Manager-Backend/assets/db_diagram.png">

### `Auth`
- Implemented robust email and password validation checks to ensure the integrity and security of user credentials.<br/>
- Sign Up: Utilized the industry-standard bcrypt hashing algorithm to encrypt and securely store user passwords, enhancing data protection<br/>
- Login: Implemented token-based authentication using the widely adopted jsonwebtoken library, ensuring secure and reliable user authentication.<br/>

### `Main`
Implemented advanced ordering and pagination capabilities using optimized SQL queries.

- Ordering: Enabled users to sort task listings based on different attributes such as imminency and status. This empowers users to easily find the products that best meet their preferences and requirements.
- Pagination: Implemented efficient pagination techniques to handle large datasets, ensuring smooth and fast browsing experience for users. 

### `Details`
- Utilized AWS S3 to store images and enable media sharing capabilities
- Deployed the Backend server on AWS EC2 instance inside an auto-scaling group linked with an Elastic Load Balancer to enable a scaling cloud infrastructure design

### `Mypage`
- User Profile: Implemented a user profile page where users can view and update their personal information such as name, email, birthday, and phone number.
- Todo History: Provided a comprehensive order history feature that allows users to view their past task, including details such as completion date, status, and media.
