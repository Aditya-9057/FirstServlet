# FirstServlet

A beginner Java Servlet project that accepts a name from an HTML form and responds with a personalized greeting.

## How it works

1. Open `login.html`.
2. Enter your name and submit the form.
3. The form sends a `POST` request to `/hello`.
4. `HelloServlet` responds with a greeting.

## Project structure

```text
src/
└── main/
    ├── java/
    │   └── com/adityabhosale/
    │       └── HelloServlet.java
    └── webapp/
        ├── login.html
        └── WEB-INF/
            └── web.xml
