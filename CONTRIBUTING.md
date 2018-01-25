# Wishlist Request Instructions

This wishlist is used to request new packages for the IUS repository.  Before
creating a request, [check and see if one already exists][issues].  You can
also check in our [iuscommunity-pkg][iuscommunity-pkg] organization to see if a
repository already exists for that package.  If you need to report an issue for
an existing package, file an issue on that repository, not here.

After verifying your request is actually new, [create an issue][create] in this
repository.  A template will be provided; please make sure to complete all
requested information, as described below.

- What package do you want?  Remember that our primary goal is to provide newer
versions of packages from the base repositories.  If the package doesn't
already exist in RHEL/CentOS, consider submitting it to [EPEL][epel] instead.

- Why do you need a newer version?  A good reason would be to be able to use a
specific feature that is only available in newer versions of the software.  A
bad reason would be to [pass a security audit][pci], because Red Hat actively
[backports security fixes][backporting] to their stock packages.

- Do you agree to test the new package to ensure that it works as expected?  We
don't have any minimum requirements for testing, so use your best judgement and
be as thorough as you feel is appropriate.  Once you feel the package is ready
and would like to see it promoted to the stable repos, comment on the issue
with the word "STABLE".

[issues]: https://github.com/iuscommunity/wishlist/issues?q=is%3Aissue
[iuscommunity-pkg]: https://github.com/iuscommunity-pkg
[create]: https://github.com/iuscommunity/wishlist/issues/new
[epel]: https://fedoraproject.org/wiki/EPEL
[pci]: https://ius.io/FAQs/#should-i-use-ius-so-i-can-pass-pci-or-other-security-audits
[backporting]: https://access.redhat.com/security/updates/backporting
