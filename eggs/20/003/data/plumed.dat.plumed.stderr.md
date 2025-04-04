**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.Py1RA2.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.10b.so TD_TS-target-plumed2.6.cpp

[fv-az2207-973:12071] *** Process received signal ***
[fv-az2207-973:12071] Signal: Aborted (6)
[fv-az2207-973:12071] Signal code:  (-6)
[fv-az2207-973:12071] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5408e45330]
[fv-az2207-973:12071] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5408e9eb2c]
[fv-az2207-973:12071] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5408e4527e]
[fv-az2207-973:12071] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5408e288ff]
[fv-az2207-973:12071] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f54092a5ff5]
[fv-az2207-973:12071] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f54092bb0da]
[fv-az2207-973:12071] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f54092a5a55]
[fv-az2207-973:12071] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f54092a5a6f]
[fv-az2207-973:12071] [ 8] plumed(+0x146dd)[0x555e4831e6dd]
[fv-az2207-973:12071] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5408e2a1ca]
[fv-az2207-973:12071] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5408e2a28b]
[fv-az2207-973:12071] [11] plumed(+0x15365)[0x555e4831f365]
[fv-az2207-973:12071] *** End of error message ***
</pre>
{% endraw %}
