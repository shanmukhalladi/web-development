# WEB ABL Tasks

This document explains the three WEB ABL tasks using easy English.  
The source code is explained in simple words, and the original output screenshots are also included.

---

# Task 1: Movie Website

## Aim

To design and create a responsive movie website using HTML and CSS to display movie details, ratings, cast, and synopsis in a clean and structured layout.

## HTML Code Explanation

- `<!DOCTYPE html>` tells the browser that the page uses HTML5.
- `<html>` is the main element of the webpage.
- `<head>` contains information about the webpage.
- `<title>` gives the page title.
- `<link>` connects the HTML file with the CSS file.
- `<body>` contains the visible webpage content.

### Main Heading

The main heading displays **Movie World**.  
A second heading welcomes the user to the movie website.

### Navigation Bar

The navigation bar contains:

- Home
- Movies
- About

Anchor (`<a>`) elements are used for the navigation links.

### About Movies

This section gives a short introduction about the website. It tells the user that movie details and ratings are available.

### Popular Movies

The website displays movie information in separate movie sections.

Each movie section contains:

- Movie poster
- Movie name
- Genre
- Release year
- Cast
- Rating
- Synopsis

The source code contains movie information for **Salaar, Baahubali: The Beginning, Kalki 2898 AD, Pushpa, RRR, and Dhurandhar**.

The `<img>` element is used to display movie posters.  
The `src` attribute gives the image file name and `alt` gives alternative text.

The `<h3>` element is used for movie names.  
The `<p>` element is used for movie details.  
The `<b>` element makes labels bold.

The `rate` class is used for movie ratings.

### About Us and Footer

The About Us section gives a short description of the website.

The footer displays **Movie World - 2026**.

## CSS Code Explanation

### Body

The `body` selector sets the background color and font of the webpage.

### Main Heading

The `h1` selector gives the main heading a dark background, white text, centered text, and padding.

### Navigation

The `.nav` class styles the navigation bar with a dark background, padding, and centered text.

### Links

The `a` selector changes the link text color to white and removes the underline.

### Movie Layout

The `.movies` class uses `display: flex` to place movie cards in a row.  
The `gap` property creates space between the cards.

### Movie Card

The `.movie` class creates a movie card using:

- White background
- Border
- Padding
- Width
- Margin

### Movie Images

The `.movie img` rule sets the width and height of movie posters.

### Rating

The `.rate` class changes the rating text color.

### Footer

The footer has a dark background, white text, centered text, and padding.

## Output

![Movie Website Output](WEB_ABL_README_assets/task1_output.png)

---

# Task 2: Student Dashboard

## Aim

To design and develop a responsive Student Dashboard webpage using HTML and CSS to display student details, semester results, attendance, exam schedule, and announcements in a structured layout.

## HTML Code Explanation

- The page uses HTML5 structure.
- The head section contains character settings, viewport settings, page title, and the CSS file connection.
- The body contains the visible dashboard content.

### Main Heading

The main heading displays **Student Dashboard**.

### Navigation Bar

The navigation bar contains:

- Home
- Results
- Attendance
- Exams

The links move to the related sections of the page.

### Student Details

The Student Details section displays:

- Name
- Course
- Semester

### Semester Results

A table is used to display subject marks.

The table contains:

- Subject
- Marks

The source code contains Web Development, Python, GEN-AI, Maths, and English.

The `<table>` element creates the table.  
The `<tr>` element creates a row.  
The `<th>` element creates a heading cell.  
The `<td>` element creates a normal data cell.

### Attendance

The Attendance section displays the attendance percentage.

### Exam Schedule

The Exam Schedule section lists the examination dates for the subjects.

### Announcements

The Announcements section displays important examination and college notices.

### Footer

The footer displays the university name and year.

## CSS Code Explanation

### Body

The `body` selector gives the dashboard a light background, sets the font, and centers the text.

### Main Heading

The `h1` selector gives the heading a colored background, white text, padding, and rounded corners.

### Section Headings

