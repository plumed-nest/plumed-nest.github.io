**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.vm2sUJ.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.1.so ../../RefCV.cpp

[runnervm76f27:09201] *** Process received signal ***
[runnervm76f27:09201] Signal: Aborted (6)
[runnervm76f27:09201] Signal code:  (-6)
[runnervm76f27:09201] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb622a45330]
[runnervm76f27:09201] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb622a9ec0c]
[runnervm76f27:09201] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb622a4527e]
[runnervm76f27:09201] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb622a288ff]
[runnervm76f27:09201] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb622ea5ff5]
[runnervm76f27:09201] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb622ebb0da]
[runnervm76f27:09201] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb622ea5a55]
[runnervm76f27:09201] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb622ea5a6f]
[runnervm76f27:09201] [ 8] plumed(+0x146dd)[0x55bbb8a256dd]
[runnervm76f27:09201] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb622a2a1ca]
[runnervm76f27:09201] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb622a2a28b]
[runnervm76f27:09201] [11] plumed(+0x15365)[0x55bbb8a26365]
[runnervm76f27:09201] *** End of error message ***
</pre>
{% endraw %}
