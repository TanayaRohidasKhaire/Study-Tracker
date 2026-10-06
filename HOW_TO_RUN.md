# How to Run Java Study Tracker

## Prerequisites

Make sure Java JDK is installed on your computer.

Check the Java version using:

```cmd
java -version
```

Check the Java compiler using:

```cmd
javac -version
```

## Step 1: Clone the Repository

Clone the repository using:

```cmd
git clone https://github.com/TanayaRohidasKhaire/Java-Study-Tracker.git
```

Move into the project directory:

```cmd
cd Java-Study-Tracker
```

## Step 2: Compile the Program

Compile the Java source file:

```cmd
javac program868.java
```

## Step 3: Run the Program

Run the application using:

```cmd
java program868
```

## Step 4: Use the Menu

The application displays the following menu:

```text
1 : Insert new Study Log
2 : View all Study Log
3 : Export study log to CSV
4 : Summary of Study Log by date
5 : Summary of Study Log by subject
6 : Exit the Application
```

Enter the option number according to the operation you want to perform.

## CSV Export

When option `3` is selected, the application asks for a CSV file name.

For example:

```text
studylog.csv
```

The generated CSV file contains:

```text
Date,Subject,Duration of study,Description of study
```

along with the stored study records.

## Exit

Select option:

```text
6
```

to exit the application.
