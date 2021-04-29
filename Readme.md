# Android assignment demo

First, build the project:
```bash
docker build -t android_test .
```


Then, run this to launch container:

```bash
docker run --name android_test --privileged  --rm -i -t android_test:latest bash
```

To get access to running container, run this in another terminal:

```bash
docker exec -it android_test bash
```

Inside the container, you should already be inside /wdio folder. There, run ```bash ./run.sh``` to run the Android tests.

