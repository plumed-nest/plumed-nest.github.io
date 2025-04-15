**Project ID:** [plumID:21.035]({{ '/' | absolute_url }}eggs/21/035/)  
Stderr for source:  CmuMD-NaCl/rough-plumed.dat   
Download: [zipped raw stdout](rough-plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](rough-plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
Cmumd.6jqTzk.cpp: In member function ‘virtual void PLMD::colvar::CmuMD::calculate()’:
Cmumd.6jqTzk.cpp:290:14: error: invalid use of incomplete type ‘class PLMD::Communicator’
290 |       stride=comm.Get_size();  //Number of processes
|              ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from Cmumd.6jqTzk.cpp:22:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.6jqTzk.cpp:291:12: error: invalid use of incomplete type ‘class PLMD::Communicator’
291 |       rank=comm.Get_rank(); //Rank of present process
|            ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.6jqTzk.cpp:392:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
392 |       comm.Sum(histz);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.6jqTzk.cpp:393:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
393 |       comm.Sum(com_solv);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.6jqTzk.cpp:644:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
644 |       comm.Sum(deriv);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.6jqTzk.cpp:645:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
645 |       comm.Sum(n_CR);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.6jqTzk.cpp:646:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
646 |       comm.Sum(virial);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./Cmumd.2.10b.so Cmumd.cpp

[fv-az1910-428:65535] *** Process received signal ***
[fv-az1910-428:65535] Signal: Aborted (6)
[fv-az1910-428:65535] Signal code:  (-6)
[fv-az1910-428:65535] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f98eda45330]
[fv-az1910-428:65535] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f98eda9eb2c]
[fv-az1910-428:65535] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f98eda4527e]
[fv-az1910-428:65535] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f98eda288ff]
[fv-az1910-428:65535] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f98edea5ff5]
[fv-az1910-428:65535] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f98edebb0da]
[fv-az1910-428:65535] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f98edea5a55]
[fv-az1910-428:65535] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f98edea5a6f]
[fv-az1910-428:65535] [ 8] plumed(+0x146dd)[0x5572afd436dd]
[fv-az1910-428:65535] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f98eda2a1ca]
[fv-az1910-428:65535] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f98eda2a28b]
[fv-az1910-428:65535] [11] plumed(+0x15365)[0x5572afd44365]
[fv-az1910-428:65535] *** End of error message ***
</pre>
{% endraw %}
