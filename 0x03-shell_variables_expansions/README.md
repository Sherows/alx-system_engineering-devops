##0x03. Shell, init files, variables and expansions

0-alias
#!/bin/bash
alias ls="rm *"

1-hello_you
#!/bin/bash
echo "hello $USER"

2-path
#!/bin/bash
export PATH=$PATH:/action

3-paths
#!/bin/bash
echo $((' echo $PATH | grep -o ":/" | wc -1' +1))

4-global_variables
#!/bin/bash
printenv
