Document apparent anomalies in configuration of Bundler path and Bundler app_config

```
docker build -f Dockerfile1 -t bundler_tests .
docker run -it --rm bundler_tests > ./output/Dockerfile1.txt

docker build -f Dockerfile2 -t bundler_tests .
docker run -it --rm bundler_tests > ./output/Dockerfile2.txt

docker build -f Dockerfile3 -t bundler_tests .
docker run -it --rm bundler_tests > ./output/Dockerfile3.txt
```
