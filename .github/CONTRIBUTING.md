# Wishlist Request Instructions

To request a new package for IUS, [create an issue][1] in this repo.  Please
include the following information in your request.

- What package do you want?  Remember that our primary goal is to provide newer
versions of packages from the base repositories.  If the package doesn't
already exist in RHEL/CentOS, consider submitting it to [EPEL][2] instead.

- Why do you need a newer version?  A good reason would be to be able to use a
specific feature that is only available in newer versions of the software.  A
bad reason would be to [pass a security audit][3], because Red Hat actively
[backports security fixes][4] to their stock packages.

- What version of RHEL/CentOS would you like to use it on?  Note that We are no
longer accepting requests for RHEL/CentOS 5.

- Do you agree to test the new package to ensure that it works as expected?  We
don't have any minimum requirements for testing, so use your best judgement and
be as thorough as you feel is appropriate.  We do ask that if we build the
package for multiple versions of RHEL/CentOS that you try to test all the
versions.  Some issues may not be present on all OS versions due to differences
in libraries and init systems.

[1]: https://github.com/iuscommunity/wishlist/issues
[2]: https://fedoraproject.org/wiki/EPEL
[3]: https://ius.io/FAQs/#should-i-use-ius-so-i-can-pass-pci-or-other-security-audits
[4]: https://access.redhat.com/security/updates/backporting
