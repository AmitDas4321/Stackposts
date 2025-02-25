# Stackposts - Continuous Signup Script

## Overview
Stackposts is a Python-based tool designed to automate user signups on a specified domain. It checks the disallowed domains from Firebase and generates random user information such as full names, usernames, emails, and phone numbers to simulate signups.

## Features
- **Domain Setup**: Allows users to input and change domains.
- **Random User Generation**: Dynamically generates random user details for each signup attempt.
- **Firebase Integration**: Ensures that only allowed domains are used for signups.
- **Logs Successful Signups**: All successful signups are logged in a domain-specific log file.

## Prerequisites
Ensure you have the following installed:
- **Python 3.x**: The script requires Python 3 or later.
- **Internet Connection**: The script communicates with Firebase to check disallowed domains.

## Installation

### 1. Clone the Repository
Clone the repository to your local machine:
```bash
git clone https://github.com/AmitDas4321/Stackposts.git
