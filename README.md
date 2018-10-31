# hbase-thrift
Workouts on Using HBase through HBase Thrift

In order to be able use Thrift, we have to generate language bindings that leads us installing and compiling thrift.  
## Installing Thrift on Mac

1. Install Boost
2. Install libevent
3. Install Thrift

Note: I'm doing this with Mac using Mojave. Before going on, make sure you have updated your 'brew' or re-installed it. Otherwise, it will try downloading wrong version of packages

### Installing Boost
`brew install boost`

### Installing libevent
`brew install libevent`

### Installing Thrift
`brew install thrift` or install manually;  
Download thrift -from http://thrift.apache.org-, browse to the folder you've extracted files and run following command:  
`./configure --prefix=/usr/local/ --with-boost=/usr/local --with-libevent=/usr/local`  
Note: You may need to update bison to a version > 2.5  
The same would be done thru brew
