# Java Study Tracker

Java-based console application for maintaining and managing daily study logs.

## Features

* Add a new study log
* View all study logs
* Export study logs to a CSV file
* Generate study summary by date
* Generate study summary by subject
* Store study details using Java collections

## Technologies Used

* Java
* Object-Oriented Programming
* ArrayList
* TreeMap
* File Handling
* CSV File Handling
* LocalDate API

## Project Structure

```text
Java-Study-Tracker/
│
├── program868.java
├── README.md
└── HOW_TO_RUN.md
```

## Application Menu

```text
1 : Insert new Study Log
2 : View all Study Log
3 : Export study log to CSV
4 : Summary of Study Log by date
5 : Summary of Study Log by subject
6 : Exit the Application
```

## How It Works

The application stores each study record as a `StudyLog` object containing:

* Date
* Subject
* Study Duration
* Description

The `StudyTracker` class manages the study logs using an `ArrayList`.

`TreeMap` is used to generate summaries by date and subject.

The application can also export the stored study records into a CSV file.

## Author

Tanaya Rohidas Khaire
