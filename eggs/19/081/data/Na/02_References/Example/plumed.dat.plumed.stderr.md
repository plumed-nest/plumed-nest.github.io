**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.H3Fk06.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[runnervmmtnos:38562] *** Process received signal ***
[runnervmmtnos:38562] Signal: Aborted (6)
[runnervmmtnos:38562] Signal code:  (-6)
[runnervmmtnos:38562] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbd39e45330]
[runnervmmtnos:38562] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbd39e9eb2c]
[runnervmmtnos:38562] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbd39e4527e]
[runnervmmtnos:38562] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbd39e288ff]
[runnervmmtnos:38562] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbd3a2a5ff5]
[runnervmmtnos:38562] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbd3a2bb0da]
[runnervmmtnos:38562] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbd3a2a5a55]
[runnervmmtnos:38562] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbd3a2a5a6f]
[runnervmmtnos:38562] [ 8] plumed(+0x146dd)[0x55b12edff6dd]
[runnervmmtnos:38562] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbd39e2a1ca]
[runnervmmtnos:38562] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbd39e2a28b]
[runnervmmtnos:38562] [11] plumed(+0x15365)[0x55b12ee00365]
[runnervmmtnos:38562] *** End of error message ***
</pre>
{% endraw %}