The `h2` selector changes the color of section headings.

### Paragraphs

The `p` selector gives paragraphs a white background, padding, margin, width, and rounded corners.

### Navigation

The `.nav` class styles the navigation bar.

### Links

The `a` selector makes the links white and removes the underline.

### Table

The `table` selector styles the table background, position, and width.

The `th` selector styles the table heading.

The `td` and `th` selectors add borders and padding to table cells.

### Announcements

The `.sem` class styles the announcement area with a white background, padding, margin, width, and rounded corners.

## Output

![Student Dashboard Output 1](WEB_ABL_README_assets/task2_output_1.png)

![Student Dashboard Output 2](WEB_ABL_README_assets/task2_output_2.png)

---

# Task 3: WELLCORE Center Website

## Aim

To design and create a responsive wellness website (WELLCORE Center) using HTML and CSS to showcase yoga, meditation, class schedules, and membership plans in an organized layout.

## HTML Code Explanation

- The page uses HTML5 structure.
- The head section contains the title and CSS file connection.
- The body contains all visible content.

### Main Heading

The main heading displays **WELLCORE Center**.

### Navigation Bar

The navigation bar contains:

- Home
- Yoga
- Meditation
- Classes
- Contact

### Home Section

The Home section welcomes users to the WELLCORE Center.

It explains that yoga and meditation can help people stay healthy and peaceful.

An image is displayed using the `<img>` element.

### Yoga Section

The Yoga section contains a heading, a short description, and a yoga image.

### Meditation Section

The Meditation section explains that meditation helps reduce stress and improve focus.

### Class Schedule

The Class Schedule section displays:

- Morning Yoga - 6:00 AM
- Meditation - 8:00 AM
- Evening Yoga - 5:00 PM

### Membership Plans

The Membership section displays the monthly plan and contact information.

## CSS Code Explanation

### Body

The `body` selector sets a light background, font, centered text, and removes the default margin.

### Main Heading

The `h1` selector gives the website title a green background, white text, padding, and no outside margin.

### Navigation

The `.nav` class gives the navigation bar a green background and padding.

### Links

The `a` selector makes the navigation links white and removes the underline.

### Sections

The `div` selector adds padding and margin to the sections.

### Headings

The `h2` selector changes the section heading color.

### Paragraphs

The `p` selector creates white content boxes with width, padding, margin, and rounded corners.

### Images

The `img` selector gives images rounded corners and a border.

### Button

The `button` selector gives a button a green background, white text, padding, no border, and rounded corners.

## Output

![WELLCORE Output 1](WEB_ABL_README_assets/task3_output_1.png)

![WELLCORE Output 2](WEB_ABL_README_assets/task3_output_2.png)

---

# Important HTML and CSS Concepts Used

| Concept | Simple Meaning |
|---|---|
| `h1` | Main heading |
| `h2` | Section heading |
| `h3` | Smaller heading |
| `p` | Paragraph |
| `a` | Link |
| `img` | Image |
| `div` | Container or section |
| `table` | Creates a table |
| `tr` | Creates a table row |
| `th` | Table heading cell |
| `td` | Table data cell |
| `b` | Makes text bold |
| `footer` | Footer section |
| `background-color` | Changes background color |
| `color` | Changes text color |
| `font-family` | Changes font style |
| `text-align` | Aligns text |
| `padding` | Space between content and border |
| `margin` | Space outside an element |
| `width` | Sets element width |
| `height` | Sets element height |
| `border` | Adds a border |
| `border-radius` | Makes corners rounded |
| `display: flex` | Creates a flexible layout |
| `gap` | Adds space between flex items |
| `text-decoration: none` | Removes link underline |

---

# Conclusion

These three tasks demonstrate the basic use of HTML and CSS.

- The **Movie Website** shows movie information in movie cards.
- The **Student Dashboard** shows student information, marks, attendance, exams, and announcements.
- The **WELLCORE Center** shows yoga, meditation, class schedules, and membership information.

The original output screenshots are preserved in this README.
