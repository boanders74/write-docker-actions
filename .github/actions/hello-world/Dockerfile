2.	FROM golang:1.15
3.	
4.	WORKDIR /go/src/hello
5.	
6.	COPY . .
7.	
8.	RUN go get -d -v ./...
9.	
10.	RUN go install -v ./...
11.	
CMD ["hello"]
