# Website status checker

## Check a website status with URL.

## Features

-   Enter URL as a query parameter to url
-   Output status check from the website

**Technology**

-   Java
-   Spring Boot

**Development**

-   Use the VS code lense and press "run" in the main
-   The REST api for url check is:

```
/check
```

-   The REST api accepts request parameter named "url"
-   The parameter "url" should be payload type of a string
-   Example request to the app

```
localhost:8080/check?url=https://google.com
```

-   Output message: **"Site is down!"** or **"Site is up!"**
