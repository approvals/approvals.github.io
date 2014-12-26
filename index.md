---
layout: page
title: Home
---

# News:
* 3/01/2013 - Listen to the 30 minute [Podcast on Hanselminutes](http://www.hanselminutes.com/360/approval-tests-with-llewellyn-falco)
* 1/02/2013 - Listen to the 43 minute [Podcast on WatirPodcast](http://watirpodcast.com/podcast-53/)
* 7/21/2011 - Listen to the 1 Hour [Podcast on Herding Code](http://www.developerfusion.com/media/122649/herding-code-117-llewellyn-falcon-on-approval-tests/)

> A picture's worth a 1000 tests.

Unit testing asserts can be difficult to use. Approval tests simplify this by taking a snapshot of the results, and confirming that they have not changed.

In normal unit testing, you say `assertEquals(5, person.getAge())`. Approvals allow you to do this when the thing that you want to assert is no longer a primitive but a complex object. For example, you can say, `Approvals.verify(person).`

|   |   |
| :------------ | :---------------: |
| **Step 1:** Create your scenario | ![](https://lh3.googleusercontent.com/-YnReahw8t10/Tc4fT4pBO3I/AAAAAAAAAdw/wmuV2aYHVDE/s288/approval_test_01_whiteboard.png)       |
| **Step 2:** Write that scenario in English | ![](https://lh6.googleusercontent.com/-qbpq8-H7iSk/Tc4glvulw-I/AAAAAAAAAd0/HCQ_bcY6j60/s288/approval_test_02_english.png)  |
| **Step 3:** Translate english to Code | ![](https://lh3.googleusercontent.com/-_2Z0GU6rOS4/T6Wo2qEbGNI/AAAAAAAAAkQ/VT5yRZBKPgQ/s800/approval_test_03_translate.png) |
| **Step 4:** Create Code so it works | ![](https://lh3.googleusercontent.com/-udxQHJw1s-s/Tc4h7siq1NI/AAAAAAAAAd8/BEq9SJ1n_uA/s288/approval_test_04_create.png) |
|**Step 5:** Run your test for feedback while you code | ![](https://lh6.googleusercontent.com/-jI-IyC21_Wo/Tc4kejbp-VI/AAAAAAAAAeE/FsponLUTN4I/s288/approval_test_05_feedback.png)  |
| **Step 6:** Approve result so it continues to work | ![](https://lh3.googleusercontent.com/-3zr61ngUV_0/Tc4jjVgHpNI/AAAAAAAAAeA/jSBv-YTSMXk/s288/approval_test_05_approve.png) |
| **Step 7:** Change the requirement | ![](https://lh6.googleusercontent.com/-G5qp01Qz1T4/Tc4lfNhDjgI/AAAAAAAAAeI/pfVI12_JR90/s288/approval_test_07_change.png) |
| **Step 8:** See the new solution | ![](https://lh4.googleusercontent.com/_s2oZS5jFv1g/Tc4mwITB3MI/AAAAAAAAAeM/3aEgyuLosso/s400/approval_test_08_granularity.png)  |
| **Step 9:** Re-approve so it continues to work | ![](https://lh4.googleusercontent.com/-C9aGPYRCxSo/Tc4nuX-kJ2I/AAAAAAAAAeQ/V-SJ9AEWvMs/s288/approval_test_09_reapprove.png) |

# More info

For more information checkout the [Resources](resources) page...
