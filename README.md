# Cyber-Blog: A Secure Web Application Project

<p align="center">
  <img src="https://example.com/your-logo.png" alt="Logo" width="200">
</p>

<p align="center">
  <em>A showcase of my cybersecurity bootcamp project, demonstrating skills in systems administration, networking, network security, cryptography, virtualization, cloud deployment, and web development.</em>
</p>

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Problem and Solution](#problem-and-solution)
- [Project Components](#project-components)
  - [Azure Cloud Services](#azure-cloud-services)
  - [Docker Container](#docker-container)
  - [SSL Certificates](#ssl-certificates)
  - [WAF Rules and Security Center](#waf-rules-and-security-center)
- [Live Demo](#live-demo)
- [Installation and Usage](#installation-and-usage)
- [Security Features](#security-features)
- [Learnings](#learnings)
- [License](#license)

## Introduction
In this cybersecurity bootcamp project, I built and hosted a secure "cyber-blog" web application using Microsoft Azure. This project allowed me to gain hands-on experience in various aspects of cybersecurity, including Keyvaults, App Services, Front Door, WAF
PHP, HTML, Docker, OpenSSL. The project has been developed with security in mind, incorporating a range of security features to protect the web application from potential threats.

## Technologies Used
- Azure: {Keyvaults, App Services, Front Door, WAF}
- PHP, HTML
- Docker
- OpenSSL
- GoDaddy

## Problem and Solution
The primary goal of this project was to set up and secure a web application using Microsoft Azure, ensuring that the web app is protected from potential threats and vulnerabilities. This project demonstrates the ability to apply cybersecurity best practices and use various tools and technologies to create a secure environment.

One challenge faced during the development of the project was the initial usage of a self-signed SSL certificate. While this provided basic encryption for data transmitted between the client and server, it lacked the trust and validation offered by a Certificate Authority (CA). To address this issue, I replaced the self-signed certificate with a managed CA-approved certificate, which increased the overall security and trustworthiness of the web application.

Another challenge encountered was the need to restrict traffic from certain countries as part of the security measures. To overcome this, I deployed Azure's Front Door and configured a Web Application Firewall (WAF) rule that effectively limited access to the web app based on the geographic location of incoming requests.

Throughout the project, I gained hands-on experience with a variety of Azure services and other technologies, such as Docker and OpenSSL, and learned how to apply security best practices to protect a web application from potential threats. This project demonstrates my ability to adapt and learn new technologies quickly and effectively, as well as my commitment to ensuring the security and integrity of web applications.

## Project Components
### Azure Cloud Services
(Explain how you used Azure Cloud Services to host your web application, and the benefits of using this technology.)

### Docker Container
(Describe how you deployed a Docker container with a blog webpage framework, and how you customized the webpage by SSHing into the container.)

### SSL Certificates
(Explain the process of creating a self-signed certificate with OpenSSL, storing it in Azure Key Vault, and binding it to your website. Also, discuss the security issues associated with self-signed certificates and how you switched to a managed CA-approved certificate.)

### WAF Rules and Security Center
(Discuss how you deployed Azure Front Door, configured WAF rules to restrict traffic from certain countries, and analyzed Azure Security Center recommendations to apply the necessary fixes.)

## Live Demo
(Provide a link to the live demo of your cyber-blog web application if you have one hosted on a public domain.)

## Installation and Usage
(Provide step-by-step instructions on how to set up and run your project, making it easy for potential employers to test your application.)

## Security Features
(Highlight the security measures you've implemented in your project, such as SSL certificates, Azure security features, and WAF rules.)

## Learnings
(Share your key takeaways from the project, including what you've learned about systems administration, networking, network security, cryptography, virtualization, cloud deployment, and web development.)

## License
(Include the license information for your project, specifying how potential employers can use and modify your code.)
