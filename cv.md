## Valeriy V. Vorotyntsev

- Email: valery.vv@gmail.com
- GitHub: https://github.com/vvv
- LinkedIn: https://www.linkedin.com/in/vorotylo/

## Summary

Skilled Rust programmer seeking a role as an individual contributor in a dynamic and innovative team. Passionate about sharing knowledge, mentoring others, and creating user-focused tools. Eager to explore new programming languages like Zig and domains such as drone flight controller programming. An advocate for open-source coding, work-life balance, and a collaborative work culture. Open to opportunities in mature startups, with a preference for environments that promote a balanced lifestyle.

## Skills

**Programming Languages**: 
- Rust, Bash, Python
- Years of C and Haskell experience, but prefer not to use in the future

**Functional Programming**: 
- Proficient in functional programming principles, using languages like Emacs Lisp, Haskell, Elm, Dhall, and Rust

**Languages**: 
- Native in Ukrainian, fluent in English

**Operating Systems**: 
- Extensive development experience on Linux platform (Red Hat/Fedora/CentOS, Debian/Ubuntu, Amazon Linux 2)

**CI/CD**: 
- Experience defining CI workflows for GitLab and GitHub Actions
- Applied Dhall configuration language to reduce code duplication

**Containerization and Orchestration**: 
- Familiar with Docker (Dockerfiles, docker compose) and basic interaction with Kubernetes (`kubectl`, OpenLens)

**Cloud Technologies**:
- Experienced with AWS services including EC2, EBS, S3, ECS, CloudFront, and Lambda

**API Tools**: 
- Experienced in implementing and debugging HTTP APIs using tools like Insomnia, Postman, and Wireshark

**Performance Engineering**:
- Proficient in performance engineering tools like Criterion and flamegraph-rs

**Security**: 
- Basic exposure to computer security domain through work on a ransomware detection team

**Documentation**:
- Experience writing technical specifications in the form of RFC-like documents

**Version Control**:
- Proficient with Git, recognized as team's "Bash/Git go-to guy"

**Editors**: 
- Proficient with vanilla & Doom Emacs, VS Code, Neovim

**AI Assistants:**
- Proficient in utilizing AI tools like ChatGPT-4 and CoPilot in daily tasks

**Leadership and Mentoring**:
- Team leadership and mentoring experience

## Work Experience

### March 2023–May 2023: Senior Software Engineer at ZincLabs

ZincLabs is a start-up focused on cloud-based technologies. I joined as the 6th member of the team and contributed primarily to the ZincObserve project on the backend team. 

**Project:** [ZincObserve]

[ZincObserve]: https://github.com/zinclabs/zincobserve

**Contributions**:
- Collaborated in R&D, resulting in the design and implementation of a robust PromQL execution engine 
- Developed a variety of HTTP APIs, including dashboards and Prometheus integrations, which enhanced user experience
- Increased the performance of the PromQL engine by 38% through rigorous benchmarking and optimization
- Overhauled existing codebase, improving code maintainability and clarity, and created comprehensive documentation for future team members 

**Technologies**:
- Utilized Apache Arrow, DataFusion for data manipulation and querying
- Incorporated Prometheus, Grafana for monitoring and visualization 
- Leveraged AWS, GCS for cloud computing and storage solutions
- Interacted with Kubernetes (k8s) and etcd for container orchestration

### January 2023–March 2023: Senior Rust Engineer, Evinced (contracted through Grid Dynamics)

**Project:** [Mobile Flow Analyzer][MFA] (accessibility testing toolkit)

[MFA]: https://www.evinced.com/products/flow-analyzer-for-mobile

**Team:** R&D

**Key Contributions:**

- **Redesigned and Optimized CLI Application:** Led the successful revamp of a command-line interface application used for generating comprehensive Android and XCUI testing reports, enhancing overall efficiency and user experience.

- **Developed WebSocket IPC Library:** Implemented a WebSocket inter-process communication library, providing functionality for obtaining custom data, such as font information and color details, from mobile devices, thus enriching data analysis capability.

**Key Technologies:**

- Asynchronous programming (Tokio)
- WebSockets
- Transport Layer Security (TLS)

### December 2022-January 2023: Freelance Performance Optimization Consultant, ZincLabs

**Project:** [ZincObserve]

In this freelance engagement, I was tasked with exploring performance optimization opportunities for ZincObserve's search engine.

Key Responsibilities and Achievements:

- Conducted comprehensive investigation into potential performance enhancements for the application.
- Gained substantial expertise in working with Parquet, Arrow, and DataFusion technologies.
- Delivered actionable insights and recommendations to optimize application performance, contributing to improved project outcomes.

Technologies Used:

- Arrow
- DataFusion
- Parquet

### October 2020–December 2022: Rust Developer, Elastio

