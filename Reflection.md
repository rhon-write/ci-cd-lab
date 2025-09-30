1.) Continuous Integration (CI):
It’s the practice of regularly combining (integrating) code from different developers into a shared project. Each time someone commits code, automated checks like building the project and running tests are triggered to catch errors early. In short, CI makes sure the code works well together before it’s merged.

Continuous Delivery/Deployment (CD):
It’s the next step after CI. Once the code passes all tests, CD ensures that it can be automatically packaged and delivered to production (deployment) or at least to a staging environment. The idea is to quickly and safely release new features or fixes to users without manual intervention.

2.)Speed – Tasks like building code, running tests, and deploying software can be done in minutes or seconds, instead of hours if done by hand.
Consistency – Automation ensures the same steps happen the same way every time, reducing “it worked on my machine” problems.
Early bug detection – Automated testing and integration catch issues quickly, before they grow into bigger problems.

3.)Automated testing – Every change goes through unit, integration, or UI tests, which helps catch bugs early.
Consistent builds – Pipelines ensure the software is built the same way every time, reducing “works on my machine” issues.
Frequent releases – Smaller, incremental updates are less risky than big, infrequent releases.
Quick bug fixes – With automation, teams can deliver patches faster and more reliably.
Continuous feedback – Monitoring and pipeline results highlight weak spots in code or tests, improving quality over time.

4.)Tool Selection – Choosing the right CI/CD tools (like Jenkins, GitHub Actions, or GitLab CI) can be confusing since each has pros and cons.
Pipeline Configuration – Writing and maintaining pipeline scripts (build, test, deploy steps) can be tricky, especially at the start.
Integration with Existing Systems – Making the pipeline work smoothly with version control, testing frameworks, cloud platforms, and deployment environments can be challenging.
Test Reliability – If automated tests are unstable (sometimes pass, sometimes fail), they can slow down the whole pipeline.
Environment Differences – Making sure the pipeline runs consistently across dev, staging, and production environments is not always easy.
Security Concerns – Storing secrets (API keys, credentials) safely in the pipeline requires careful setup.
Team Adoption – Getting everyone in the team to trust and properly use the pipeline can take time and training.
