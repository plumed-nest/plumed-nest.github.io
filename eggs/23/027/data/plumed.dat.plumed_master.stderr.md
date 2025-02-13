**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Cmumd.BlrqyW.cpp: In member function ‘virtual void PLMD::colvar::Cmumd::calculate()’:
Cmumd.BlrqyW.cpp:291:14: error: invalid use of incomplete type ‘class PLMD::Communicator’
291 |       stride=comm.Get_size();  //Number of processes
|              ^~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from Cmumd.BlrqyW.cpp:22:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.BlrqyW.cpp:292:12: error: invalid use of incomplete type ‘class PLMD::Communicator’
292 |       rank=comm.Get_rank(); //Rank of present process
|            ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.BlrqyW.cpp:401:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
401 |       comm.Sum(histz);
|       ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.BlrqyW.cpp:402:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
402 |       comm.Sum(com_solv);
|       ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.BlrqyW.cpp:680:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
680 |       comm.Sum(deriv);
|       ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.BlrqyW.cpp:681:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
681 |       comm.Sum(n_CR);
|       ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.BlrqyW.cpp:682:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
682 |       comm.Sum(virial);
|       ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./Cmumd.2.11.0-dev.so Cmumd.cpp

[fv-az1046-619:06084] *** Process received signal ***
[fv-az1046-619:06084] Signal: Aborted (6)
[fv-az1046-619:06084] Signal code:  (-6)
[fv-az1046-619:06084] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6be9a45330]
[fv-az1046-619:06084] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6be9a9eb2c]
[fv-az1046-619:06084] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6be9a4527e]
[fv-az1046-619:06084] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6be9a288ff]
[fv-az1046-619:06084] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6be9ea5ff5]
[fv-az1046-619:06084] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6be9ebb0da]
[fv-az1046-619:06084] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6be9ea5a55]
[fv-az1046-619:06084] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6be9ea5a6f]
[fv-az1046-619:06084] [ 8] plumed_master(+0x146dd)[0x55b9a6f636dd]
[fv-az1046-619:06084] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6be9a2a1ca]
[fv-az1046-619:06084] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6be9a2a28b]
[fv-az1046-619:06084] [11] plumed_master(+0x15365)[0x55b9a6f64365]
[fv-az1046-619:06084] *** End of error message ***
</pre>
{% endraw %}
