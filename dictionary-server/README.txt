A TCP server that used as dictionary from a key string to a list of strings.

To run the server go to com.dictionaryservice.listener.TCPListener class and run it. You can choose the port that the server will listen by adding it to the running argument or it will use port 1987 by default.

The customized protocol that the server uses is as follow:
accept: 
[method name],[arg1(string)], [arg2(string)] [\n] 
returns: "succes", if the method don't have a return value 
[Value1],[Value2],[Value3]...[\n] when there are values to return

for example request: 
get,key1\n 
return:
value1,value2\n

To verify that the server is up and working fine you can use the client test: go to class com.dictionaryserver.listener.TCPClientTest and run it. verify that there are no exceptions printed in the output.

The keys and values are stored in 


