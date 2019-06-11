---
name: new package request
about: Request a new IUS package
title: ''
labels: ''
assignees: ''

---

<!--
Do you need to report an issue or request an update for an existing package?  If so, you're in the wrong place.  Find the corresponding package source repository in the iusrepo organization (https://github.com/iusrepo) and report an issue there instead.
-->

**What new package do you want?**

<!--
IUS is not a generic RPM repository.  It has the limited scope of providing newer versions of packages already in RHEL.  If the sofware you want is NOT presently available in RHEL, then it is eligible to be added to the EPEL repository, and is out of scope for IUS.

Only one package per issue.

The below text is an EXAMPLE, modify it for your purposes.
-->

foobar 2.0.x

**Why?**

<!--
Give specific reasons why packaging this would be beneficial.

The below text is an EXAMPLE, modify it for your purposes.
-->

In foobar 2.0.0, the `--whiz-bang` flag was added.  This feature would be very useful to me, and RHEL 7 only has foobar 1.8.1.

**Testing**

<!--
You don't need to modify the text below, just read and understand it.
-->

I agree to test the new package to ensure that it works as expected.  Once I am satisfied with the results of my testing I will comment on this issue with the word "STABLE" to get it promoted to the stable repos.
