<img src="images/banner.png">

This repository has a single Java file which provides one of the most simplest code to create an AI chatbot.
<br><br>

# Artifacts
The following files are included in this repository.
| Filename | Language | Backend | Connection Type | Comments |
| :-- | :-- | :-- | :-- | :-- |
| chatbot_openai_sync_old.py | Java | OpenAI | Synchronous | Uses older openai==0.28 Python module (Aug 2023) |
<br>

# Installation

1. Install Java, Apache Maven, and Eclipse (see <a href="https://chronicler.tech/ide-setup-eclipse-and-maven-for-java-development-2/">blog</a>$\textcolor{silver}{↗}$).

2. In Eclipse, click on _File_ > _New_ > _Maven Project_.

<ul><img width="50%" src="https://github.com/user-attachments/assets/92cd6004-206c-4951-a8e4-11e0e151f1e2"></ul>

3. Select "Create a simple project (skip archetype selection)" then click _Next_.

<ul><img width="50%" src="https://github.com/user-attachments/assets/660ba7a5-1aff-4218-b0b9-c01c018c2bcd"></ul>

4. Add a group id (e.g., chatbot), artifact id (e.g., chatbot), and description (e.g., MyFirstChatbot) then click _Finish_.

<ul><img width="25%" src="https://github.com/user-attachments/assets/a78eaf89-9233-4f33-bcdf-e6a930e914e0"></ul>

5. Expand "openai" and double-click on `pom.xml` to edit the file.

6. Enter the following content into the pom.xml file.
```
<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0"
  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>

  <groupId>org.cgpt</groupId>
  <artifactId>ChatGPTJavaApplication</artifactId>
  <version>1.0-SNAPSHOT</version>

</project>
```

7. Right-click on `src/main/java` and select _New_ > _Class_.

8. For Name, enter "MyChatbot" then click _Finish_.

9. Add this code to the newly created `chatbot_openai_sync.java` file.
<br>

# Usage

TBD

