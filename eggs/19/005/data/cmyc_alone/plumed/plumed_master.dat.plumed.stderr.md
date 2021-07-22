**Project ID:** [plumID:19.005]({{ '/' | absolute_url }}eggs/19/005/)  
Stderr for source:  cmyc_alone/plumed/plumed_master.dat   
(download [zipped raw stdout](plumed_master.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[fv-az95-172:72857] *** Process received signal ***
[fv-az95-172:72857] Signal: Aborted (6)
[fv-az95-172:72857] Signal code:  (-6)
[fv-az95-172:72857] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff31b91e210]
[fv-az95-172:72857] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff31b91e18b]
[fv-az95-172:72857] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff31b8fd859]
[fv-az95-172:72857] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff31bb85911]
[fv-az95-172:72857] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff31bb9138c]
[fv-az95-172:72857] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff31bb913f7]
[fv-az95-172:72857] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ff31bb916a9]
[fv-az95-172:72857] [ 7] plumed(+0xf47d)[0x5575f0f7f47d]
[fv-az95-172:72857] [ 8] plumed(+0x14004)[0x5575f0f84004]
[fv-az95-172:72857] [ 9] plumed(+0xf698)[0x5575f0f7f698]
[fv-az95-172:72857] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff31b8ff0b3]
[fv-az95-172:72857] [11] plumed(+0xf76e)[0x5575f0f7f76e]
[fv-az95-172:72857] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[fv-az95-172:72858] *** Process received signal ***
[fv-az95-172:72858] Signal: Aborted (6)
[fv-az95-172:72858] Signal code:  (-6)
[fv-az95-172:72858] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4eccfa1210]
[fv-az95-172:72858] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f4eccfa118b]
[fv-az95-172:72858] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4eccf80859]
[fv-az95-172:72858] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4ecd208911]
[fv-az95-172:72858] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f4ecd21438c]
[fv-az95-172:72858] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f4ecd2143f7]
[fv-az95-172:72858] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f4ecd2146a9]
[fv-az95-172:72858] [ 7] plumed(+0xf47d)[0x55d9a0e4147d]
[fv-az95-172:72858] [ 8] plumed(+0x14004)[0x55d9a0e46004]
[fv-az95-172:72858] [ 9] plumed(+0xf698)[0x55d9a0e41698]
[fv-az95-172:72858] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f4eccf820b3]
[fv-az95-172:72858] [11] plumed(+0xf76e)[0x55d9a0e4176e]
[fv-az95-172:72858] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpiexec noticed that process rank 0 with PID 0 on node fv-az95-172 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
