**Project ID:** [plumID:19.005]({{ '/' | absolute_url }}eggs/19/005/)  
Stderr for source:  cmyc_and_10058_F4/plumed/plumed_master.dat   
(download [zipped raw stdout](plumed_master.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[fv-az95-172:72891] *** Process received signal ***
[fv-az95-172:72891] Signal: Aborted (6)
[fv-az95-172:72891] Signal code:  (-6)
[fv-az95-172:72891] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2922d46210]
[fv-az95-172:72891] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2922d4618b]
[fv-az95-172:72891] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2922d25859]
[fv-az95-172:72891] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2922fad911]
[fv-az95-172:72891] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2922fb938c]
[fv-az95-172:72891] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2922fb93f7]
[fv-az95-172:72891] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f2922fb96a9]
[fv-az95-172:72891] [ 7] plumed(+0xf47d)[0x555cd20e147d]
[fv-az95-172:72891] [ 8] plumed(+0x14004)[0x555cd20e6004]
[fv-az95-172:72891] [ 9] plumed(+0xf698)[0x555cd20e1698]
[fv-az95-172:72891] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2922d270b3]
[fv-az95-172:72891] [11] plumed(+0xf76e)[0x555cd20e176e]
[fv-az95-172:72891] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[fv-az95-172:72890] *** Process received signal ***
[fv-az95-172:72890] Signal: Aborted (6)
[fv-az95-172:72890] Signal code:  (-6)
[fv-az95-172:72890] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3e3f8a9210]
[fv-az95-172:72890] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3e3f8a918b]
[fv-az95-172:72890] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3e3f888859]
[fv-az95-172:72890] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3e3fb10911]
[fv-az95-172:72890] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f3e3fb1c38c]
[fv-az95-172:72890] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f3e3fb1c3f7]
[fv-az95-172:72890] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f3e3fb1c6a9]
[fv-az95-172:72890] [ 7] plumed(+0xf47d)[0x564d3447947d]
[fv-az95-172:72890] [ 8] plumed(+0x14004)[0x564d3447e004]
[fv-az95-172:72890] [ 9] plumed(+0xf698)[0x564d34479698]
[fv-az95-172:72890] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3e3f88a0b3]
[fv-az95-172:72890] [11] plumed(+0xf76e)[0x564d3447976e]
[fv-az95-172:72890] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 0 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
