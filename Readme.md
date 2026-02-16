# Ice Test

https://icetest.info


To run it in a docker container:
```
docker build . --network host -t tgabi333/ice-test
docker run -d --net host -v $(pwd)/web:/workspace/ice-test/web --name ice-test tgabi333/ice-test
docker exec -it ice-test bash
```
