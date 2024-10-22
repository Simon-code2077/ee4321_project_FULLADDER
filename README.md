# ee4321_project
It is the final project repo for EE4321 VLSI.

To have ssh access, please check https://docs.github.com/zh/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

To set-up, cd into your work root, type : git clone git@github.com:Simon-code2077/ee4321_project.git
To do the pull, get the new files from repo, type : git pull
To do the push, update your work to repo, type :   git add .
                                                   git commit -m "description on your change"
                                                   git push

To check if you forget whether you do some change on local : git status


When pulling new schematic files or any other virtuoso files, here would be an access lock. For example, there is a schematic file name "add", created by "hy2891" on host "cadpc09.ee.columbia.edu", the access is defined in file "sdclck", under "./add/schematic/sch.oa.cdslck.RHEL30.*****", change two lines in file from:

LoginName                      hy2891
HostName                       cadpc09.ee.columbia.edu

to:
LoginName                      <your uni>
HostName                       <your host>

Then you will get the full access to schematics.
