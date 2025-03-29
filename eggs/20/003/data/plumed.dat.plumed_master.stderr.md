**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.sZhfdI.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.11.0-dev.so TD_TS-target-plumed2.6.cpp

[fv-az1374-136:67502] *** Process received signal ***
[fv-az1374-136:67502] Signal: Aborted (6)
[fv-az1374-136:67502] Signal code:  (-6)
[fv-az1374-136:67502] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd4f3645330]
[fv-az1374-136:67502] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd4f369eb2c]
[fv-az1374-136:67502] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd4f364527e]
[fv-az1374-136:67502] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4f36288ff]
[fv-az1374-136:67502] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4f3aa5ff5]
[fv-az1374-136:67502] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4f3abb0da]
[fv-az1374-136:67502] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4f3aa5a55]
[fv-az1374-136:67502] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4f3aa5a6f]
[fv-az1374-136:67502] [ 8] plumed_master(+0x146dd)[0x559b42f766dd]
[fv-az1374-136:67502] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd4f362a1ca]
[fv-az1374-136:67502] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd4f362a28b]
[fv-az1374-136:67502] [11] plumed_master(+0x15365)[0x559b42f77365]
[fv-az1374-136:67502] *** End of error message ***
</pre>
{% endraw %}
