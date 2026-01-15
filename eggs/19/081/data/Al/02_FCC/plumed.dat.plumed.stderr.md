**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.OTuuNp.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[runnervmmtnos:38014] *** Process received signal ***
[runnervmmtnos:38014] Signal: Aborted (6)
[runnervmmtnos:38014] Signal code:  (-6)
[runnervmmtnos:38014] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd69f645330]
[runnervmmtnos:38014] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd69f69eb2c]
[runnervmmtnos:38014] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd69f64527e]
[runnervmmtnos:38014] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd69f6288ff]
[runnervmmtnos:38014] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd69faa5ff5]
[runnervmmtnos:38014] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd69fabb0da]
[runnervmmtnos:38014] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd69faa5a55]
[runnervmmtnos:38014] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd69faa5a6f]
[runnervmmtnos:38014] [ 8] plumed(+0x146dd)[0x5599d4ac16dd]
[runnervmmtnos:38014] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd69f62a1ca]
[runnervmmtnos:38014] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd69f62a28b]
[runnervmmtnos:38014] [11] plumed(+0x15365)[0x5599d4ac2365]
[runnervmmtnos:38014] *** End of error message ***
</pre>
{% endraw %}
