---
layout: page
title: F.A.Q.
---

**Q: Which languages are supported?**

**A:** Check out our [Platforms](/platforms) page for our list of support frameworks.

**Q: Can I run approval tests with my existing test framework?**

**A:** Yes! Approvals are just an alternative for assertions.
They work with your favorite framework

- JUnit
- MSTest
- NUnit
- MBunit
- RSpec
- Cucumber
- Simple test

**Q: How do I install the Ruby Version?**

`gem install approval_tests`

**Q: What setup is required?**

**A:** None! Just make sure that the jar/dll/gem is accessible.

**Q: How do I start?**

**A:** We suggest you start with the approval kata
Also, read the documentation.

**Q: Are approvals for unit or acceptance tests?**

**A:** Both. Approvals help assert complicated states which is a common blocking problem in acceptance tests. However, it is also a common problem in regular unit testing.

**Q: Can I expand Approvals for `XXXX`?**

**A:** Yes! Approvals can be expanded in many ways. You can add a convenience function to format the output before being approved, you can write your own approval writers to serialize an object to file, you can write your own namers, to deal with special frameworks, and you can write your own approval reporters to display the results of your tests.

**Q: What are the 2 parts of a test?**

1. Do
2. Verify

All tests have this (not only unit tests). With approvals, the second part becomes `Approvals.verify(...)`

**Q: What are the 4 benefits of a unit test?**

1. Specification
2. Feedback
3. Regression
4. Granularity

**Q: What is the testing circle?**

The Testing Circle is the normal everyday pattern I used while doing TDD/BDD. Read [the Blog here](http://blog.approvaltests.com/2012/05/testing-circle.html).
