windows
powershell
$env:path += ";c:/dev/Strawberry/c/bin/"

PS D:\work\makefile_work\ModernMakefile\codes\os\02> $env:path += ";c:/dev/Strawberry/c/bin/"
PS D:\work\makefile_work\ModernMakefile\codes\os\02> gmake
$uname_S is [Windows]
gmake: *** No targets.  Stop.

eric@eric-virtual-machine:~/work/makefile_work/ModernMakefile/codes/os/02$ make
$uname_S is [Linux]
make: *** No targets.  Stop.