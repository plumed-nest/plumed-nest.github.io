**Project ID:** [plumID:21.035]({{ '/' | absolute_url }}eggs/21/035/)  
Stderr for source:  CmuMD-NaCl/rough-plumed.dat   
Download: [zipped raw stdout](rough-plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](rough-plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
Cmumd.amRETa.cpp: In member function ‘virtual void PLMD::colvar::CmuMD::calculate()’:
Cmumd.amRETa.cpp:290:14: error: invalid use of incomplete type ‘class PLMD::Communicator’
290 |       stride=comm.Get_size();  //Number of processes
|              ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from Cmumd.amRETa.cpp:22:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.amRETa.cpp:291:12: error: invalid use of incomplete type ‘class PLMD::Communicator’
291 |       rank=comm.Get_rank(); //Rank of present process
|            ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.amRETa.cpp:392:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
392 |       comm.Sum(histz);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.amRETa.cpp:393:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
393 |       comm.Sum(com_solv);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.amRETa.cpp:644:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
644 |       comm.Sum(deriv);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.amRETa.cpp:645:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
645 |       comm.Sum(n_CR);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.amRETa.cpp:646:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
646 |       comm.Sum(virial);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./Cmumd.2.10.1.so Cmumd.cpp

[runnervmvrwv9:08601] *** Process received signal ***
[runnervmvrwv9:08601] Signal: Aborted (6)
[runnervmvrwv9:08601] Signal code:  (-6)
[runnervmvrwv9:08601] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7944045330]
[runnervmvrwv9:08601] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f794409eb2c]
[runnervmvrwv9:08601] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f794404527e]
[runnervmvrwv9:08601] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79440288ff]
[runnervmvrwv9:08601] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f79444a5ff5]
[runnervmvrwv9:08601] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f79444bb0da]
[runnervmvrwv9:08601] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f79444a5a55]
[runnervmvrwv9:08601] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f79444a5a6f]
[runnervmvrwv9:08601] [ 8] plumed(+0x146dd)[0x55b1d01f46dd]
[runnervmvrwv9:08601] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f794402a1ca]
[runnervmvrwv9:08601] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f794402a28b]
[runnervmvrwv9:08601] [11] plumed(+0x15365)[0x55b1d01f5365]
[runnervmvrwv9:08601] *** End of error message ***
</pre>
{% endraw %}
