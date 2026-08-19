This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

# Cloud Computing TA-1
## Dockerizing and Hosting a Next.js Web Application on AWS

### Student Details

- **Name:** Swayam Sagarkar
- **Section:** B1
- **Roll No:** 03
- **Subject:** Cloud Computing
- **Year:** 2026

---

## 1. Aim

To create and implement a Dockerfile for a self-created Next.js web application, build a Docker image, deploy the application inside a Docker container, and host the application on an AWS EC2 instance.

---

## 2. Objective

The main objectives of this practical are:

- To understand Docker containerization.
- To create a production-ready Dockerfile for a Next.js application.
- To build a Docker image from the application source code.
- To create and run a Docker container on an AWS EC2 instance.
- To configure AWS networking and security groups.
- To make the containerized web application accessible over the internet.
- To understand the basic workflow of deploying a web application using Docker and AWS.

---

## 3. Technologies Used

| Technology | Purpose |
|------------|---------|
| Next.js | Web application framework |
| React | Frontend library |
| TypeScript | Application development |
| Tailwind CSS | UI styling |
| Node.js 20 | JavaScript runtime |
| Docker | Application containerization |
| AWS EC2 | Cloud hosting |
| AWS VPC | Network configuration |
| AWS Security Group | Firewall configuration |
| Ubuntu | EC2 operating system |
| Git & GitHub | Source code management |

---

## 4. Application

The application used for this practical is a self-created Next.js web application.

The application contains information related to the Cloud Computing TA-1 practical, including student details, assignment scope, technology stack, and Docker configuration.

The project was developed using Next.js and then containerized using Docker.

---

## 5. Project Architecture

The deployment architecture used in this practical is:

```text
                    GitHub Repository
                           |
                           |
                           v
                  Next.js Application
                           |
                           v
                       Dockerfile
                           |
                           v
                    Docker Build
                           |
                           v
                 Docker Image
                aryan-cc-ta1:latest
                           |
                           v
                    AWS EC2 Instance
                      Ubuntu Linux
                           |
                           v
                   Docker Container
                     Port 3000
                           |
                           v
                    AWS Security Group
                     TCP Port 3000
                           |
                           v
                       Internet
                           |
                           v
                Next.js Web Application

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
