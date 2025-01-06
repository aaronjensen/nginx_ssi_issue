# How to run

`docker-compose up --build -d`

## How to test

Run

```
curl localhost
<html>
    <head><title>test</title></head>
    <body>
        <div>i am not empty</div>



        <!-- START -->

            <div>I am a fallback</div>

            <div>I am a fallback</div>

    </body>
</html>
```

And see duplicate SSI stub
