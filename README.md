The hardest portion of this project was figuring out how the test cases worked. Because they were in JSON format, they were extremely difficult to read, so we decided to draw out a model to visualize how the router worked. They can be seen below:  

![p3 notes](https://github.com/zarippas/3700project3/blob/main/p3%20notes.png)

For each set of test cases, we followed a similar approach. Firstly, we would run the tests without coding anything, to see what would fail. From there, we would print debug messages to figure out when we should call operations to fix the test case. Finally, we would implement the logic for each method. We would the output of each test case in order to ensure functionality.

One key thing that we did was to do the work by hand and then convert that into an algorithm. This was especially useful for handling IPs and netmasks. Additionally, we would write out the routing tables at different points to make sure we were fully aware of the current condition of the program.

Besides figuring out what the test cases were asking, another challenge we faced was over-engineering specific methods. For instance, at one point of the project we were planning on writing a helper method to find the lowest IP address by converting them to binary and comparing each quad, but then we realized that the less than operator already does this in Python. We tried to design our project to be as readable as possible, and used Python's built in functions whenever we could.

A feature of our code we think is good is that we chose to define as many small functions as possible. This makes the code MUCH easier to debug, since it made it easy to figure out where in each method we made a mistake. Additionally, it made the code base readable and easier to design. We also felt like we utilized filtering within for-loops effectively, and kept a lot of potentially multi-line statements into single ones.
