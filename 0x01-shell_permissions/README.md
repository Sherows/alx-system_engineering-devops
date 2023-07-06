0-iam_betty
#!/bin/bash
su betty

1-who_am_i
#!/bin/bash
whoami

2-groups
#!/bin/bash
group

3-new_owner
#!/bin/bash
chown betty

4-empty
#!/bin/bash
touch hello

5-execute
#!/bin/bash
chmod u+x hello

6-multiple_permissions
#!/bin/bash
chmod ug+x,o+r hello

7-everybody
#!/bin/bash
chmod ugo+x hello


8-James_Bond
#!/bin/bash
chmod 007 hello

9-John_Doe
#!/bin/bash
chmod 753 hello

10-mirror_permissions
#!/bin/bash
chmod --reference==olleh hello

11-directories_permissions
#!/bin/bash
chmod -R +X .

12-directory_permissions
#!/bin/bash
mkdir -m 751 my_dir

13-change_group
#!/bin/bash
chgrp school hello

100-change_owner_and_group
#!/bin/bash
chown vincent:staff *

101-symbolic_link_permissions
#!/bin/bash
chown -h vincent:staff _hello

102-if_only
#!/bin/bash
chown --from=guillaume betty hello

103-Star_Wars
#!/bin/bash
telnet towel.blinkenlights.nl
