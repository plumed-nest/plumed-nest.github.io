**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmbietmlfzoi:11140] *** Process received signal ***
[pkrvmbietmlfzoi:11140] Signal: Aborted (6)
[pkrvmbietmlfzoi:11140] Signal code:  (-6)
[pkrvmbietmlfzoi:11140] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5dde445330]
[pkrvmbietmlfzoi:11140] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5dde49eb2c]
[pkrvmbietmlfzoi:11140] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5dde44527e]
[pkrvmbietmlfzoi:11140] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5dde4288ff]
[pkrvmbietmlfzoi:11140] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5dde8a5ff5]
[pkrvmbietmlfzoi:11140] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5dde8bb0da]
[pkrvmbietmlfzoi:11140] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5dde8a5a55]
[pkrvmbietmlfzoi:11140] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5dde8a5a6f]
[pkrvmbietmlfzoi:11140] [ 8] plumed(+0x146dd)[0x556e730496dd]
[pkrvmbietmlfzoi:11140] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5dde42a1ca]
[pkrvmbietmlfzoi:11140] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5dde42a28b]
[pkrvmbietmlfzoi:11140] [11] plumed(+0x15365)[0x556e7304a365]
[pkrvmbietmlfzoi:11140] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmbietmlfzoi:11141] *** Process received signal ***
[pkrvmbietmlfzoi:11141] Signal: Aborted (6)
[pkrvmbietmlfzoi:11141] Signal code:  (-6)
[pkrvmbietmlfzoi:11141] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff7e1c45330]
[pkrvmbietmlfzoi:11141] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff7e1c9eb2c]
[pkrvmbietmlfzoi:11141] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff7e1c4527e]
[pkrvmbietmlfzoi:11141] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff7e1c288ff]
[pkrvmbietmlfzoi:11141] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff7e20a5ff5]
[pkrvmbietmlfzoi:11141] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff7e20bb0da]
[pkrvmbietmlfzoi:11141] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff7e20a5a55]
[pkrvmbietmlfzoi:11141] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff7e20a5a6f]
[pkrvmbietmlfzoi:11141] [ 8] plumed(+0x146dd)[0x55cd1deb76dd]
[pkrvmbietmlfzoi:11141] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff7e1c2a1ca]
[pkrvmbietmlfzoi:11141] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff7e1c2a28b]
[pkrvmbietmlfzoi:11141] [11] plumed(+0x15365)[0x55cd1deb8365]
[pkrvmbietmlfzoi:11141] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmbietmlfzoi exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
