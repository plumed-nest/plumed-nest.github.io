**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.B2aQwy.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[runnervmeorf1:11032] *** Process received signal ***
[runnervmeorf1:11032] Signal: Aborted (6)
[runnervmeorf1:11032] Signal code:  (-6)
[runnervmeorf1:11032] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f508a845330]
[runnervmeorf1:11032] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f508a89eb2c]
[runnervmeorf1:11032] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f508a84527e]
[runnervmeorf1:11032] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f508a8288ff]
[runnervmeorf1:11032] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f508aca5ff5]
[runnervmeorf1:11032] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f508acbb0da]
[runnervmeorf1:11032] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f508aca5a55]
[runnervmeorf1:11032] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f508aca5a6f]
[runnervmeorf1:11032] [ 8] plumed(+0x146dd)[0x55ed970886dd]
[runnervmeorf1:11032] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f508a82a1ca]
[runnervmeorf1:11032] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f508a82a28b]
[runnervmeorf1:11032] [11] plumed(+0x15365)[0x55ed97089365]
[runnervmeorf1:11032] *** End of error message ***
</pre>
{% endraw %}
