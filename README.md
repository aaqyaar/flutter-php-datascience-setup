# Flutter-PHP-DataScience Setup Guide

Welcome to the setup guide for the Flutter, PHP and DataScience at Jamhuriya. This document provides step-by-step instructions to ensure you have all the required tools and dependencies set up correctly.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Flutter Setup](#flutter-setup)
- [PHP Environment Setup](#php-environment-setup)
- [Data Science Tools Setup](#data-science-tools-setup)
- [Final Notes](#final-notes)

## Prerequisites

- A computer with Windows/MacOS/Linux.
- At least 8 GB of RAM recommended.
- Stable internet connection.

## Flutter Setup

### 1. Install Flutter SDK:

- Visit the [official Flutter website](https://flutter.dev/docs/get-started/install) and choose the appropriate operating system.
- Follow the installation steps and ensure the Flutter command is accessible globally.

### 2. Install a Code Editor:

- **Recommended**: [Visual Studio Code](https://code.visualstudio.com/) with the Flutter plugin.
- Alternatively, you can use [Android Studio](https://developer.android.com/studio) with the Flutter and Dart plugins installed.

### 3. Verify Installation:

Run the following command to check if everything is set up correctly:

```bash
flutter doctor
```
This will provide a report on any missing dependencies. Follow the recommendations provided by flutter doctor to resolve any issues.

## PHP Environment Setup

### 1. Install a Local Server:

- **For Windows**: [XAMPP](https://www.apachefriends.org/index.html)
- **For MacOS**: [MAMP](https://www.mamp.info/en/downloads/)
- **For Linux**: [LAMP Stack](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-20-04)

### 2. Verify PHP Installation:

Open your terminal or command prompt and type:
```bash
php -v
```
You should see the PHP version information.
### 3. PHP Extensions:
Make sure to enable extensions relevant to your project, such as pdo_mysql or mysqli if you're dealing with MySQL databases.

## Data Science Tools Setup

### 1. Install Python:

Download and install the latest version of Python from [the official Python website](https://www.python.org/downloads/).

### 2. Install Jupyter Notebook:

```bash
pip install jupyterlab
```
Run Jupyter Lab:
```bash Copy code
jupyter lab
```
3. Python Libraries:
Install commonly used data science libraries:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn
```
### Final Notes

Always ensure your tools are up to date to avoid potential compatibility issues.
Regularly backup your project to prevent data loss.
Thanks 
