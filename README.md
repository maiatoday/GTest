See [http://www.thebigblob.com/getting-started-with-google-test-on-ubuntu/](http://www.thebigblob.com/getting-started-with-google-test-on-ubuntu/) for a guide to getting started with google test on Ubuntu

```
cmake CMakeLists.txt
make
./runTests
```

now working on the jenkins build

or to get the test results in xml 
```
./runTests --gtest_output="xml:testresults.xml"
```