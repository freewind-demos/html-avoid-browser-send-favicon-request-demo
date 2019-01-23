Html Avoid Browser Send Favicon Requests Demo
=============================================

Notice: should find a way to clear browser favicon cache before testing.

```
npm install
npm run demo
```

Then open:

1. <http://localhost:8080/index.html>
2. <http://localhost:8080/index-no-favicon.html>

You will see the log from http-server to see if there is `http://localhost:8080/favicon.ico` requests.
