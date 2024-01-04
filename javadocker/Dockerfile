FROM openjdk:17
RUN mkdir code; \
    cd code;\
    echo "Hello World" >hello-world.txt 

WORKDIR code
COPY Hello.java .
RUN ["touch","newfile.txt"]
RUN ["javac","Hello.java"]
ENTRYPOINT ["java","Hello"]
CMD ["dalai"]