# Likes



## Server

1. Start:
    ```bash
    go run server.go
    ```
1. Add site:
    ```bash
    curl -XPUT localhost:8000/example.com
    ```
1. View sites:
    ```bash
    curl localhost:8000/
    ```
1. Add post:
    ```bash
    curl -XPUT localhost:8000/example.com/1
    ```
1. View posts:
    ```bash
    curl localhost:8000/example.com
    ```
1. Show post stat:
    ```bash
    curl localhost:8000/example.com/1
    ```
