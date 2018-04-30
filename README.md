Create a Thread by Implementing a Runnable Interface

Step 1:

As a first step, you need to implement a run() method provided by a Runnable interface. 
This method provides an entry point for the thread and you will put your complete business logic inside this method. 
Following is a simple syntax of the run() method −

public void run( )

Step 2:

As a second step, you will instantiate a Thread object using the following constructor −

Thread(Runnable threadObj, String threadName);

Where, threadObj is an instance of a class that implements the Runnable interface and threadName is the name given to the new thread.

Step 3:

Once a Thread object is created, you can start it by calling start() method, which executes a call to run( ) method.
Following is a simple syntax of start() method −

void start();
