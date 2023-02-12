# XeroCodee 👋

![xerocodee](./public/images/Logo-OAuth.png)

## Readable & Production Ready Codee

<img src="https://raw.githubusercontent.com/xerocodee/.github/master/profile/images/xerocodee-open-source.svg" title="XeroCodee">

---
[![Slack](https://img.shields.io/badge/Slack-%40xerocodee-blue)](https://xerocodee.slack.com/)
[![Discord](https://img.shields.io/badge/Discord-%40xerocodee-blue)](https://discord.gg/FTf9VD7pMB)
[![LinkedIN](https://img.shields.io/badge/LinkedIN-%40xerocodee-blue)](https://www.linkedin.com/company/xerocodee)
[![Website](https://img.shields.io/badge/Website-%40xerocodee-blue)](https://xerocodee.com/)
[![Blog](https://img.shields.io/badge/Blog-%40xerocodee-blue)](https://blog.xerocodee.com/)

---

There is XEROCODE if there is React/Typescript and a WebApp or MobileApp. If you only give it a try, you won't want to stop using it. The more websites you make, the more time you'll save.

---

## Advanced microservice-based OAuth system ( Goel )

To implement an advanced microservice-based OAuth system, you need to consider the following steps:

- Implement the authorization server

- Implement the resource server

- Implement the client application

- Implement the user authentication and authorization flow

- Integrate the components with a database

- Implement security measures

[more deatils](https://github.com/xerocodee/oauth/wiki)

---
### What stack is WeMakeDevs built on?

[![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://docs.docker.com/)
[![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/docs/home/)
[![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
[![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

### Quick Start
---

Install **XeroCodee OAuth** by running either of the following:

---

1 : Google Cloud Console setup

- Add Authorized Redirect URIs to be: <http://localhost:3000/auth/google> and  <http://localhost:3000/auth/google/callback>

- Google will generate unique Client ID and Client Secret keys for project. Create a new file called .env and add your keys and callback URL in there like so,

.env.example 

```shell 

CLIENT_ID=107xxx-ni31ps789mf1jd33nnfk57vdllhqcmie.apps.googleusercontent.com 
CLIENT_SECRET=KE5xxxvvm 
CALLBACK_URL=<http://localhost:3000/auth/google/callback>

```
2 : Start a Local Mongo DB

```shell
mongod
```
A local Mongo instance should start up on mongo://localhost:27017

---

Clone the repository with the following command:

```bash
git clone https://github.com/xerocodee/oauth
```

Run in terminal this command:

```bash
npm install
```

Then run this command to start your local server

```bash
npm start
```
---

# Contribute

We welcome contributions in our community.<br>
Before contributing,see <a href="https://github.com/xerocodee/oauth/blob/main/CONTRIBUTING.md">Contribution guide</a> for more information.

# License

This Community is <a href="https://github.com/xerocodee/oauth/blob/master/LICENSE">Licensed</a> under Mozilla Public License Version 2.0

