# repo-testing
A testing repos for EndeavourOS.

Packages may be the latest and greatest, but they can be outdated. Please check before using.

You may use the repos e.g. with the following addition to your **/etc/pacman.conf**:
<pre>
[endeavouros-testing]
SigLevel = PackageRequired
Server = https://github.com/endeavouros-team/repo-testing/releases/download/assets

[endeavouros-testing-dev]
SigLevel = PackageRequired
Server = https://github.com/endeavouros-team/repo-testing/releases/download/$arch
</pre>
To take advantage of this testing repo, place it before the **[endeavouros]** repo.
