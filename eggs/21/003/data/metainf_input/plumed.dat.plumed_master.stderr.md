**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmbietmlfzoi:11174] *** Process received signal ***
[pkrvmbietmlfzoi:11174] Signal: Aborted (6)
[pkrvmbietmlfzoi:11174] Signal code:  (-6)
[pkrvmbietmlfzoi:11174] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7315c45330]
[pkrvmbietmlfzoi:11174] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7315c9eb2c]
[pkrvmbietmlfzoi:11174] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7315c4527e]
[pkrvmbietmlfzoi:11174] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7315c288ff]
[pkrvmbietmlfzoi:11174] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f73160a5ff5]
[pkrvmbietmlfzoi:11174] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f73160bb0da]
[pkrvmbietmlfzoi:11174] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f73160a5a55]
[pkrvmbietmlfzoi:11174] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f73160a5a6f]
[pkrvmbietmlfzoi:11174] [ 8] plumed_master(+0x146dd)[0x561679f016dd]
[pkrvmbietmlfzoi:11174] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7315c2a1ca]
[pkrvmbietmlfzoi:11174] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7315c2a28b]
[pkrvmbietmlfzoi:11174] [11] plumed_master(+0x15365)[0x561679f02365]
[pkrvmbietmlfzoi:11174] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmbietmlfzoi:11175] *** Process received signal ***
[pkrvmbietmlfzoi:11175] Signal: Aborted (6)
[pkrvmbietmlfzoi:11175] Signal code:  (-6)
[pkrvmbietmlfzoi:11175] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd57b645330]
[pkrvmbietmlfzoi:11175] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd57b69eb2c]
[pkrvmbietmlfzoi:11175] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd57b64527e]
[pkrvmbietmlfzoi:11175] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd57b6288ff]
[pkrvmbietmlfzoi:11175] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd57baa5ff5]
[pkrvmbietmlfzoi:11175] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd57babb0da]
[pkrvmbietmlfzoi:11175] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd57baa5a55]
[pkrvmbietmlfzoi:11175] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd57baa5a6f]
[pkrvmbietmlfzoi:11175] [ 8] plumed_master(+0x146dd)[0x55e50e2186dd]
[pkrvmbietmlfzoi:11175] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd57b62a1ca]
[pkrvmbietmlfzoi:11175] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd57b62a28b]
[pkrvmbietmlfzoi:11175] [11] plumed_master(+0x15365)[0x55e50e219365]
[pkrvmbietmlfzoi:11175] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmbietmlfzoi exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
