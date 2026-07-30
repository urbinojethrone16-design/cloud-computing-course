# Reflection: Cloud Computing Concepts and Version Control

## Cloud Services I Use Regularly

In my daily workflow as a student and developer, I interact with several cloud applications to store files, consume media, and communicate.

**1. Google Drive**
* **Service Model:** Software as a Service (SaaS). I use Google Drive directly through a browser or mobile application to store, organize, and edit documents. Google manages the full technology stack, including physical servers, storage infrastructure, and application updates.
* **Deployment Model:** Public Cloud. The infrastructure is owned and operated by Google, serving millions of individual users and organizations over the public internet.

**2. Netflix**
* **Service Model:** Software as a Service (SaaS). As an end-user, I access an on-demand video streaming application. I do not manage or configure underlying cloud hardware, database clusters, or content delivery networks.
* **Deployment Model:** Public Cloud. Netflix runs its core services and databases on public cloud infrastructure (primarily Amazon Web Services), leveraging massive global capacity to stream content seamlessly.

**3. Messenger**
* **Service Model:** Software as a Service (SaaS). Meta provides a fully managed messaging platform for real-time communication and media sharing. Users interact solely with the application layer without managing network protocols or server maintenance.
* **Deployment Model:** Public Cloud. The application runs on Meta's public cloud architecture, accessible worldwide over standard internet connections.

## The Role of Git & GitHub in Cloud Projects

Version control is indispensable when managing modern cloud environments because cloud resources are increasingly created and configured using code (Infrastructure as Code). Using Git ensures that every infrastructure change, configuration update, or script revision is logged with a detailed history of who made the change and why.

GitHub serves as the collaborative hub for cloud development teams. Through branching strategies and pull requests, developers can test and peer-review cloud configurations before deploying them to live production environments. This peer review process significantly reduces configuration errors, security breaches, and accidental service disruptions. If a broken deployment does occur, GitHub enables teams to review the exact commit log and execute a rapid rollback to a stable state, minimizing system downtime.
