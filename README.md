
### 📦 Project: `ansible-springpetclinic`

This project automates the deployment of the **Spring PetClinic** Java application using **Ansible**.

#### ✅ Features:

* Installs necessary prerequisites (Java, Maven)
* Pulls the Spring PetClinic source code
* Builds the application with Maven
* Starts the app using a systemd service or background task

#### 📂 Playbooks included:

* `prerequisites.yml` – installs required packages
* `install_java.yml` – installs Java
* `install_maven.yml` – installs Maven
* `pull_repo.yml` – clones the PetClinic repo
* `start_app.yml` – starts the Spring Boot application
