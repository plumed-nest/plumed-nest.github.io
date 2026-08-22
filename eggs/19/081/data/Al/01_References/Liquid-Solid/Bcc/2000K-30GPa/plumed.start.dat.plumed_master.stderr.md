**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.L4VaR8.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[runnervm76f27:08893] *** Process received signal ***
[runnervm76f27:08893] Signal: Aborted (6)
[runnervm76f27:08893] Signal code:  (-6)
[runnervm76f27:08893] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb20b445330]
[runnervm76f27:08893] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb20b49ec0c]
[runnervm76f27:08893] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb20b44527e]
[runnervm76f27:08893] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb20b4288ff]
[runnervm76f27:08893] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb20b8a5ff5]
[runnervm76f27:08893] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb20b8bb0da]
[runnervm76f27:08893] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb20b8a5a55]
[runnervm76f27:08893] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb20b8a5a6f]
[runnervm76f27:08893] [ 8] plumed_master(+0x146dd)[0x56363970d6dd]
[runnervm76f27:08893] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb20b42a1ca]
[runnervm76f27:08893] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb20b42a28b]
[runnervm76f27:08893] [11] plumed_master(+0x15365)[0x56363970e365]
[runnervm76f27:08893] *** End of error message ***
</pre>
{% endraw %}
