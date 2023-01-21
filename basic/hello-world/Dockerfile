FROM busybox AS english
LABEL com.org.image.authors="fernandomsilva.devops@gmail.com"
LABEL com.org.image.language="english"
WORKDIR /hello
COPY files .
CMD ["cat", "hello-world.en.txt"]

FROM english AS portuguese
LABEL com.org.image.language="portuguese"
CMD ["cat", "hello-world.pt.txt"]