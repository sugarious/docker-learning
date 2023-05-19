1. For Creating Docker Image
    ```docker build -t <name> <path>```
    Example: 
        ```docker build -t myproject .```

2. For Cecking Docker Images available and for running containers
    ```docker images```
    ```docker ps```

3. For docker running
    Here `-p` flags is for port forwarding to local network.
    ```docker run -p 3000:3000 myproject```

4. Use ```rebuild``` script in package json.