Working with permissions

chown
chgrp
chmod
su
sudo

RWX => Read Write Execute

rwx-rwx-rwx
 |   |   |
 |   |   |___Other User Permissions
 |   |_______Group owner permissions
 |___________File owner permissions

rwx => 111 => 7
rw- => 110 => 6
r-x => 101 => 5
r-- => 100 => 4