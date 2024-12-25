![mock-up-book](https://github.com/user-attachments/assets/ac6dc76e-9dea-4682-ae71-0ef5c8b05a80)

# Hello 👋, welcome!

This organization contains all code repositories for [Real-Life Infrastructure as Code with AWS CDK](https://real-life-iac.com/), published by [Andre Sionek](https://github.com/andresionek91).

## What is this book about?
This book will show you how to build a modern software platform in Python using [AWS CDK](https://aws.amazon.com/cdk/). Even if you use a different language, you will find this book useful because I focus on architecture patterns rather than syntax details. The book is divided into three parts: Foundations, Real-Life Examples, and Best Practices. 

I begin with an introduction to Infrastructure as Code (IaC) CDK to help you quickly learn and refresh some concepts. Then, we dive into a series of real-life implementations of various services and components that you can use to build your software platform. All examples are complete and fully functional, as I have personally deployed them. Finally, I discuss some best practices that I have learned from experience and implemented in the examples. You'll learn:

* AWS CDK and IaC concepts.
* Cloud computing concepts and services, including the [AWS Well Architected Framework](https://aws.amazon.com/architecture/well-architected/).
* How to build a cloud-native software platform using CDK.
* Create functional constructs of code that can build your cloud application.
* How to create reusable construct libraries.

In most cases, I will not discuss the pros and cons of different approaches or try to convince you to use one tool over another. I assume that you are already familiar with the *WHATs* and *WHYs*, and you are reading this book to learn the *HOWs. I will share my opinionated best practices, but keep in mind that opinions can change based on new evidence or different contexts. My opinions may also be completely wrong. Keep this in mind while reading.

Most books focus on syntax or general concepts, and the documentation for both AWS and CDK is excellent. Therefore, I do not believe that I should write a book to discuss those topics. Instead, I focus on the areas that can be challenging, such as connecting and orchestrating different cloud services. The book also includes diagrams and illustrations to help you understand the architecture and how each component fits into the system.

I will share what I believe is the best way to build and manage infrastructure on AWS. In most cases, I will not show alternative implementations, but I hope to provide you with the tools and knowledge to make your own decisions. My goal is to support you in building a robust software platform in AWS by applying the concepts and examples that I share. I also hope to help you avoid some of the mistakes I have made.

By the end of this book, you will have a clear understanding of IaC with CDK and the confidence to build a scalable, secure, and easy-to-maintain software platform in AWS.

## 🍿 Download a free PDF
Get a free PDF version at no cost on [https://real-life-iac.com/](https://real-life-iac.com/)!

## 💝 Did you enjoy the book? Sponsor it!
There are several ways to support this project if you enjoyed the content!

1. Buy a paperback or digital version on Amazon, Apple books or Play books.
2. Send a one-off or recurring donation via [Github Sponsors](https://github.com/sponsors/Real-Life-IaC/).
3. If you are in Brazil, you can send me a PIX on **pix@real-life-iac.com**, [clicking here](https://nubank.com.br/cobrar/1j8r44/676aa1c1-1998-4b21-bc75-71ce62844573), or with the QR Code below:


![pix-qr-code](https://github.com/user-attachments/assets/4a8c3c2a-643f-4f15-ba05-111278c6ec1c)


## 🧭 Instructions and Navigation
All code is organized into repositories. There is usually one repo per chapter. You'll find the repository reference at the beginning of each chapter, as shown below:

![Chapter](https://github.com/Real-Life-IaC/.github/assets/5912422/cf7a94fe-dc10-4389-947f-475aa4672a9f)

Each repository is independent and "almost" self-sufficient. As explained in the book, there are some dependencies between repositories and you'll need to deploy them in the correct order.

### 🎫 Issues / Questions

Please open an issue in the respective repository if you have questions or found a problem with the code!

### 👩‍💻 The Makefile
Each repository contains a `Makefile` that you can use to initialise the project, install the dependencies and run the tests.

## 🧙 About the author

### Andre Sionek 
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@sionek)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/andresionek)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/andresionek91/)
[![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/10353023)
[![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/andresionek)
[![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white)](https://www.reddit.com/user/AndreSionek)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/sou.o.belisco/)

I am an experienced Lead Software/Data Engineer focused on Infrastructure as Code, CI/CD, APIs, Software Architecture, and microservices. Instructor of data engineering Bootcamps and a winner of some Kaggle challenges. 

I've been working over the past few years to improve the developer experience with better continuous integration, testing and automating all steps of software development. My goal is to give my team 100% confidence that if the tests are passing, then it will work in the cloud/production. I enable them to refactor and constantly improve existing code so that we don't end with skeletons in the closet. 

For example, I built the whole infrastructure at one startup using AWS CDK, then automated all processes with GitHub Actions. I also implemented design patterns that made all of our APIs similar to each other, easing the maintenance and implementation. I also have extensive experience with Data Engineering, which makes me think about the software engineering discipline as processes to move (or display) data from one place to another.

My main interests are in creating systems and architectures to deliver data reliably, and to improve the team's productivity by automating any manual processes. I'm a strong Python developer, have great communication skills, and I'm always willing to share some knowledge.
