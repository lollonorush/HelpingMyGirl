# Welcome
Here we learn about webservers

## Principle
Instead of clicking on an html file and open it with google (as known as `browser`) we use a `web-server`.

Basically we can think of the `browser` as a `client`: something that asks for information.

```
Dear web-server can you give me the file called index.html and the styling file called mystyle.css ?
```

The web-server has access to the computer (or more specifically the `file system`), 
and can pass the information to the client.

## How
Web-Server can be incredibly simple to create.

To get started and run your first web-server open `powershell` and type:
```
python -m http.server
```

If everything goes write a text like this will appear:
```
Serving HTTP on :: port 8000 (http://[::]:8000/) ...
```

**To stop the web server**: click on powershell and press at the same time `ctrl+c`

Now that you have started your webserver see what happens if you go on google and type:
```
localhost:8000
```


