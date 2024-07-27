#This is my notes on Assembly language studies

##Mainly I'm talking about CPU and Memory

There are two memory parts that we shold take notes on. The registers inside CPU and the Main memory of the program. Retrieving an instruction from the registers takes only one clock cycle, and retrieving it from the L1 cache takes a few cycles, while retrieving it from RAM takes around 200 cycles. When this is done billions of times a second, it makes a massive difference in the overall execution speed.

When we start a program memory gives a small part of allocated memory specific to that program. In this program there are four segments.
    1. Stack - Last in and First Out design. Can access data with pop-ing and push-ing.
    2. Heap - Data can be stored and access in any order
    3. Data - Consist of Data part and bss part
    4. Text - Contain the Main Assembly instructions


