# Blog
Blog repository

This blog is run on the rocker/tidyverse image, which I have installed Blogdown on to and called it blogr. It is then in a container called BlogR

docker run -e USER=user -e PASSWORD=password --rm -p 8787:8787 --name BlogR -v ~/Desktop/Blog/:/home/AoifeONeill/ blogr
