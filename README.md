This is a simple demo for command line usage
```
Robot Framework 2.9 or earlier 
[xiaocwan@dhcp test_robotframework]$ pybot -V resource-test.py   test.txt
==============================================================================
Test :: This suite cover all testxxx related cases                            
==============================================================================
case1 - scenario xxx and xxx                                          | PASS |
------------------------------------------------------------------------------
Test :: This suite cover all testxxx related cases                    | PASS |
1 critical test, 1 passed, 0 failed
1 test total, 1 passed, 0 failed
==============================================================================
Output:  /home/xiaocwan/robotFramework_simple_demo/output.xml
Log:     /home/xiaocwan/robotFramework_simple_demo/log.html
Report:  /home/xiaocwan/robotFramework_simple_demo/report.html

```


By default the -L (debug level) is INFO, the print and return from lib func are printed to log.html


##############################################################################
Robot Framework 2.9 or later:
$ mv test.txt test.robot
$ robot -V resource-test.py   test.robot
