# Golang Wiki

By: Yehezkiel Wiradhika <br />
NRP: 5025201086 <br />
Class: PBKK D

## About

- Creating a data structure with load and save methods
- Using the net/http package to build web applications
- Using the html/template package to process HTML templates
- Using the regexp package to validate user input
- Using closures

## Tasks

Here are some simple tasks you might want to tackle on your own:

- Store templates in tmpl/ and page data in data/.
- Add a handler to make the web root redirect to /view/FrontPage.
- Spruce up the page templates by making them valid HTML and adding some CSS rules.
- Implement inter-page linking by converting instances of [PageName] to <a href="/view/PageName">PageName</a>. (hint: you could use regexp.ReplaceAllFunc to do this)

## Compilation

To Compile use the following commands

```
$ go build wiki.go
$ ./wiki
```

Then just access `http://127.0.0.1:8080/view/Example`

## References

From the tutorial: https://go.dev/doc/articles/wiki/
