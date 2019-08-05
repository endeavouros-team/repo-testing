# repo-testing
A testing repo for EndeavourOS.<br><br>
Contains the latest available packages. And as the name suggests, this is a testing repo, and can include packages that do not always work as expected.<br><br>
You may use the repo e.g. with the following addition to your /etc/pacman.conf:
<pre>
[endeavouros-testing]
SigLevel = PackageRequired
Server = https://github.com/endeavouros-team/repo-testing/releases/download/assets
</pre>
To take advantage of this testing repo, place it before the [endeavouros] repo.
