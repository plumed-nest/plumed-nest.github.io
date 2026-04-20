**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.50JoRC.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[runnervmeorf1:10735] *** Process received signal ***
[runnervmeorf1:10735] Signal: Aborted (6)
[runnervmeorf1:10735] Signal code:  (-6)
[runnervmeorf1:10735] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb909c45330]
[runnervmeorf1:10735] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb909c9eb2c]
[runnervmeorf1:10735] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb909c4527e]
[runnervmeorf1:10735] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb909c288ff]
[runnervmeorf1:10735] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb90a0a5ff5]
[runnervmeorf1:10735] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb90a0bb0da]
[runnervmeorf1:10735] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb90a0a5a55]
[runnervmeorf1:10735] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb90a0a5a6f]
[runnervmeorf1:10735] [ 8] plumed(+0x146dd)[0x5631091406dd]
[runnervmeorf1:10735] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb909c2a1ca]
[runnervmeorf1:10735] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb909c2a28b]
[runnervmeorf1:10735] [11] plumed(+0x15365)[0x563109141365]
[runnervmeorf1:10735] *** End of error message ***
</pre>
{% endraw %}
