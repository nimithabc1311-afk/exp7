# Experiment 7 – Adaptive UI using ListView and ImageView

## Student Information

| Details | Information |
|---|---|
| Name | Nimitha BC |
| USN | 25MCAR0132 |
| Course | MCA |
| Experiment | Experiment 7 |
| Project Name | Exp7 |
| Application Name | Student Explorer |
| Package Name | com.example.exp7 |

---

## 1. Aim

To create an adaptive Android user interface using **ListView** and **ImageView** to display student information in a structured and scrollable list.

---

## 2. Objective

The objectives of this experiment are:

- To understand the use of `ListView` in Android.
- To understand the use of `ImageView`.
- To create a custom ListView item layout.
- To display multiple student records dynamically.
- To use a custom adapter with ListView.
- To create a simple and responsive user interface.
- To test the application with different student records.

---

## 3. Scenario

The application is designed as a **Student Explorer** application.

It displays a list of students along with:

- Student name
- USN
- Course
- Subject
- Student image

The information is displayed using a `ListView`. Each list item contains an `ImageView` and multiple `TextView` components.

The ListView allows the user to scroll through multiple student records.

---

## 4. Concept / Technology Used

### Android Development

The application is developed using Android Studio and Kotlin.

### ListView

`ListView` is used to display multiple items in a vertically scrollable list.

### ImageView

`ImageView` is used to display an image for each student.

### Custom Adapter

A custom adapter named `StudentAdapter` is used to connect the student data with the ListView.

### XML Layout

XML layouts are used to design:

- Main application screen
- Individual student list item

### Kotlin

Kotlin is used for application logic and data handling.

---

## 5. Features

The application provides the following features:

1. Displays the application title.
2. Displays an experiment subtitle.
3. Displays multiple student records.
4. Uses ListView for scrolling.
5. Uses ImageView for student icons.
6. Displays student name and USN.
7. Displays course and subject.
8. Uses a custom ListView adapter.
9. Supports multiple records in a single screen.
10. Provides a simple and user-friendly interface.

---
## 6 Output
<img width="1920" height="1020" alt="Mad exp 7" src="https://github.com/user-attachments/assets/79d92619-dd9a-44fc-a028-f9223a908f4e" />


## 7. Application Structure

```text
Exp7
│
├── app
│   │
│   └── src
│       │
│       └── main
│           │
│           ├── java
│           │   └── com
│           │       └── example
│           │           └── exp7
│           │               ├── MainActivity.kt
│           │               ├── Student.kt
│           │               └── StudentAdapter.kt
│           │
│           ├── res
│           │   ├── layout
│           │   │   ├── activity_main.xml
│           │   │   └── student_list_item.xml
│           │   │
│           │   └── values
│           │       └── strings.xml
│           │
│           └── AndroidManifest.xml
│
├── screenshots
│   ├── main_output.png
│   ├── test_case_1.png
│   ├── test_case_2.png
│   └── test_case_3.png
│
└── README.md
