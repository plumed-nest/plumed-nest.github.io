**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.lCizms.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.10b.so TD_TS-target-plumed2.6.cpp

[fv-az1374-136:67469] *** Process received signal ***
[fv-az1374-136:67469] Signal: Aborted (6)
[fv-az1374-136:67469] Signal code:  (-6)
[fv-az1374-136:67469] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f63df245330]
[fv-az1374-136:67469] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f63df29eb2c]
[fv-az1374-136:67469] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f63df24527e]
[fv-az1374-136:67469] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f63df2288ff]
[fv-az1374-136:67469] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63df6a5ff5]
[fv-az1374-136:67469] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63df6bb0da]
[fv-az1374-136:67469] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63df6a5a55]
[fv-az1374-136:67469] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63df6a5a6f]
[fv-az1374-136:67469] [ 8] plumed(+0x146dd)[0x558c9f4ee6dd]
[fv-az1374-136:67469] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f63df22a1ca]
[fv-az1374-136:67469] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f63df22a28b]
[fv-az1374-136:67469] [11] plumed(+0x15365)[0x558c9f4ef365]
[fv-az1374-136:67469] *** End of error message ***
</pre>
{% endraw %}
