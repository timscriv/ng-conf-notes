# Jeff Whelpley & Patrick Stapleton - Angular Universal

- github.com/angular/univeral
- Problems solved by patters
    - Gap Events
        - user events before the client JS takes over
        - preboot will replay all events
    - Async
        - 
    - Dependencies
        - platform specific (like window) that doesn't exist on the server
        - can use stores to implement localstorage that is different based on the platform used