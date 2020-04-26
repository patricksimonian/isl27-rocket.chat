Day 1.

Researched how mongo replica sets work. Over all fairly straight forward of how to add/remove members. 

Found examples of k8s based replica sets. One of these examples using a nodejs side car container to orchestrate replication of mongo pods. 

Checking the image i noticed it was created over a year ago and only under the latest tag. As a test to get it working i created a local image stream for the docker image so that we avoiid 'latest' issues. I took a look through the code base and there isn't much specific to a mongo version. Let's see how this goes!

