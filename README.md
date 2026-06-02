# Google Sheets & Google Drive API Integration with Spring Boot

A Java Spring Boot project demonstrating integration with Google Sheets API and Google Drive API using Google Cloud credentials.

## Overview

This project shows how to connect a Spring Boot application with Google Sheets and Google Drive services.

It demonstrates the basic setup required to authenticate with Google APIs, access spreadsheet data, and interact with Google Drive resources from a Java backend application.

## Features

* Google Sheets API integration
* Google Drive API integration
* Google Cloud credentials setup
* Spring Boot backend implementation
* Gradle-based project setup
* Java service-layer implementation
* API authentication using `credentials.json`

## Technology Stack

* Java
* Spring Boot
* Gradle
* Google Sheets API
* Google Drive API
* Google Cloud Console

## Integration Flow

```text
Spring Boot Application
        │
        ▼
Google API Credentials
        │
        ▼
Google Sheets API / Google Drive API
        │
        ▼
Read / Write / Manage Google Resources
```

## Prerequisites

Before running this project, make sure you have:

* Java installed
* Gradle installed
* Google Cloud project created
* Google Sheets API enabled
* Google Drive API enabled
* Google API credentials file generated

## Google Cloud Setup

1. Go to Google Cloud Console.
2. Create a new project.
3. Enable Google Sheets API.
4. Enable Google Drive API.
5. Configure the required OAuth consent screen.
6. Create API credentials.
7. Download the `credentials.json` file.
8. Add the credentials file to your Spring Boot project as required by the implementation.

## Getting Started

### Clone Repository

```bash
git clone https://github.com/mohammadadil-dev/google-sheets-drive-api-springboot.git
cd google-sheets-drive-api-springboot
```

### Build Project

```bash
./gradlew clean build
```

### Run Application

```bash
./gradlew bootRun
```

## Use Cases

This integration can be used for:

* Reading data from Google Sheets
* Writing data to Google Sheets
* Automating spreadsheet updates
* Managing Google Drive files
* Creating reporting tools
* Building lightweight admin/data-entry systems
* Syncing business data between backend systems and Google Workspace

## Learning Outcomes

This project helped me understand:

* Google Cloud API credential setup
* Google Sheets API integration with Java
* Google Drive API integration with Java
* OAuth/API permission setup
* Spring Boot external API integration
* Backend automation using Google Workspace APIs

## Video Tutorial

I have also recorded tutorial videos for this integration.

* Google Sheet Integration With Spring Boot In One Video
  https://www.youtube.com/watch?v=4mP3Fsi4hio&t=39s

* Full Playlist
  https://www.youtube.com/watch?v=Z808S_eSKmI&list=PL2IQ9VnvNu0XF6DrZzsTfu52dHzQNIzRG

## Disclaimer

This repository was created as a learning and demonstration project for integrating Google Sheets and Google Drive APIs with Spring Boot.

Do not commit real API credentials, tokens, or sensitive configuration files to a public repository.

## Author

Mohammad Adil
FinTech Backend Lead | Java Architect | AI Engineer

