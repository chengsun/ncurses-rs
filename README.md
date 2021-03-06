ncurses-rs ![Build Status](https://travis-ci.org/jeaye/ncurses-rs.png)
==========

There is not yet any test suite, so, rest assured, there
will be bugs. If you find one, please make a ticket and/or
submit a pull request!

## Building
The compiled library will go to the `lib` directory.
```
make clean && make -B
```

## Examples
Examples are built automagically. To run them, check the `bin`
directory. Example numbers increase along with the complexity
of the example.

Current examples:  
**1.** [Hello World](https://github.com/jeaye/ncurses-rs/blob/master/examples/ex_1.rs)  
**2.** [Basic Input & Attributes](https://github.com/jeaye/ncurses-rs/blob/master/examples/ex_2.rs)  
**3.** [Simple Pager](https://github.com/jeaye/ncurses-rs/blob/master/examples/ex_3.rs)  
**4.** [Window Movement](https://github.com/jeaye/ncurses-rs/blob/master/examples/ex_4.rs)  
**5.** [Pager & Syntax Highlighting](https://github.com/jeaye/ncurses-rs/blob/master/examples/ex_5.rs)  

## Thanks
Thanks to pnkfelix for his initial version of this
library, [rust-curses](https://github.com/pnkfelix/rust-curses),
from which ncurses-rs was able to blossom.

