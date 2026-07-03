# Week 00 - Internet and Networking

Part of the DevOps Micro Internship (DMI) Cohort 3 with Agentic AI

---

# 🧑‍💻 Task 1: Using ChatGPT as Your Learning Assistant

## Scenario

You're new to DevOps and will frequently encounter technical questions. ChatGPT can be your learning companion.

## Your Task

Write a clear ChatGPT prompt to help you understand:

> "What is a protocol in networking? Explain with a simple real-life example."

<img width="1248" height="616" alt="image" src="https://github.com/user-attachments/assets/89c95828-6653-481b-ac92-55c85b3de52e" />


* Your detailed prompt (with clear expectations)
* ChatGPT's simplified response with an example

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.

<img width="1314" height="843" alt="image" src="https://github.com/user-attachments/assets/3868a97d-a2fb-43c7-ba35-80786c52dc5a" />


---

## What I Learned (2–3 lines)

Through this task, I learned how to break down a technical concept like networking protocols into simple, relatable language. I also practiced using real-life analogies to make complex ideas easier for beginners to understand, especially for a non-technical audience. 

---

# 🌐 Task 2: Internet and Networking

## Scenario

Your friend is launching an online bookstore named **EpicReads**.

He asked you to explain how users globally can access his website hosted in Finland.

## Your Task

Write a short explanation (**100–150 words**) that includes:

* Packet Switching
* IP Address
* TCP/IP
* HTTP/HTTPS

💡 **Tip:** You may use ChatGPT (as demonstrated in Task 1) to refine your explanation.

## Answer

When a user visits a site like EpicReads, the journey begins with packet switching, where data is split into small packets (data packets) and routed independently across the internet before being reassembled at the destination.
The destination is identified using an IP address, which acts like a unique digital location for the server hosting the website.
Communication between the user and server follows the TCP/IP protocol suite. TCP ensures reliable, ordered delivery of packets, while IP handles routing them across networks.
Finally, web content is delivered using HTTP/HTTPS. Whereas, HTTPS adds a layer of security through encryption, ensuring safe browsing and transactions.


---

# 🏗️ Task 3: Application Architecture & Stack

## Scenario

EpicReads bookstore has two application versions:

### Two-Tier Application

* Frontend
* Database

### Three-Tier Application

* Frontend
* Backend
* Database

## Your Task

* Draw simple diagrams (hand-drawn or tool-based such as draw.io)
* Label each layer clearly
* List at least two common technologies or tools used for each layer
* Submit a screenshot or photo clearly showing your own drawing

## Diagram Screenshot / Photo

Save your diagram image in the `screenshots` folder and update the file name below.

![Application Architecture Diagram]
<img width="1527" height="641" alt="image" src="https://github.com/user-attachments/assets/2d764daa-7f79-4db6-a9b8-5b8bc2b6c4ba" />


---

## Technologies Used

### Frontend

HTML, CSS, JavaScript
React / Angular / Vue


### Backend

Node.js (Express)
Python (Django / Flask)
Java (Spring Boot)

### Database

MySQL
PostgreSQL / MongoDB


---

# 🌍 Task 4: Domain Name & DNS (Basic Concepts)

## Scenario

Your friend's bookstore **EpicReads** is currently accessible through:

```text
52.172.142.222:3000
```

He purchased the domain:

```text
epicreads.com
```

## Your Task

In **50–100 words**, explain in your own words:

1. What is DNS (Domain Name System)?
2. Which DNS record type should be used to connect the domain to the given IP, and why?

## Answer

DNS (Domain Name System) is the internet’s naming system that translates human-readable domain names like epicreads.com into machine-readable IP addresses so browsers can find the correct server.
To connect epicreads.com to 52.172.142.222, we should use an A record, because it maps a domain directly to an IPv4 address. The port (3000) is not handled by DNS; it is managed by the web server or application configuration after the domain resolves to the correct IP.


---

# 💻 Task 5: Visual Studio Code Setup (Hands-on)

## Your Task

Install Visual Studio Code (if not already installed).

Take a screenshot of your VS Code environment showing:

* Terminal open inside VS Code
* Running a basic command:

### Windows

```powershell
dir
```

### Linux / macOS

```bash
pwd
ls
```

* Your selected VS Code theme clearly visible

⚠️ **Important:** The screenshot must show your username or another identifiable detail to confirm it is your environment.

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.
<img width="1415" height="780" alt="image" src="https://github.com/user-attachments/assets/b09f5047-3f19-4e19-b08f-e5a6de7c2376" />


Replace `task-5-vscode.png` with your actual screenshot file name.

---

# 🔗 Task 6: Publish Your Assignment as a LinkedIn Post

## Objective

Publishing on LinkedIn helps you:

* Build your professional online presence
* Reinforce your learning
* Document your DevOps journey publicly

## Your Task

Summarize your answers from Tasks 1–5 into a LinkedIn post.

Clearly structure your post into the following sections:

* ChatGPT
* Internet & Networking
* App Architecture
* DNS
* VS Code Setup

Add the following credit note at the end of your post:

> **P.S. This post is a part of DevOps Micro Internship with Agentic AI Cohort-3 by Pravin Mishra. You can start your DevOps journey by joining this Discord community: https://discord.pravinmishra.com/**

---

## LinkedIn Post URL

Paste your LinkedIn post URL here:

https://www.linkedin.com/feed/update/urn:li:activity:7456257572602339328/

---

## LinkedIn Post Backup Copy

https://www.linkedin.com/feed/update/urn:li:activity:7456257572602339328/

My DevOps Learning Journey: Building Strong Foundations
My recent learning has been focused on understanding the core building blocks of modern systems—Internet & Networking, Application Architecture, and DNS (Domain Name System).
One key realization: everything we interact with online is essentially a well-orchestrated flow of requests, routing, and resolution. For instance, DNS plays a critical role by translating human-friendly domain names into IP addresses, enabling seamless access to applications across the globe.
To accelerate my learning, I’ve been using ChatGPT as a real-time learning companion. It has helped me simplify complex concepts, explore practical scenarios, and validate my understanding step by step.
Another essential part of my workflow is Visual Studio Code. Beyond being a code editor, it serves as a productivity hub for writing configurations, working with infrastructure-as-code, and integrating with CI/CD pipelines.
📈 Continuously learning, building, and strengthening my understanding of each layer of the stack.

P.S. This post is part of the FREE DevOps Micro Internship Cohort run by Pravin Mishra. You can start your DevOps journey for free from his https://lnkd.in/dctnze3v

---

# Reflection – Week 0

### What did you find easy?

Add your answer here...

---

### What was difficult?

Add your answer here...

---

### What will you improve next week?

Add your answer here...

---

## 📌 About DMI & CloudAdvisory

DevOps Micro Internship (DMI) is a project-based DevOps program run by Pravin Mishra (The CloudAdvisory) focused on real-world execution, systems thinking, and career readiness.

It helps learners build strong DevOps foundations with hands-on experience.


## 📌 Resources

- 🌐 **DMI Official Website:** https://pravinmishra.com/dmi  
- 🎓 **DevOps for Beginners (Udemy):** https://www.udemy.com/course/devops-for-beginners-docker-k8s-cloud-cicd-4-projects/  
- 🎓 **Ultimate Agentic AI DevOps with Clude Code** https://www.udemy.com/course/ultimate-agentic-ai-devops-with-claude-code/?referralCode=448389767BC96284087B
- 🎓 **DevOps with Claude Code: Terraform, EKS, ArgoCD & Helm** https://www.udemy.com/course/devops-with-claude-code-terraform-eks-argocd-helm/?referralCode=1C5B734505D65A010FA3
- ▶️ **YouTube Playlist (DMI Cohort 3):** https://www.youtube.com/playlist?list=PLFeSNDtI4Cho  
- 🔗 **Pravin Mishra (LinkedIn):** https://www.linkedin.com/in/pravin-mishra-aws-trainer/  
- 🏢 **CloudAdvisory (LinkedIn):** https://www.linkedin.com/company/thecloudadvisory/

---

*This submission is part of DevOps Micro Internship (DMI) Cohort 3 — Agentic AI Track*
