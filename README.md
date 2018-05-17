# LINE-
Hallo... 

Revolutionofkiller 
Http://github.com/Revolutionofkiller/line-
README.md

51f24fa58ca429dcc1ab25681c0fef970d84b62c 
Db7bb-898bd 
pkg install python2
Hit:1 https://termux.net stable InRelease
Reading package lists... Done
Building dependency tree
Reading state information... Done
7 packages can be upgraded. Run 'apt list --upgradable' to see them.
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following additional packages will be installed:
  gdbm libbz2 libcrypt libffi libsqlite libutil
  ncurses-ui-libs
The following NEW packages will be installed:
  gdbm libbz2 libcrypt libffi libsqlite libutil
  ncurses-ui-libs python2
0 upgraded, 8 newly installed, 0 to remove and 7 not upgraded.
Need to get 7413 kB of archives.
After this operation, 38.3 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 https://termux.net stable/main aarch64 gdbm aarch64 1.14.1 [50.4 kB]
Get:2 https://termux.net stable/main aarch64 libbz2 aarch64 1.0.6-1 [22.9 kB]
Get:3 https://termux.net stable/main aarch64 libcrypt aarch64 0.2 [7148 B]
Get:4 https://termux.net stable/main aarch64 libffi aarch64 3.2.1-2 [6004 B]
Get:5 https://termux.net stable/main aarch64 libsqlite aarch64 3.23.1 [284 kB]
Get:6 https://termux.net stable/main aarch64 libutil aarch64 0.3 [2228 B]
Get:7 https://termux.net stable/main aarch64 ncurses-ui-libs aarch64 6.1.20180331-1 [27.2 kB]
Get:8 https://termux.net stable/main aarch64 python2 aarch64 2.7.15 [7013 kB]
Fetched 7413 kB in 4s (1721 kB/s)
Fetched 7413 kB in 4s (1721 kB/s)
Selecting previously unselected package gdbm.
(Reading database ... 5971 files and directories currently installed.)
Preparing to unpack .../0-gdbm_1.14.1_aarch64.deb ...
Unpacking gdbm (1.14.1) ...
Selecting previously unselected package libbz2.
Preparing to unpack .../1-libbz2_1.0.6-1_aarch64.deb ...
Unpacking libbz2 (1.0.6-1) ...
Selecting previously unselected package libcrypt.
Preparing to unpack .../2-libcrypt_0.2_aarch64.deb ...
Unpacking libcrypt (0.2) ...
Selecting previously unselected package libffi.
Preparing to unpack .../3-libffi_3.2.1-2_aarch64.deb ...
Unpacking libffi (3.2.1-2) ...
Selecting previously unselected package libsqlite.
Preparing to unpack .../4-libsqlite_3.23.1_aarch64.deb ...
Unpacking libsqlite (3.23.1) ...
Selecting previously unselected package libutil.
Preparing to unpack .../5-libutil_0.3_aarch64.deb ...
Unpacking libutil (0.3) ...
Selecting previously unselected package ncurses-ui-libs.
Preparing to unpack .../6-ncurses-ui-libs_6.1.20180331-1_aarch64.deb ...
Unpacking ncurses-ui-libs (6.1.20180331-1) ...
Selecting previously unselected package python2.
Preparing to unpack .../7-python2_2.7.15_aarch64.deb ...
Unpacking python2 (2.7.15) ...
Setting up libutil (0.3) ...
Setting up libbz2 (1.0.6-1) ...
Setting up ncurses-ui-libs (6.1.20180331-1) ...
Setting up gdbm (1.14.1) ...
Setting up libcrypt (0.2) ...
Setting up libsqlite (3.23.1) ...
Setting up libffi (3.2.1-2) ...
Setting up python2 (2.7.15) ...
Setting up pip2...
Collecting setuptools
Collecting pip
Installing collected packages: setuptools, pip
Successfully installed pip-9.0.3 setuptools-39.0.1
$ pkg install git
Hit:1 https://termux.net stable InRelease
Reading package lists... Done
Building dependency tree
Reading state information... Done
7 packages can be upgraded. Run 'apt list --upgradable' to see them.
Reading package lists... Done
Building dependency tree
Reading state information... Done
git is already the newest version (2.17.0-1).
0 upgraded, 0 newly installed, 0 to remove and 7 not upgraded.
$ git clone https://github.com/alfathdirk/LIN3-TCR Cloning into 'LIN3-TCR'...
remote: Counting objects: 73, done.
remote: Total 73 (delta 0), reused 0 (delta 0), pack-reused 73
Unpacking objects: 100% (73/73), done.
$ pip2 install rsa
Collecting rsa
  Downloading https://files.pythonhosted.org/packages/e1/ae/baedc9cb175552e95f3395c43055a6a5e125ae4d48a1d7a924baca83e92e/rsa-3.4.2-py2.py3-none-any.whl (46kB)
    21% |███████                         | 10kB 873    43% |██████████████                  | 20kB 620    65% |█████████████████████           | 30kB 571    87% |████████████████████████████    | 40kB 720    100% |████████████████████████████████| 51kB 546kB/s
Collecting pyasn1>=0.1.3 (from rsa)
  Downloading https://files.pythonhosted.org/packages/ba/fe/02e3e2ee243966b143657fb8bd6bc97595841163b6d8c26820944acaec4d/pyasn1-0.4.2-py2.py3-none-any.whl (71kB)
    14% |████▋                           | 10kB 9.0    28% |█████████▏                      | 20kB 5.7    42% |█████████████▊                  | 30kB 4.0    57% |██████████████████▎             | 40kB 1.7    71% |██████████████████████▉         | 51kB 1.2    85% |███████████████████████████▍    | 61kB 1.4    100% |████████████████████████████████| 71kB 850kB/s
