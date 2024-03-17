# unixtools


A set of tools that I have been carrying around for a decade or two.



- column2line - Converts a column of words to a single line, with optional quoting and seperators
- line2column - Converts a line of words to a column
- e2d         - unix epoch time to a date time, e.g.
- now         - this instants datetime as a unix epoch, has simple subtraction/addition of hours,
              minutes, seconds, days, weeks
- psef        - runs 'ps -ef | grep RE' where RE is supplie don the command line


- comdb2_to_rdb - special filter that converts the output from cdb2sql to an RDB format printed to stdout
                comdb2 is a relational database built in-house at Bloomberg L.P.  It is distributed
                under the Apache License v2.  See https://github.com/bloomberg/comdb2
