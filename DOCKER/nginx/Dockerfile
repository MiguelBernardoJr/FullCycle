# teve alguns exemplos anterios que eu substitui
# 
# v 1
# FROM ubuntu:latest
# 
# ENTRYPOINT [ "echo", "Hello"]
# 
# CMD [ "World" ]


FROM nginx:latest

COPY html/ /usr/share/nginx/html

ENTRYPOINT ["/docker-entrypoint.sh"]
CMD ["nginx", "-g", "daemon off;"]