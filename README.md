a Zuul application. It forward ```http://localhost:8090/student/xxxx``` to ```http://localhost:8080```

Need to checkout https://github.com/allenlipeng47/SimpleService first.

For example, if request is:

```http://localhost:8090/student/echoStudentName/abcd```

It forwards to:

```http://localhost:8080/echoStudentName/abcd```
 