[Elastio](https://elastio.com/) is a startup that provides backup and recovery solutions for AWS customers. The company uses machine learning, signatures, and heuristics to scan AWS Backup data for ransomware, malware, and corruption, ensuring clean recoveries.

In this role, I made significant contributions to the core functionality of the product and the improvement of team productivity and project outcomes.

Key Responsibilities and Achievements:

- Developed and implemented robust ransomware detection software in Rust, contributing to Elastio's core mission of providing secure recovery options for AWS customers.
- Created a variety of R&D tools using Bash, Python, and Rust, furthering the company's product development efforts.
- Improved the ergonomics of the `elastio` CLI tool, enhancing user experience and ease of use.
- Developed a configuration crate akin to `aws config`, contributing to the seamless integration of Elastio with AWS Backup.
- Improved the maintainability of CI definitions, including the application of `github-actions-dhall`, promoting an efficient and agile development environment.
- Programmed gRPC API services in Rust, expanding service offerings and improving system efficiency.

Technologies Used:

- Rust
- Bash
- Python
- AWS (EBS, EC2, ECR, Lambda, S3)
- Protobuf
- Docker
- GitHub Actions CI
- jq
- Dhall

### July 2011 - October 2020: Various Roles at Xyratex / Seagate

During my time at Seagate, which absorbed Xyratex, I was privileged to participate in the development of an object storage system project, which pivoted into an archival solution and then a hybrid cloud. This codebase was eventually open-sourced in autumn 2020 as the [CORTX Motr Project](https://github.com/Seagate/cortx-motr).

#### Team Lead, "Hare" team (July 2019 - August 2020)
Leading a 5-person team, we successfully replaced the legacy High Availability (HA) system with a simpler Consul-based solution. I innovated our team structure and communication with the [PC3] collaboration model, resulting in increased team efficiency and satisfaction. Additionally, I introduced RFC practices and enhanced test automation, CI, and merge bot systems. Key technologies employed included Python, Dhall, Bash, Consul, and GitLab CI.

[PC3]: https://github.com/Seagate/cortx-hare/blob/6915b5670f12c666900261dfbef56b8e719054a0/rfc/9/README.md

#### Haskell Programmer, Team Lead (May 2017 - June 2019)
I took the reins of a 50K-line High Availability (HA) solution written in Haskell, mentoring five colleagues new to Haskell programming along the way. This team transitioned to functional maintenance work and feature development within a few months. The primary technology used during this time was Cloud Haskell.

#### C Programmer (June 2011 - May 2017)
In the early stages of my tenure, I was responsible for designing and implementing several key features, including a configuration caching subsystem, a modular initialization/finalization mechanism, and a memory-efficient representation of device pools. Additionally, I developed helper scripts that were positively received by the team. Technologies used included C, Python, Bash, and Expect.

### 2006 - 2010: Telecom Data Processing Engineer at UMC / MTS

During my tenure at UMC, which was acquired by MTS and then rebranded as Vodafone, I maintained and developed software for Call Detail Record (CDR) processing using C++ and Python. Key accomplishments include:

- Developed a custom templating engine using an `m4` macro library, improving efficiency in generating wiki documentation for data format converters.
- Created a CLI tool in C for converting DER-encoded Call Detail Record (CDR) files to text format (s-expressions) and vice versa, enabling CDR file filtering and modifications.
- Pioneered the introduction of Python into the unit's tech stack, previously solely C++, thereby improving delivery speed.

### 1999 - 2006: Software Developer at ИТЦ ПК, subcontracted by GSE Systems

Worked on projects developing nuclear power plant (NPP) simulators, focusing on the Plant Process Computer (PPC) subsystem. The role involved both adapting existing software and creating new tools to provide realistic, detailed simulation experiences. Key responsibilities and achievements included:

- Successfully ported the PPC dashboard system from IRIX to Linux, which involved customizing and integrating an array of C programs originally designed for a different NPP unit. This work provided invaluable experience in Linux and C programming.
- Designed and implemented a client-server GUI application in C++, adding representation for a specific NPP unit component not included in the original software package. The server read data from IPC System V shared memory and sent it via a TCP socket to the client for graphical display.
- Developed a CGI server for report generation using Python, marking my introduction to the language and broadening the toolkit for future projects.
- For a subsequent analytical NPP simulator project, I leveraged my Python skills to develop a program that parsed display description files and generated files in the `DataViews` format. This enabled the viewing of PPC displays on the Instructor Station, enhancing the simulator's functionality and usability.

Technologies utilized: SysV IPC (shmem), TCP sockets, X11, gdbm, C, C++, Bash, awk, Python, gtkmm, ACE framework, Trac (issues & wiki), `DataViews`.

### Education

**National Technical University of Ukraine "Kyiv Polytechnic Institute"**, Kyiv, Ukraine, 1993-1999
- Degree: Avionics Engineer (Honors)

**Kyiv Natural Science Lyceum No. 145**, Kyiv, Ukraine, 1989-1993
- Received a Certificate of Distinction for Outstanding Achievements in Mathematics Study.

### Community Involvement

- Organized the LtU-Kyiv Haskell Hackathon, an event designed to gather Haskell enthusiasts and foster knowledge sharing and coding collaboration.
- Served as a team lead for a group of Android developers in IT Volunteering Project in 2015.
- Facilitated study groups to explore and learn Haskell and Elm programming languages.
- Organized Rust Hack & Learn meetup in Kyiv.
