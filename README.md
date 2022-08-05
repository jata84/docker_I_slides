### Slides
The slides are made with Marpit
To run it local you can use the docker run command bellow

```docker run --rm --init -v $PWD:/home/marp/app -e LANG=$LANG -p 8080:8080 -p 37717:37717 marpteam/marp-cli -s .```