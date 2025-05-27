# MidnightBlue

Our web application is built on the fundamental principle of a decentralized web, giving users unprecedented control and flexibility over their content interactions. We drew inspiration from pioneering projects like Diaspora and streamlined approaches similar to ActivityPub, but it took considerable effort in API development to bring this vision to life. The robust APIs we meticulously crafted are what enable this platform to facilitate seamless, direct interactions between different nodes. Users can connect with other compatible web applications, viewing, liking, and commenting on posts, all without the need to route through centralized behemoths like Facebook or Twitter. This demanding API development was crucial for empowering users with genuine autonomy and choice.

# Screencast:
https://youtu.be/YUdXL5ok_gQ?si=qHEog-XlXyQk65PN

# Tech-stack:
Frontend: React.js
Backend: Django
Deployment: Heroku

# Key Features

---

## Account Management

* **Secure Access:** Easily sign up and sign in, whether you're a regular user or an app manager.

---

## App Manager Tools

* **Interoperability:** Connect your app seamlessly with other compatible platforms, expanding your network's reach.
* **User Oversight:** Gain a complete view of all local users within your application.

---

## User Experience & Content

* **Diverse Content Creation:** Express yourself with plain text, rich CommonMark formatting, or image posts.
* **Granular Privacy:** Control who sees your content with **Public**, **Unlisted** (link-only), and **Friends-Only** visibility options.
* **Content Discovery:**
    * **Public Content:** Explore public posts from users on your app and across connected applications.
    * **Unlisted Content:** View unlisted posts from local users and from users on connected apps you follow.
    * **Friends-Only Content:** Access private posts from local users and from users on connected apps you mutually follow.
* **GitHub Integration:** Your GitHub activity can be automatically shared as public posts.
* **Post Control:** Edit your own posts at any time.
* **Effortless Sharing:** Share any public post from another user using a unique URL.
* **Engage with Content:**
    * **Likes:** React to any local or remote post with a like.
    * **Like Visibility:** See all the likes on any post.
    * **Comments:** Share your thoughts by commenting on local or remote posts.
    * **Comment Visibility:** View all comments on any post.
* **Connect with Others:** Follow authors within your app or from connected applications.
* **Manage Connections:** Easily view, accept, or reject incoming follow requests.

