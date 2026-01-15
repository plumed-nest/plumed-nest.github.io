**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.TjG8Gi.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10.0.so ../../../../../RefCV.cpp

[runnervmmtnos:37673] *** Process received signal ***
[runnervmmtnos:37673] Signal: Aborted (6)
[runnervmmtnos:37673] Signal code:  (-6)
[runnervmmtnos:37673] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f636ac45330]
[runnervmmtnos:37673] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f636ac9eb2c]
[runnervmmtnos:37673] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f636ac4527e]
[runnervmmtnos:37673] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f636ac288ff]
[runnervmmtnos:37673] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f636b0a5ff5]
[runnervmmtnos:37673] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f636b0bb0da]
[runnervmmtnos:37673] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f636b0a5a55]
[runnervmmtnos:37673] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f636b0a5a6f]
[runnervmmtnos:37673] [ 8] plumed(+0x146dd)[0x56372c9326dd]
[runnervmmtnos:37673] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f636ac2a1ca]
[runnervmmtnos:37673] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f636ac2a28b]
[runnervmmtnos:37673] [11] plumed(+0x15365)[0x56372c933365]
[runnervmmtnos:37673] *** End of error message ***
</pre>
{% endraw %}
