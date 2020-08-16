
> docker cp 10c468cbeab5:/var/lib/ghost ~/c/Arturs/docker


> docker run -d --name some-ghost8 -p 3003:2368 -v /c/arturs/docker/ghost:/var/lib/ghost -e url=http://localhost:3003 ghost