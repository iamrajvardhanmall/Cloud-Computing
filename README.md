# ☁️ Cloud Computing — Practical Lab Repository

A comprehensive collection of **Cloud Computing practicals, hands-on implementations, commands, and learning resources** covering essential cloud and DevOps technologies, including AWS, Docker, Git, and Kubernetes.

This repository serves as a centralized reference for learning cloud computing concepts, practicing industry-relevant tools, and preparing for laboratory examinations.

<p align="center">
  <img src="https://img.shields.io/badge/Cloud-Computing-blue?style=for-the-badge&logo=icloud&logoColor=white" alt="Cloud Computing" />
  <img src="https://img.shields.io/badge/AWS-Cloud%20Services-orange?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Docker-Containerization-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-Version%20Control-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Kubernetes-Container%20Orchestration-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
</p>

---

## 📌 Table of Contents

- [About the Repository](#-about-the-repository)
- [Technologies Covered](#-technologies-covered)
- [Repository Structure](#-repository-structure)
- [Getting Started](#-getting-started)
- [Prerequisites](#-prerequisites)
- [Practical Learning Roadmap](#-practical-learning-roadmap)
- [Learning Objectives](#-learning-objectives)
- [How to Use This Repository](#-how-to-use-this-repository)
- [Contributing](#-contributing)
- [Author](#-author)
- [License](#-license)

---

## 🎯 About the Repository

Cloud computing is a fundamental part of modern software development, infrastructure management, and DevOps engineering.

This repository organizes practical work and learning materials into dedicated folders, making it easier to explore individual technologies and practice their core concepts.

### What You'll Find Here

- ☁️ **AWS:** Cloud computing concepts and practical learning resources.
- 🐳 **Docker:** Containerization, Docker commands, images, containers, and application deployment exercises.
- 🌿 **Git:** Version control, repository management, branching, and collaboration workflows.
- ☸️ **Kubernetes:** Container orchestration concepts and practical exercises.

The goal is to connect theoretical knowledge with practical implementation through organized examples and reference materials.

## 🛠️ Technologies Covered

| Technology | Purpose | Key Learning Areas |
|---|---|---|
| AWS | Cloud infrastructure | Cloud services and fundamental cloud concepts |
| Docker | Containerization | Images, containers, Dockerfiles, ports, volumes, and networking |
| Git | Version control | Commits, branches, merges, remotes, and collaboration |
| Kubernetes | Container orchestration | Pods, Deployments, Services, and application management |

*The learning areas above describe the technologies' scope; consult each folder for the practicals and topics actually included.*

## 📂 Repository Structure

```text
Cloud-Computing/
│
├── AWS/
│   └── AWS practicals and learning resources
│
├── Docker/
│   ├── Flask application
│   ├── Node.js / Express and MongoDB application
│   └── Docker practicals and reference material
│
├── Git/
│   └── Git commands and practical resources
│
├── Kubernetes/
│   └── Kubernetes practicals and learning resources
│
└── README.md
```

> **Note:** This is a high-level representation of the repository. Refer to the actual folders for the complete file structure.

## 🚀 Getting Started

### 1. Clone the Repository

Make sure Git is installed, then run:

```bash
git clone --branch Raj https://github.com/iamrajvardhanmall/Cloud-Computing.git
```

### 2. Navigate to the Project

```bash
cd Cloud-Computing
```

### 3. Explore the Folders

Open the repository in VS Code:

```bash
code .
```

Alternatively, browse the folders directly through your terminal or file explorer.

### 4. Choose a Practical

Navigate to the relevant directory (`AWS`, `Docker`, `Git`, or `Kubernetes`) and follow the instructions or reference files provided for that practical.

**Important:** Install the required tools for each practical before executing commands. Some exercises may require additional configuration, cloud credentials, or environment-specific setup.

## 📋 Prerequisites

Depending on the practical, you may need some of the following tools:

| Tool | Requirement |
|---|---|
| Git | Required for cloning and practicing version control |
| Docker Desktop or Docker Engine | Required for containerization exercises |
| AWS account and AWS CLI | Required for exercises involving AWS services |
| kubectl and a Kubernetes cluster | Required for Kubernetes exercises |
| VS Code or another code editor | Recommended for inspecting and editing files |
| Python or Node.js | Required only for the corresponding application practicals |

Follow the official installation guides:

- [Git](https://git-scm.com/downloads)
- [Docker](https://docs.docker.com/get-started/get-docker/)
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- [Kubernetes Tools](https://kubernetes.io/docs/tasks/tools/)
- [Visual Studio Code](https://code.visualstudio.com/download)

## 🗺️ Practical Learning Roadmap

Use the following roadmap to organize your learning and laboratory preparation.

### 1. Git — Version Control

Learn how to manage source code and collaborate using Git.

Topics to practice:

- Initialize and clone repositories.
- Track changes using `git status` and `git add`.
- Create commits using `git commit`.
- Create and switch branches.
- Merge branches and resolve conflicts.
- Connect local repositories to remote repositories.
- Push and pull changes from GitHub.

### 2. Docker — Containerization

Learn how to package and run applications in containers.

Topics to practice:

- Run and inspect containers.
- Pull, list, and remove Docker images.
- Write Dockerfiles.
- Build custom Docker images.
- Map container ports.
- Use environment variables and volumes.
- Push images to Docker Hub.
- Containerize web applications.

### 3. Kubernetes — Container Orchestration

Understand how containerized applications are deployed and managed.

Topics to practice:

- Create and inspect Pods.
- Deploy applications using Deployments.
- Expose applications through Services.
- Scale application replicas.
- Update and roll back deployments.
- Inspect cluster resources and troubleshoot failures.

### 4. AWS — Cloud Computing

Explore cloud infrastructure and the AWS services covered in the repository.

Topics to practice:

- Understand cloud computing fundamentals.
- Explore relevant AWS services.
- Configure access securely.
- Follow the provided practical instructions for resource creation and management.

*This roadmap is a recommended study sequence, not a claim that every listed exercise is present in the repository.*

## 🎓 Learning Objectives

By working through the relevant practicals, you can develop an understanding of:

- Cloud computing fundamentals and infrastructure.
- Version control and collaborative software development.
- Container images, application packaging, and deployment.
- Kubernetes resource management and orchestration.
- Basic cloud and DevOps workflows.
- Command-line tools and practical troubleshooting.

## 💡 How to Use This Repository

1. **Explore:** Start with the folder corresponding to the technology you want to learn.
2. **Understand:** Read the available instructions, documentation, and source code.
3. **Implement:** Execute the practicals in your local development environment.
4. **Experiment:** Modify examples and observe how the behavior changes.
5. **Troubleshoot:** Review command output and error messages to understand common issues.
6. **Revise:** Practice commands and repeat the exercises before your laboratory examination.

### Recommended Practice Strategy

- Maintain a personal record of commands and their outputs.
- Understand each command instead of memorizing it without context.
- Practice common failure scenarios and troubleshooting steps.
- Verify the results of every operation before moving to the next step.

## 🤝 Contributing

Contributions that improve the repository's learning value are welcome.

To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and test them.
4. Commit your changes with a meaningful message.
5. Open a pull request describing your contribution.

Please ensure that new practicals include clear instructions, required dependencies, and expected results wherever applicable.

## 👨‍💻 Author

**Rajvardhan Mall**

Computer Science student interested in software development, cloud computing, and DevOps technologies.

- GitHub: [@iamrajvardhanmall](https://github.com/iamrajvardhanmall)
- Portfolio: [rajvardhanmall.vercel.app](https://rajvardhanmall.vercel.app/)

## 📄 License

Unless a license file specifies otherwise, the repository's reuse and redistribution terms have not been established here. Add an appropriate `LICENSE` file if you intend to publish the repository under an open-source license.

---

<p align="center">
  <b>Learn by building. Improve by experimenting. Grow through practice. 🚀</b>
</p>
