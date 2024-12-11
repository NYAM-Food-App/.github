<div align="center">
  <img src="img/NYAM-logo.png" alt="NYAM App Icon" width="300" />
  <h1>NYAM Food Apps</h1>
</div>

# 📌 Summary
| Name          | Value                 |
| ------------- | --------------------- |
| Type          | Product-based Project |
| Team ID       | C242-PS136            |
| Project Topic | Health Innovation     |

# 📖 Table of contents
- [📌 Summary](#-summary)
- [📖 Table of contents](#-table-of-contents)
- [📝 Introduction](#-introduction)
  - [🤖 Machine Learning](#-machine-learning)
  - [📱 Mobile Development](#-mobile-development)
  - [☁️ Cloud Computing](#️-cloud-computing)
- [🗂️ Repositories](#️-repositories)
- [👨‍💻 Our Team Members](#-our-team-members)
- [🙏 Conclude](#-conclude)

# 📝 Introduction
Maintaining a healthy body starts with eating nutritious food. However, achieving this goal is often more challenging than it seems. It's not just about eating healthy; we must also consider various factors, such as the nutritional value of the food, how to prepare it in a way that retains its nutrients, and how to make it taste delicious. These considerations can be overwhelming for many people, especially when they are unsure where to start.

To address this challenge, we created NYAM, which stands for Not Your Average Menu. We designed NYAM, an innovative application, to assist users in discovering healthy diet menus using ingredients they already have at home. The app uses image recognition technology to analyze an image of the ingredients uploaded by the user. It then predicts the content of the image and suggests recipes tailored to the user's BMI, making healthy eating more accessible and personalised than ever before.


We have organised this project into three major categories, each of which represents a core aspect of our work. We will provide a comprehensive overview of the responsibilities and tasks associated with each category, offering insights into the specific job roles and contributions involved. The categories are outlined as follows:

## 🤖 Machine Learning

We developed two machine learning models using TensorFlow for our application. The first, an image classification model, uses the MobileNetV2 architecture to recognize ingredients in images categorized into 17 classes.  The second model utilizes Body Mass Index (BMI) data to predict BMI categories into six distinct groups. We preprocessed the image data by resizing, sharpening, and categorizing it, and cleaned the BMI dataset using missing value imputation and duplicate removal. We saved both models in the.keras format to facilitate easy deployment and prediction on new data.

## 📱 Mobile Development

To create the planned program, we started by designing and developing the application's workflow, covering all features from start to finish as agreed upon during discussions. Next, we designed the UI/UX based on the existing workflow, striving to create an interface that is simple for users to understand while delivering the best possible experience. Afterward, we implemented the UI design into Android Studio (slicing). The process went smoothly but required some adjustments along the way.

## ☁️ Cloud Computing

Our project would not be working properly unless the Cloud Computing team provides backend applications and the ML model. The first step is to design a cloud architecture, which will help us understand the application's workflow. Next, we start developing a backend application using ExpressJS and a Flask API to facilitate communication between the machine learning model and the backend application. After developing the backend application, we first build it using Cloud Build to create the Docker image, and then we deploy it using Cloud Run.

# 🗂️ Repositories

Our team uses GitHub to manage and collaborate on the source code effectively. Before reviewing our source code, put some attention on it because **there are many branches in our repositories**. Below are the repositories, categorised by our main focus areas:

| Learning Path      | Repo Link                                                                 |
| ------------------ | ------------------------------------------------------------------------- |
| Machine Learning   | [Machine-Learning](https://github.com/NYAM-Food-App/Machine-Learning)     |
| Mobile Development | [Mobile-Development](https://github.com/NYAM-Food-App/Mobile-Development) |
| Cloud Computing    | [Cloud-Computing](https://github.com/NYAM-Food-App/Cloud-Computing)       |

# 👨‍💻 Our Team Members

| Student ID   | Name                       | Learning Path      | University                               | Contact                                                                                                                                                                                                                                                                                                                |
| ------------ | -------------------------- | ------------------ | ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| M320B4KX1390 | Fanny Rorencia Ribowo      | Machine Learning   | Universitas Surabaya                     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fanny-rorencia-ribowo-27390b228/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/fannyyrr29/) |
| M320B4KX2039 | Janet Deby Marlien Manoach | Machine Learning   | Universitas Surabaya                     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deby-manoach/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/byMann/)                        |
| M108B4KY4331 | Theophilus                 | Machine Learning   | Institut Informatika Indonesia Surabaya  | [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/theophilus-a3567a331/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/KawaiSeigiDesu/)        |
| A108B4KY4539 | Yohanes Christianto        | Mobile Development | Institut Informatika Indonesia Surabaya  | [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yohanes-christianto-965868308/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/yoc19/)        |
| A409B4KY2131 | Kaleb Gibran Joso Dihardjo | Mobile Development | Sekolah Tinggi Ilmu Komputer Yos Sudarso | [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaleb-gibran-506863308/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/KalebGibran/)         |
| C320B4KY0936 | Christopher                | Cloud Computing    | Universitas Surabaya                     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chrispengalilla/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/zeroX397)                    |
| C764B4KY0606 | Aqil Muhammad Fachrezi     | Cloud Computing    | Universitas Teknologi Bandung            | [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aqil-muhammad-fachrezi-5852892a7/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/mofach/)    |

# 🙏 Conclude

We would like to extend our deepest gratitude to everyone who contributed to the success of the **NYAM Food Apps** project. This accomplishment would not have been possible without the support, guidance, and collaboration of various individuals and organisations.

- **Bangkit Academy by Google, GoTo, and Traveloka**: We are grateful for the platform, resources, and mentorship you provided, which allowed us to embark on this exciting journey and expand our knowledge.
- **Mentors and Instructors**: Your guidance and expertise were invaluable in helping us navigate challenges and refine our ideas into actionable solutions.
- **Team Members**: Each of you brought unique strengths and unwavering dedication to the project. This application is a testament to our shared efforts and collaboration.
- **Friends and family**: Your encouragement and support fuelled our motivation to achieve our goals.
 
Lastly, we thank everyone who took the time to review and engage with our project. We hope this application serves as a helpful tool for promoting healthier lifestyles.

With gratitude,
**NYAM Food**