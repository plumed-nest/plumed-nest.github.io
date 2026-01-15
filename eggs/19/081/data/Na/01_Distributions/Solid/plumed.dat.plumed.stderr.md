**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Solid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.BW9gJh.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[runnervmmtnos:38439] *** Process received signal ***
[runnervmmtnos:38439] Signal: Aborted (6)
[runnervmmtnos:38439] Signal code:  (-6)
[runnervmmtnos:38439] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd099445330]
[runnervmmtnos:38439] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd09949eb2c]
[runnervmmtnos:38439] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd09944527e]
[runnervmmtnos:38439] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd0994288ff]
[runnervmmtnos:38439] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd0998a5ff5]
[runnervmmtnos:38439] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd0998bb0da]
[runnervmmtnos:38439] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd0998a5a55]
[runnervmmtnos:38439] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd0998a5a6f]
[runnervmmtnos:38439] [ 8] plumed(+0x146dd)[0x5611312fe6dd]
[runnervmmtnos:38439] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd09942a1ca]
[runnervmmtnos:38439] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd09942a28b]
[runnervmmtnos:38439] [11] plumed(+0x15365)[0x5611312ff365]
[runnervmmtnos:38439] *** End of error message ***
</pre>
{% endraw %}
