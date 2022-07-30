# Applying-the-Self-axes-method
Assignment 6 W8D5 - SDA - Software QA Bootcamp

## Table of contents
* [Question](#question)
* [Answer](#answer)
* [Output Screenshots](#output-screenshots)


## Question
Create 3 or 4 examples for XPath by applying the self axes method

## Answer
I used itmeo website https://itmeo.com/
Before running the code, there are some steps that need to take considered:


### First:
Setup Latest Web Driver for Chrome  Driver.
Donwload the necessary jar files:
- Selenium (Lastest).
- TestNG (Lastest).
- commander (Lastest).

### Second:
Add them as a library in the classpath of the project
- _click-reight on the file project >Build path > configure Bild path > Java Build Path > Libraries > classpath > add external JARs > Apply and close_.

### Third:
I Opened the website, then write four Xpath using 'self' axes method.

- XPath= //div[@class='logo']//self::div

<p align="center">
<img src="https://user-images.githubusercontent.com/48597284/182003378-7ccb945a-4c0d-406b-97e0-0ae4e1fc3ab4.png" width=60% height=60%>
</p>

- XPath= //a//self::a[contains(text(),'UI & dashboards')]

<p align="center">
<img src="https://user-images.githubusercontent.com/48597284/182003387-b0a101ee-7a3e-4eb3-97ef-fc144699b4c8.png" width=60% height=60%>
</p>

- XPath= //*//self::a[contains(@class,'product-hunt') and contains(@target,'_blank')]

<p align="center">
<img src="https://user-images.githubusercontent.com/48597284/182003394-fd7d5f22-fc92-42c0-a792-28d853151517.png" width=60% height=60%>
</p>

- XPath= //form//self::input[contains(@placeholder,'Your email address') or @class='footer-subscribe-form__input']

<p align="center">
<img src="https://user-images.githubusercontent.com/48597284/182003407-b6a398c1-b38a-4965-899a-d613d5990b60.png" width=60% height=60%>
</p>


## Output Screenshots:

<p align="center">
<img src="https://user-images.githubusercontent.com/48597284/182003419-d184e1ac-49bb-4120-bd5a-4a3bdb7765de.png" width=80% height=80%>


https://user-images.githubusercontent.com/48597284/182003446-e093cc5c-b7b9-43b7-8de8-55d0a5bbc28d.mp4
</p>
