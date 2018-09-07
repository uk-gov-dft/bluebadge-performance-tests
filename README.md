# performance-tests

To run in headless mode:

```
jmeter -JLOOP_COUNT=2 -JDURATION_SECONDS=10 -DCookieManager.save.cookies=true -n -t performance-test-suite.jmx -l some-log-file.jtl -j output.log -f -e -o test-output/ 2>&1 > jmeter-run.log
```
