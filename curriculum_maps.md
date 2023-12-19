### [Developer Curriculum]( https://static.alta3.com/curriculum/Developer_path.html)
#### Courses:

- Linux Essentials for Developers
- Git and GitHub Essentials
- Git and GitLab Essentials
- Python 101- Basics
- Python 201- APIs and API Design with Python
- Python 202- Python for Network Automation
- Jenkins Automation Server Essentials
- Python 203- Data Sciences
- Python 204- Python and Django for Full Stack Web Developer
- Go Programming Essentials

```mermaid
graph TD
    A[Linux Essentials for Developers] --> B[Git and GitHub Essentials]
    A --> C[Git and GitLab Essentials]
    B --> D[Python 101- Basics]
    C --> D
    D --> E[Python 202- Python for Network Automation]
    D --> F[Python 201- APIs and API Design with Python]
    E --> F
    F --> G[Jenkins Automation Server Essentials]
    F --> H[Python 203- Data Sciences]
    G --> I[Python 204- Python and Django for Full Stack Web Developer]
    H --> I
    F --> I
    I --> J[Go Programming Essentials]
```

### [NetDevOps Curriculum](https://static.alta3.com/curriculum/NetDevOps_path.html)
#### Courses:

- Git and GitHub Essentials
- Git and GitLab Essentials
- TCP/IP Fundamentals
- Python 101- Basics
- Ansible 101- Essentials
- Ansible 102- Dell Storage Devices
- Ansible 201- Network Automation
- Ansible 202- Linux Server Automation
- Ansible 203- Windows Server Automation
- Ansible 301- Customizing Ansible
- Ansible 302- Ansible Tower/Ansible AWX

```mermaid
graph TD
    style Ansible100 fill:#1E90FF
    style Ansible200 fill:#1E90FF
    style Ansible300 fill:#1E90FF

    A[Git and GitHub Essentials] --> B[Python 101- Basics]
    C[Git and GitLab Essentials] --> B
    B --> Ansible100["Ansible 100 Courses- Introduction to Ansible"]
    Ansible100 --> D[Ansible 101- Essentials]
    Ansible100 --> E[Ansible 102- Dell Storage Devices]
    D --> Ansible200["Ansible 200 Courses- Platform Specific"]
    E --> Ansible200
    Ansible200 --> F[Ansible 201- Network Automation]
    Ansible200 --> G[Ansible 202- Linux Server Automation]
    Ansible200 --> H[Ansible 203- Windows Server Automation]
    F --> TCP_IP[TCP/IP Fundamentals]
    F --> Ansible300["Ansible 300 Courses- Advanced Ansible"]
    G --> Ansible300
    H --> Ansible300
    Ansible300 --> I[Ansible 301- Customizing Ansible]
    Ansible300 --> J[Ansible 302- Ansible Tower/Ansible AWX]
```

### [Server Administration Curriculum](https://static.alta3.com/curriculum/ServerAdministration_path.html)
#### Courses:

- Linux Essentials for Developers 
- Git and GitHub Essentials
- Git and GitLab Essentials
- Terraform 101- Infrastructure as Code
- Kubernetes KUBv201v2.6 Administration
- Ansible 201- Network Automation
- TCP/IP Fundamentals
- Jenkins Automation Server Essentials
- Packer Essentials
- Rancher Manager RAN201v2.7

```mermaid
graph TD
    A[Linux Essentials for Developers] --> B[Git and GitHub Essentials]
    A --> C[Git and GitLab Essentials]
    B --> D[Terraform 101- Infrastructure as Code]
    C --> D
    D --> E[Ansible 201- Network Automation]
    D --> F[Kubernetes KUBv201v2.6 Administration]
    D --> G[Jenkins Automation Server Essentials]
    D --> H[Packer Essentials]
    E --> I[TCP/IP Fundamentals]
    F --> J[Rancher Manager RAN201v2.7]
    G --> H
    J --> H
    I --> H
```
