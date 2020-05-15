# sampleGrpcServer
 sample binary grpc server for client test 
 
 ![img](https://grpc.io/img/logos/grpc-icon-color.png){width=250px}

### Get start
```sh
$ ./main -port [your port]
```
run on localhost `0.0.0.0:PORT`

### Proto service

| rpc | request message | response message | |
| ------ | ------ | ------ | ------ |
| checkConnection | any | text | unary
| sendText | text | text | unary
| sum | sumRequest | sumResponse | unary

### Proto message

| message | value name | type |
| ------ | ------ | ------ |
| any | null  | null
| text | text | string
| sumRequest | firstNumber & secondNumber | int
| sumResponse | result  | int
