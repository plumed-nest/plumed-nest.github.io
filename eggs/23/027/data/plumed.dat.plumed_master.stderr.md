**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Cmumd.2ypay0.cpp: In member function ‘virtual void PLMD::colvar::Cmumd::calculate()’:
Cmumd.2ypay0.cpp:291:14: error: invalid use of incomplete type ‘class PLMD::Communicator’
291 |       stride=comm.Get_size();  //Number of processes
|              ^~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:31,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from Cmumd.2ypay0.cpp:22:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.2ypay0.cpp:292:12: error: invalid use of incomplete type ‘class PLMD::Communicator’
292 |       rank=comm.Get_rank(); //Rank of present process
|            ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.2ypay0.cpp:401:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
401 |       comm.Sum(histz);
|       ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.2ypay0.cpp:402:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
402 |       comm.Sum(com_solv);
|       ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.2ypay0.cpp:680:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
680 |       comm.Sum(deriv);
|       ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.2ypay0.cpp:681:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
681 |       comm.Sum(n_CR);
|       ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
Cmumd.2ypay0.cpp:682:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
682 |       comm.Sum(virial);
|       ^~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./Cmumd.2.11.0-dev.so Cmumd.cpp

[runnervmw9dnm:07932] *** Process received signal ***
[runnervmw9dnm:07932] Signal: Aborted (6)
[runnervmw9dnm:07932] Signal code:  (-6)
[runnervmw9dnm:07932] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9acc245330]
[runnervmw9dnm:07932] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9acc29eb2c]
[runnervmw9dnm:07932] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9acc24527e]
[runnervmw9dnm:07932] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9acc2288ff]
[runnervmw9dnm:07932] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9acc6a5ff5]
[runnervmw9dnm:07932] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9acc6bb0da]
[runnervmw9dnm:07932] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9acc6a5a55]
[runnervmw9dnm:07932] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9acc6a5a6f]
[runnervmw9dnm:07932] [ 8] plumed_master(+0x146dd)[0x5595c14fa6dd]
[runnervmw9dnm:07932] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9acc22a1ca]
[runnervmw9dnm:07932] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9acc22a28b]
[runnervmw9dnm:07932] [11] plumed_master(+0x15365)[0x5595c14fb365]
[runnervmw9dnm:07932] *** End of error message ***
</pre>
{% endraw %}
