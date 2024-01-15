# STUDENT DEBT MONITOR APP
A platform that allows schools in a certain locality list directory of people owing them to help them avoid going to other schools.


## Feature Requests

### User: Unauthenticated.

- Visit the platform to view basic information about it
- View and Interact with the documentation
- Register to view more details
- No access to data

### User: Authenticated
- Full access to the platform
- Verify details before full access to platform
- Post new data about a debtor
- Allow debtors to challenge - contend
- Comment on post by others
- Copy should be disabled


## Tech Stack

 **Design:**
<img src="https://img.shields.io/badge/FIGMA-orange?style=for-the-badge&logo=figma&logoColor=white" alt="FIGMA Badge"/>

**Client:**
<img src="https://img.shields.io/badge/HTML5-darkorange?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge"/>
<img src="https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3in&logoColor=white" alt="CSS3 Badge"/>
<img src="https://img.shields.io/badge/JAVASCRIPT-grey?style=for-the-badge&logo=javascript&logoColor=white" alt="Javascript Badge"/>

**Server:**
<img src="https://img.shields.io/badge/PYTHON-skyblue?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge"/>
<img src="https://img.shields.io/badge/DJANGO-darkgreen?style=for-the-badge&logo=django&logoColor=white" alt="Django Badge"/>

**Database:**
<img src="https://img.shields.io/badge/MYSQL-blue?style=for-the-badge&logo=mysql&logoColor=white" alt="Mysql Badge"/>

**Project Management and Version Control:**

<img src="https://img.shields.io/badge/GITHUB-black?style=for-the-badge&logo=github&logoColor=white" alt="github Badge"/>

## Documentation

- [Project Documentation](https://docs.google.com/document/d/1-XiVOQfVH-CCipMf4uTxQ41ilxrm-QvOlra41wzQ7NQ/edit?usp=sharing)
- [Figma Link](https://www.figma.com/file/z3zpJwBWGlbfeV10DBhmeA/My-Debtors-WiFi-(Copy)?type=design&node-id=0%3A1&mode=design&t=iDdy1UXLYwVjpfQ6-1)
- [Data Schema](https://app.sqldbm.com/MySQL/DatabaseExplorer/p284560/)


## Authors

- [Motunrayo Sanni](https://www.github.com/cutespot3200)
- [Add your name](https://www.github.com/your-username)


## Run Locally

Clone the project

```
git clone https://github.com/cutespot3200/PORTFOLIO-PROJECT.git
```

Go to the project directory

```
cd PORTFOLIO-PROJECT
```

Create a Virtual Environment

```
python -m venv env
```

Activate Virtual Environment

```
env\scripts\activate
```

Install Dependencies

```
pip install -r requirements.txt
```


Create .env file in SDM project level containing SECRET_KEY='' 


Migrate Database 

```
python manage.py migrate
```
Create Super User 
```
python manage.py createsuperuser
```
Finally, Start The Server.
```
python manage.py runserver
```


## Acknowledgements 🚀 

<p>
  <img src="https://res.cloudinary.com/zuri-team/image/upload/zuriboard/tenant-logo/wmqxdxt4skv05wsvc21o.png"
       alt="ALX Logo"
  >
</p>