# Screenshots:
#### Login/Sign up
![](https://private-user-images.githubusercontent.com/64448813/397957870-0132252d-225c-4c16-93c7-55f2107528ef.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDgzODM5NDQsIm5iZiI6MTc0ODM4MzY0NCwicGF0aCI6Ii82NDQ0ODgxMy8zOTc5NTc4NzAtMDEzMjI1MmQtMjI1Yy00YzE2LTkzYzctNTVmMjEwNzUyOGVmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA1MjclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNTI3VDIyMDcyNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWJlNjNkODhlMzJhMjJlYTMzZmQ1YWU0Mzc2N2Y0YjI4NjFmYzFjN2I1YzA3NzRjMjIwZDJmMDU4OTAyYTNkOTgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.KRkVCPqX2lOc-TZjKjmoYvpeOwwaQaVBykZL8IRmqeA)

#### Make public, friends-only, image posts
![](https://private-user-images.githubusercontent.com/64448813/397957907-2e89d0b5-0455-4b1d-868c-11e200b5ff08.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDgzODM5NDQsIm5iZiI6MTc0ODM4MzY0NCwicGF0aCI6Ii82NDQ0ODgxMy8zOTc5NTc5MDctMmU4OWQwYjUtMDQ1NS00YjFkLTg2OGMtMTFlMjAwYjVmZjA4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA1MjclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNTI3VDIyMDcyNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWMxODdmYmU2YWM4ZjRkNmMxZDUxMWI0ZjYxODA0ZGI0YjZlMjM5MDNmYWEzYmRkMDIwMjRmZGU4NGUxOWQwZGUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.Qgj_F-Jb2oOATWw4ppKqRi66Aeae23U9-6j89PS2WZ4)
![](https://private-user-images.githubusercontent.com/64448813/397957908-6a3b5824-25f9-4d69-a735-492a008b6827.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDgzODM5NDQsIm5iZiI6MTc0ODM4MzY0NCwicGF0aCI6Ii82NDQ0ODgxMy8zOTc5NTc5MDgtNmEzYjU4MjQtMjVmOS00ZDY5LWE3MzUtNDkyYTAwOGI2ODI3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA1MjclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNTI3VDIyMDcyNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBjNDFhZGNmODdjMmU1MjY5Y2JmODc1YjI2YTUzZmJjNTQ0NDkxMjY3Yzg1OTA3MTllYzVmODNiYzdlMmNmODUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.b0owrBBZwmNibY3C5dSlrBGmabqZkqkfqgItoCntW4Y)
![](https://private-user-images.githubusercontent.com/64448813/397958050-35d9a32c-7ccf-45ce-b68a-25c30ef00ee4.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDgzODM5NDQsIm5iZiI6MTc0ODM4MzY0NCwicGF0aCI6Ii82NDQ0ODgxMy8zOTc5NTgwNTAtMzVkOWEzMmMtN2NjZi00NWNlLWI2OGEtMjVjMzBlZjAwZWU0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA1MjclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNTI3VDIyMDcyNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTViY2Y5OTczYzI0OWYzYmI4ODAyMmEwMWMyM2NjZWRlYjRiMGQzOWMzMjg4NDllZWE0OGI3N2ZjYTFlZjAxZmYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.R4qNglSnLH9j-zyouDfIMNdYUiYkpnfwoWlXnWydi_E)
![](https://private-user-images.githubusercontent.com/64448813/397958052-07ab9440-de76-4946-af06-15731a356a9c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDgzODM5NDQsIm5iZiI6MTc0ODM4MzY0NCwicGF0aCI6Ii82NDQ0ODgxMy8zOTc5NTgwNTItMDdhYjk0NDAtZGU3Ni00OTQ2LWFmMDYtMTU3MzFhMzU2YTljLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA1MjclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNTI3VDIyMDcyNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWQ0YjA4NDgxMzVlOGY1Njg2ZjI4ZTcwMTY2YzVkOGMzMDNjNDhkZmUwOGYwZDUxZjhlZjgyNTkzZWUyNzBjYzEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.3uFKjCVSpZPi_uRZ63yZT---m3Cmr89DrPPziA1kIIs)

#### Share posts
![](https://private-user-images.githubusercontent.com/64448813/397958078-011c0537-aea6-402b-87ee-8dab02a3eb91.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDgzODM5NDQsIm5iZiI6MTc0ODM4MzY0NCwicGF0aCI6Ii82NDQ0ODgxMy8zOTc5NTgwNzgtMDExYzA1MzctYWVhNi00MDJiLTg3ZWUtOGRhYjAyYTNlYjkxLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA1MjclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNTI3VDIyMDcyNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWZlYzA4Zjc2NThiZTQzOWU0ZDRiMjkwNTk0NTVhNDY1OTNkZDAxMDg3YjI2M2M4NWZiNmNiNTE1ZjJlYWJlMDcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.10-HjlsO26pWc110SZe27JMdZIp7Id10A4keU0EZbvo)

#### Send/Accept follow requests
![](https://private-user-images.githubusercontent.com/64448813/397958096-556f641b-9bda-4f4b-9bfe-0ea0cd62123a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDgzODM5NDQsIm5iZiI6MTc0ODM4MzY0NCwicGF0aCI6Ii82NDQ0ODgxMy8zOTc5NTgwOTYtNTU2ZjY0MWItOWJkYS00ZjRiLTliZmUtMGVhMGNkNjIxMjNhLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA1MjclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNTI3VDIyMDcyNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTY4YmVlOTJhYWVjOTdhMGY5MjJkYjRlNGIyM2EyMjQ1NGZkNTZlZDVlZmQzN2JjZDYzYTc5YTczZjAwMjI4NjYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.8Px9cNZiHQzGWHYRGgZ8rSO2z3Lu6513xpgdYhGGRGY)
