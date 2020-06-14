---
title: "AISC: Generative Adversarial Networks: From Theory to Deployment"
excerpt: "As part of the capstone project for this GAN workshop, we developed and deployed a service to generate synthetic medical images."
#layout: "projects"
---

# AISC
I stumbled upon [ai.science](https://ai.science) through their youtube channel where they have many Ai related paper reviews, done by the authors themselves. AISC seems to be a company focused on building an Ai community and training platform. Bases in Toronto/Canada, great part of its user base seem to be from their and know each other personally (something that I found out only much later).

I was intrigued when I found out that they offer Ai workshops as well, and because they are quite cheap I decided to give it a try, and signed up for their 4 week long **Generative Adversarial Networks: From Theory to Deployment** workshop.

## Workshop: Generative Adversarial Networks: From Theory to Deployment 
I definitely learned many useful new skills, and finally got some hands on experience with model packaging and deployment, but concerning the GAN aspect, I must say the course worse kinda disappointing.

The course is spread over 4 weeks in which every week the participants get access to video lectures covering some GAN theory and software/model deployment and two home work exercises. The last two weeks, participants should work in small groups (2-3 people) at capstone projects that showcast the topics covered and skills learned.

In addition we had regular zoom meetings once a week where tutorals would reveal homework solutions, and resolve open questions students may have.

I enjoyed the lectures and materials provided, but must critique the capstone project approach. Spending half of the course on the capstone project is just too much. Obviously everyone has to decide themselves on how much time they can or want to invest, but I ruffly had to dedicate 70-80% of my time to the capstone project instead of learning about GAN theory and MLOps. Luckily the time spend includes a lot of hand on experience with model deployment, but sadly as well spend on resolving destructive group dynamics, group coordination or polishing the capstone project and presentation.

Aa a resumen I can say, I learned little about GANs, and some good hands on experience in model deployment, and reinforced the knowledge that group management is a tricky psychological exercise.

# Capstone Project: Synthetyk
As the capstone project, we developed a service to generate synthetic medical images of Invasive Ductal Carcinoma (IDC) positive histological samples.

![Image Comparison](/assets/img/AISC_Synthetyk.png "Image Comparison"){: .align-center}

The fruits of the project are available at [github](https://github.com/mapa17/AISC_BHI) and include
* A notebook to train a DCGAN model
* Code to package the model using MLFlow
* Serve the model over two REST API endpoints using flask or gunicorn
* Contanerize the model as a docker image

A show video presenting the project is available [here](TODO: Add link)