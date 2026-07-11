# AWS Cloud Resume Website

A responsive and interactive online resume website built with HTML, CSS, and JavaScript and deployed on AWS using Amazon S3 and Amazon CloudFront.

## Live Website

https://d3mt75xd75ulad.cloudfront.net

## GitHub Repository

https://github.com/sripathiabhiram29-droid/aws-cloud-resume

---

## Project Overview

This project is a single-page professional resume website designed to showcase my AWS cloud experience, technical skills, employment history, education, certification, and career highlights.

The website is built with separate HTML, CSS, and JavaScript files. JavaScript is used to create an interactive employment timeline that allows visitors to select different positions and dynamically view role details, achievements, and technology environments.

The application is hosted as a static website on Amazon S3 and distributed globally through Amazon CloudFront.

---

## Features

- Responsive single-page resume website
- Interactive employment timeline built with JavaScript
- Professional summary section
- Core AWS and cloud architecture expertise
- Dynamic professional experience section
- Technical skills organized by category
- AWS certification section
- Education section
- Career highlights
- Contact section
- Mobile-responsive design
- HTTPS delivery through Amazon CloudFront

---

## Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript

### AWS Services

- Amazon S3
- Amazon CloudFront
- AWS IAM
- AWS Budgets

### Development Tools

- Visual Studio Code
- Git
- GitHub

---

## AWS Architecture

The website follows this architecture:

```text
User Browser
      |
      | HTTPS
      v
Amazon CloudFront
      |
      | HTTP
      v
Amazon S3 Static Website Hosting
      |
      v
HTML + CSS + JavaScript
