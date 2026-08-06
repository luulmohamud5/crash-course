# URL Breakdown & Journey of a URL

## Example URL

``` text
https://www.example.com/products/laptops?brand=HP&sort=price#reviews
```

## URL Breakdown

  --------------------------------------------------------------------------
  Component                  Example                  Purpose
  -------------------------- ------------------------ ----------------------
  **Protocol**               `https://`               Creates a secure
                                                      connection.

  **Domain Name**            `www.example.com`        Identifies the
                                                      website.

  **Path**                   `/products/laptops`      Opens a specific
                                                      webpage.

  **Query String**           `?brand=HP&sort=price`   Sends extra
                                                      information, such as
                                                      search filters.

  **Fragment**               `#reviews`               Opens a specific
                                                      section of the page.
  --------------------------------------------------------------------------

## Journey of a URL

When I enter a URL into my browser, **DNS** finds the website's IP
address. The browser then sends an **HTTP/HTTPS request** to the **web
server**, which returns the webpage files (**HTML, CSS, and
JavaScript**). Finally, the browser reads these files and displays the
webpage on the screen.

## Summary

**A URL is the address of a webpage. Each part of the URL helps the
browser locate the correct website, communicate with the server, and
display the exact page the user requests.**