Installing collected packages: pyasn1, rsa
Successfully installed pyasn1-0.4.2 rsa-3.4.2
You are using pip version 9.0.3, however version 10.0.1 is available.
You should consider upgrading via the 'pip install --upgrade pip' command.

$ pip2 install thrift==0.9.3
Collecting thrift==0.9.3
  Downloading https://files.pythonhosted.org/packages/ae/58/35e3f0cd290039ff862c2c9d8ae8a76896665d70343d833bdc2f748b8e55/thrift-0.9.3.tar.gz
Installing collected packages: thrift
  Running setup.py install for thrift ... done
Successfully installed thrift-0.9.3
You are using pip version 9.0.3, however version 10.0.1 is available.
You should consider upgrading via the 'pip install --upgrade pip' command.
$ pip2 install requests
Collecting requests
  Downloading https://files.pythonhosted.org/packages/49/df/50aa1999ab9bde74656c2919d9c0c085fd2b3775fd3eca826012bef76d8c/requests-2.18.4-py2.py3-none-any.whl (88kB)
    11% |███▊                            | 10kB 518    23% |███████▍                        | 20kB 777    34% |███████████                     | 30kB 731    46% |██████████████▊                 | 40kB 645    57% |██████████████████▌             | 51kB 540    69% |██████████████████████▏         | 61kB 623    80% |█████████████████████████▉      | 71kB 717    92% |█████████████████████████████▌  | 81kB 691    100% |████████████████████████████████| 92kB 524kB/s
Collecting certifi>=2017.4.17 (from requests)
  Downloading https://files.pythonhosted.org/packages/7c/e6/92ad559b7192d846975fc916b65f667c7b8c3a32bea7372340bfe9a15fa5/certifi-2018.4.16-py2.py3-none-any.whl (150kB)
  6% |██▏                             | 10kB 5.5M    13% |████▍                           | 20kB 2.2    20% |██████▌                         | 30kB 1.0    27% |████████▊                       | 40kB 1.2    34% |███████████                     | 51kB 1.2    40% |█████████████                   | 61kB 1.4    47% |███████████████▎                | 71kB 1.1    54% |█████████████████▍              | 81kB 1.0    61% |███████████████████▋            | 92kB 1.1    68% |█████████████████████▉          | 102kB 1.    74% |████████████████████████        | 112kB 1.    81% |██████████████████████████▏     | 122kB 1.    88% |████████████████████████████▎   | 133kB 1.    95% |██████████████████████████████▌ | 143kB 1.    100% |████████████████████████████████| 153kB 743kB/s
Collecting chardet<3.1.0,>=3.0.2 (from requests)
  Downloading https://files.pythonhosted.org/packages/bc/a9/01ffebfb562e4274b6487b4bb1ddec7ca55ec7510b22e4c51f14098443b8/chardet-3.0.4-py2.py3-none-any.whl (133kB)
    7% |██▌                             | 10kB 8.2M    15% |█████                           | 20kB 5.0    23% |███████▍                        | 30kB 2.3    30% |█████████▉                      | 40kB 707    38% |████████████▎                   | 51kB 661    46% |██████████████▊                 | 61kB 778    53% |█████████████████▏              | 71kB 799    61% |███████████████████▋            | 81kB 900    69% |██████████████████████▏         | 92kB 820    76% |████████████████████████▋       | 102kB 76    84% |███████████████████████████     | 112kB 76    92% |█████████████████████████████▌  | 122kB 68    99% |████████████████████████████████| 133kB 71    100% |████████████████████████████████| 143kB 626kB/s
    Collecting idna<2.7,>=2.5 (from requests)
  Downloading https://files.pythonhosted.org/packages/27/cc/6dd9a3869f15c2edfab863b992838277279ce92663d334df9ecf5106f5c6/idna-2.6-py2.py3-none-any.whl (56kB)
    18% |█████▉                          | 10kB 8.4    36% |███████████▋                    | 20kB 5.7    54% |█████████████████▍              | 30kB 2.2    72% |███████████████████████▏        | 40kB 1.0    90% |█████████████████████████████   | 51kB 950    100% |████████████████████████████████| 61kB 700kB/s
Collecting urllib3<1.23,>=1.21.1 (from requests)
  Downloading https://files.pythonhosted.org/packages/63/cb/6965947c13a94236f6d4b8223e21beb4d576dc72e8130bd7880f600839b8/urllib3-1.22-py2.py3-none-any.whl (132kB)
    7% |██▌                             | 10kB 5.6M    15% |█████                           | 20kB 1.5    23% |███████▍                        | 30kB 793    30% |██████████                      | 40kB 923    38% |████████████▍                   | 51kB 846    46% |██████████████▉                 | 61kB 983    54% |█████████████████▍              | 71kB 1.0    61% |███████████████████▉            | 81kB 791    69% |██████████████████████▎         | 92kB 882    77% |████████████████████████▊       | 102kB 87    85% |███████████████████████████▎    | 112kB 88    92% |█████████████████████████████▊  | 122kB 82    100% |████████████████████████████████| 133kB 564kB/s
    Installing collected packages: certifi, chardet, idna, urllib3, requests
Successfully installed certifi-2018.4.16 chardet-3.0.4 idna-2.6 requests-2.18.4 urllib3-1.22
You are using pip version 9.0.3, however version 10.0.1 is available.
You should consider upgrading via the 'pip install --upgrade pip' command.









