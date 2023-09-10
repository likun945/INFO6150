#  INFO6150 - BoardGamer HTML Page Readme

## Overview

The **BoardGamer** HTML page is designed to serve as a user interface for a board gaming community. This document provides an overview of the HTML page and explains the purpose of various HTML elements and tags used in its structure.

## Table of Contents

1. [Page Structure](#page-structure)
2. [Favicon](#favicon)
3. [Table](#table)
4. [Form](#form)
5. [Images](#images)
6. [Hyperlink](#hyperlink)
7. [Button](#button)
8. [Audio](#audio)
9. [Video](#video)
10. [Header](#header)
11. [Footer](#footer)
12. [Summary](#summary)
13. [Menu](#menu)
14. [Contact Information](#contact-information)
   - [Telephone Link (tel)](#telephone-link-tel)
   - [Email Link (mailto)](#email-link-mailto)
15. [Mobile Adaptation Plan](#mobile-adaptation-plan)

## Page Structure <a name="page-structure"></a>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags, title, stylesheet, and favicon -->
</head>
<body>
    <!-- Page content -->
</body>
</html>
```

The HTML page is structured with the standard `<!DOCTYPE html>` declaration. It includes metadata, a title, external stylesheets, vue framwork, and a favicon.

## Favicon <a name="favicon"></a>

```html
<link rel="icon" href="/assets/favicon.png" sizes="32x32" type="image/x-icon">
```
![image](https://github.com/likun945/INFO6150/assets/98712201/005cdf0b-5063-4768-9a9f-4fa68024a7f0)

This favicon represents the abbreviation "BG" for BoardGamer.

## Table <a name="table"></a>

```html
<table>
    <!-- Table content -->
</table>
```
<img width="644" alt="1694317096240" src="https://github.com/likun945/INFO6150/assets/98712201/94359612-1a97-43c4-954c-08c725a2e9fb">

Tables are used to organize and display tabular data. The table represents board game information.

## Form <a name="form"></a>

```html
               <form action="submit_registration.php" method="POST">
                    ...
                    <h2>Event Registration</h2>
                    <label for="date">Event Date:</label>
                    <input type="date" id="date" name="date" required><br><br>
                    <label for="comments">Comments:</label><br>
                    <textarea id="comments" name="comments" rows="4" cols="50"></textarea><br><br>
                    <input type="submit" value="Register">
                </form>
```
![image](https://github.com/likun945/INFO6150/assets/98712201/f0e5eebe-d57c-4cba-bf9c-8ac76e6cdd87)

A form for event registration. Users can input their event date and other information.

## Images <a name="images"></a>

```html
<img src="/assets/ticket.jpg" alt="Image Description">
```
![image](https://github.com/likun945/INFO6150/assets/98712201/9b3e019c-a657-49a8-b023-910203f9c952)

Images are embedded using the `<img>` element. The `src` attribute specifies the image file's path, and the `alt` attribute provides alternative text for accessibility.

## Hyperlink <a name="hyperlink"></a>

```html
<a href="https://boardgamegeek.com/boardgame/822" target="_blank">View on BGG</a>
```
![image](https://github.com/likun945/INFO6150/assets/98712201/0306a480-9e9a-45b1-8c8e-9df1ebb42aab)

Hyperlinks are created with the `<a>` element. They link to other web pages or resources, and the `href` attribute defines the destination URL.

## Button <a name="button"></a>

```html
<button type="button" class="green" @click="tab = 0">BoardGame List</button>
```
![image](https://github.com/likun945/INFO6150/assets/98712201/87577ba6-5e08-41a8-b898-839d6cfc2e43)

Buttons are created using the `<button>` element. They can trigger actions when clicked, we could switch the tab card by clicking the button.

## Audio <a name="audio"></a>

```html
<audio id="audio" controls>
   <source src="/assets/dancin.flac" type="audio/mpeg">
   Your browser does not support the audio element.
 </audio>
```
![image](https://github.com/likun945/INFO6150/assets/98712201/98754f5a-efbc-44e6-bd5f-04a118d8104d)

The `<audio>` element is used to embed audio content. The `controls` attribute adds audio controls (play, pause, volume) to the player.

## Video <a name="video"></a>

```html
<video controls>
  <source src="/assets/Ticket to Ride - How To Play.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```
![image](https://github.com/likun945/INFO6150/assets/98712201/a5ef88ed-05bc-4f25-ba9c-c0017a2056a8)

The `<video>` element is used to embed video content. Like audio, it supports the `controls` attribute and multiple `<source>` elements for different video formats.


## Header <a name="header"></a>

```html
<header>
  <h1>Board Games</h1>
</header>
```
![image](https://github.com/likun945/INFO6150/assets/98712201/3793713f-22ed-463f-a75a-1f2d5c42dfb9)

The `<header>` element typically contains content that appears at the top of a webpage, such as navigation links, a site logo, or a page title.

## Footer <a name="footer"></a>

```html
<footer>
  <p>&copy; 2023 Created by KUN LI. All rights reserved.</p>
</footer>
```
![image](https://github.com/likun945/INFO6150/assets/98712201/a91979f6-4ebd-421d-9897-5cf2a6f84cb1)

The `<footer>` element usually contains content that appears at the bottom of a webpage, such as copyright information, contact details, or links to related pages.

## Summary <a name="summary"></a>
                      <details>
                        <summary>Contact Information</summary>
                        <div>
                            <p><strong>Name:</strong> Kun Li</p>
                            <p><strong>Email:</strong> <a href="mailto:kunli@example.com">kunli@example.com</a></p>
                            <p><strong>Phone:</strong> <a href="tel:+1234567890">+1 (234) 567-890</a></p>
                            <p><strong>Address:</strong> 123 Main Street, City, Country</p>
                            <p>
                                <strong>Introduction:</strong> Hello, I'm Kun Li, a board game enthusiast and event
                                organizer. I enjoy bringing people together to play and have fun with board games. Feel
                                free to reach out to me for any inquiries or event registrations!
                            </p>
                        </div>
                    </details>
![image](https://github.com/likun945/INFO6150/assets/98712201/810b46e7-0a50-4058-a8ea-3a641655f96a)

The summary of each section provides a brief information.
