
heat stack-create webfarm -f /root/lb-webserver-stack.yaml

ceilometer statistics -m cpu_util -q metadata.user_metadata.stack=8f86c3d5-15cf-4a64-b9e8-70215498c046 -p 600 -a avg

