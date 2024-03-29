# test

# try to do this question
$$\int_1^2\frac {2x^2+x+1} {(2x-1)(2x^2+x-1)}\ dx$$

# please help me debug 🙇
```
PS C:\Users\Alan6\Course\COMP2012\Pa\skeleton\skeleton> make test
g++ -std=c++11 -g -Wall -fsanitize=address,leak,undefined -MMD -MP -c Buyer.cpp -o Buyer.o
g++ -std=c++11 -g -Wall -fsanitize=address,leak,undefined -MMD -MP -c Food.cpp -o Food.o
g++ -std=c++11 -g -Wall -fsanitize=address,leak,undefined -o PA1_test.exe main_test.o Menu.o Order.o OrderList.o Buyer.o Food.o
c:/program files/mingw/bin/../lib/gcc/x86_64-w64-mingw32/11.2.0/../../../../x86_64-w64-mingw32/bin/ld.exe: cannot find -lasan
c:/program files/mingw/bin/../lib/gcc/x86_64-w64-mingw32/11.2.0/../../../../x86_64-w64-mingw32/bin/ld.exe: cannot find -lubsan
collect2.exe: error: ld returned 1 exit status
make: *** [Makefile:19: PA1_test.exe] Error #
```