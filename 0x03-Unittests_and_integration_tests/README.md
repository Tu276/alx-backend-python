0x03. Unittests and Integration Tests
=====================================

UnitTestsBack-endIntegration tests

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/1/f088970b450e82c881ea.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220718T231828Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=76183ce9175e2e6bbf3665a123b4fda4ec8cd1629f051056a04ef04235ea584b)

Unit testing is the process of testing that a particular function returns expected results for different set of inputs. A unit test is supposed to test standard inputs and corner cases. A unit test should only test the logic defined inside the tested function. Most calls to additional functions should be mocked, especially if they make network or database calls.

The goal of a unit test is to answer the question: if everything defined outside this function works as expected, does this function work as expected?

Integration tests aim to test a code path end-to-end. In general, only low level functions that make external calls such as HTTP requests, file I/O, database I/O, etc. are mocked.

Integration tests will test interactions between every part of your code.

Execute your tests with

```

