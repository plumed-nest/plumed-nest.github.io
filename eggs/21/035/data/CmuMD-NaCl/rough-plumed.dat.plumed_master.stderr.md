**Project ID:** [plumID:21.035]({{ '/' | absolute_url }}eggs/21/035/)  
Stderr for source:  CmuMD-NaCl/rough-plumed.dat   
Download: [zipped raw stdout](rough-plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](rough-plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
Cmumd.o3ImV1.cpp: In member function ‘virtual void PLMD::colvar::CmuMD::calculate()’:
Cmumd.o3ImV1.cpp:290:14: error: invalid use of incomplete type ‘class PLMD::Communicator’
290 |       stride=comm.Get_size();  //Number of processes
|              ^~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from Cmumd.o3ImV1.cpp:22:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.o3ImV1.cpp:291:12: error: invalid use of incomplete type ‘class PLMD::Communicator’
291 |       rank=comm.Get_rank(); //Rank of present process
|            ^~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from Cmumd.o3ImV1.cpp:22:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.o3ImV1.cpp:392:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
392 |       comm.Sum(histz);
|       ^~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from Cmumd.o3ImV1.cpp:22:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.o3ImV1.cpp:393:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
393 |       comm.Sum(com_solv);
|       ^~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from Cmumd.o3ImV1.cpp:22:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.o3ImV1.cpp:644:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
644 |       comm.Sum(deriv);
|       ^~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from Cmumd.o3ImV1.cpp:22:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.o3ImV1.cpp:645:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
645 |       comm.Sum(n_CR);
|       ^~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from Cmumd.o3ImV1.cpp:22:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.o3ImV1.cpp:646:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
646 |       comm.Sum(virial);
|       ^~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from Cmumd.o3ImV1.cpp:22:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./Cmumd.2.11.0-dev.so Cmumd.cpp

[fv-az1215-275:08151] *** Process received signal ***
[fv-az1215-275:08151] Signal: Aborted (6)
[fv-az1215-275:08151] Signal code:  (-6)
[fv-az1215-275:08151] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3c99a42520]
[fv-az1215-275:08151] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3c99a969fc]
[fv-az1215-275:08151] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3c99a42476]
[fv-az1215-275:08151] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3c99a287f3]
[fv-az1215-275:08151] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3c99ea2b9e]
[fv-az1215-275:08151] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3c99eae20c]
[fv-az1215-275:08151] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3c99eae277]
[fv-az1215-275:08151] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3c99eae52b]
[fv-az1215-275:08151] [ 8] plumed_master(+0x14254)[0x55ad4e9ed254]
[fv-az1215-275:08151] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3c99a29d90]
[fv-az1215-275:08151] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3c99a29e40]
[fv-az1215-275:08151] [11] plumed_master(+0x14eb5)[0x55ad4e9edeb5]
[fv-az1215-275:08151] *** End of error message ***
</pre>
{% endraw %}