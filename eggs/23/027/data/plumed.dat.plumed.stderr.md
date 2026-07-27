**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Cmumd.0Vj5i2.cpp: In member function ‘virtual void PLMD::colvar::Cmumd::calculate()’:
Cmumd.0Vj5i2.cpp:291:14: error: invalid use of incomplete type ‘class PLMD::Communicator’
291 |       stride=comm.Get_size();  //Number of processes
|              ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from Cmumd.0Vj5i2.cpp:22:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.0Vj5i2.cpp:292:12: error: invalid use of incomplete type ‘class PLMD::Communicator’
292 |       rank=comm.Get_rank(); //Rank of present process
|            ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.0Vj5i2.cpp:401:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
401 |       comm.Sum(histz);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.0Vj5i2.cpp:402:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
402 |       comm.Sum(com_solv);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.0Vj5i2.cpp:680:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
680 |       comm.Sum(deriv);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.0Vj5i2.cpp:681:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
681 |       comm.Sum(n_CR);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.0Vj5i2.cpp:682:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
682 |       comm.Sum(virial);
|       ^~~~
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./Cmumd.2.10.1.so Cmumd.cpp

[runnervmvrwv9:05696] *** Process received signal ***
[runnervmvrwv9:05696] Signal: Aborted (6)
[runnervmvrwv9:05696] Signal code:  (-6)
[runnervmvrwv9:05696] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feef5645330]
[runnervmvrwv9:05696] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feef569eb2c]
[runnervmvrwv9:05696] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feef564527e]
[runnervmvrwv9:05696] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feef56288ff]
[runnervmvrwv9:05696] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feef5aa5ff5]
[runnervmvrwv9:05696] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feef5abb0da]
[runnervmvrwv9:05696] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feef5aa5a55]
[runnervmvrwv9:05696] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feef5aa5a6f]
[runnervmvrwv9:05696] [ 8] plumed(+0x146dd)[0x55e0d9f4e6dd]
[runnervmvrwv9:05696] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feef562a1ca]
[runnervmvrwv9:05696] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feef562a28b]
[runnervmvrwv9:05696] [11] plumed(+0x15365)[0x55e0d9f4f365]
[runnervmvrwv9:05696] *** End of error message ***
</pre>
{% endraw %}
