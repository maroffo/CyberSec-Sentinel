# CyberSec Sentinel

## Project Overview

CyberSec Sentinel is a web application designed to help users track their software infrastructure components and stay informed about relevant Common Vulnerabilities and Exposures (CVEs). Users can register their software assets (applications, libraries, operating systems, etc.) along with their versions. The application will then monitor various CVE feeds (e.g., from RSS/Atom sources) and notify users if any of their registered assets might be affected by a newly reported vulnerability.

**Core Features (Planned):**

* **User Authentication:** Secure registration and login for users.
* **Infrastructure Component Management:** Allow users to define and manage their infrastructure setups (e.g., "Production Web Server," "Staging Database").
* **Software Asset Tracking:** Within each infrastructure component, users can list specific software assets and their versions (e.g., "Nginx 1.20.1," "Ubuntu 22.04 LTS," "PostgreSQL 14.2," "Log4j 2.17.0").
* **CVE Feed Aggregation:** The system will periodically fetch and parse CVE information from various public feeds.
* **Vulnerability Matching:** Logic to compare registered software assets (name and version) against the details of incoming CVEs.
* **User Notifications:** In-app (and potentially email) notifications to alert users about relevant CVEs impacting their declared assets.
* **Dashboard:** A user-friendly interface to view registered assets, active CVEs, and notifications.

## Purpose of this Project

This project serves as a practical learning exercise for me to **re-familiarize myself with Ruby, Ruby on Rails, and Amazon Web Services (AWS)**.

After spending a significant amount of time working primarily with Python and Google Cloud Platform (GCP), I'm using CyberSec Sentinel as an opportunity to:

* Refresh my Ruby syntax and its core concepts.
* Dive back into the Ruby on Rails framework, its conventions, and best practices for web development.
* Refresh hands-on experience with various AWS services, including (but not limited to):
    * **Amazon RDS/Aurora:** For managed relational databases.
    * **AWS Elastic Beanstalk (with Docker):** For application deployment and management.
    * **Amazon S3:** For static asset storage.
    * **AWS IAM:** For identity and access management.
    * **Amazon CloudWatch:** For logging and monitoring.
    * **Amazon SES:** For email notifications.
* Integrate **Docker** into the development workflow and for deployment, ensuring a consistent environment.

The goal is to build a functional application while solidifying my understanding of these technologies in a modern cloud environment.
