# repo-testing
A testing repos for EndeavourOS.

Packages here may be the latest and greatest, but they can be outdated. Please check before using.

At the time of writing this (2019-Sep-08) the [endeavouros-testing] repo is outdated, don't use it.

You may use the repos e.g. with the following addition to your **/etc/pacman.conf**:
<pre>
[endeavouros-testing]
Server = https://github.com/endeavouros-team/repo-testing/releases/download/assets

[endeavouros-testing-dev]
Server = https://github.com/endeavouros-team/repo-testing/releases/download/$arch
</pre>
