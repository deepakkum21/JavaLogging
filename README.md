# JavaLogging

##SLF4J is not a logging framework.

1. If you noticed in the examples above, you don’t need to change anything in your code while changing the logging framework; just the binding jar and the underlying logging implementation (this is the reason why SLF4J is called an abstraction layer and what makes it different from logging frameworks). That’s the beauty of SLF4J and comes in real handy when you write pluggable pieces of code.

### NOTE:

1. SLF4J can be used with one and only one logging implementation of your choice. So, while configuring a new binding and logging implementation, remove the previous one.
2. The binding with the underlying logging framework has to be provided at the deployment time.