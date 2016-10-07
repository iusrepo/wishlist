# Wishlist Request Instructions

This wishlist is used to request new packages for the IUS repository.  Before
creating a request, [check and see if one already exists][issues].  You can
also check in our [iuscommunity-pkg][iuscommunity-pkg] organization to see if a
repository already exists for that package.  If you need to report an issue for
an existing package, file an issue on that repository, not here.

After verifying your request is actually new, [create an issue][1] in this
repository.  A template will be provided; please make sure to complete all
requested information, as described below.

- What package do you want?  Remember that our primary goal is to provide newer
versions of packages from the base repositories.  If the package doesn't
already exist in RHEL/CentOS, consider submitting it to [EPEL][2] instead.

- Why do you need a newer version?  A good reason would be to be able to use a
specific feature that is only available in newer versions of the software.  A
bad reason would be to [pass a security audit][3], because Red Hat actively
[backports security fixes][4] to their stock packages.

- What version of RHEL/CentOS would you like to use it on?  Note that we are no
longer accepting requests for RHEL/CentOS 5.

- Do you agree to test the new package to ensure that it works as expected?  We
don't have any minimum requirements for testing, so use your best judgement and
be as thorough as you feel is appropriate.  We do ask that if we build the
package for multiple versions of RHEL/CentOS that you try to test all the
versions.  Some issues may not be present on all OS versions due to differences
in libraries and init systems.

[1]: https://github.com/iuscommunity/wishlist/issues/new
[2]: https://fedoraproject.org/wiki/EPEL
[3]: https://ius.io/FAQs/#should-i-use-ius-so-i-can-pass-pci-or-other-security-audits
[4]: https://access.redhat.com/security/updates/backporting
[issues]: https://github.com/iuscommunity/wishlist/issues?q=is%3Aissue
[iuscommunity-pkg]: https://github.com/iuscommunity-pkg
