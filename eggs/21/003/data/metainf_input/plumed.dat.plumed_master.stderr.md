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
[pkrvmbietmlfzoi:66119] *** Process received signal ***
[pkrvmbietmlfzoi:66119] Signal: Aborted (6)
[pkrvmbietmlfzoi:66119] Signal code:  (-6)
[pkrvmbietmlfzoi:66119] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc02a45330]
[pkrvmbietmlfzoi:66119] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc02a9eb2c]
[pkrvmbietmlfzoi:66119] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc02a4527e]
[pkrvmbietmlfzoi:66119] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc02a288ff]
[pkrvmbietmlfzoi:66119] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc02ea5ff5]
[pkrvmbietmlfzoi:66119] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc02ebb0da]
[pkrvmbietmlfzoi:66119] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc02ea5a55]
[pkrvmbietmlfzoi:66119] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc02ea5a6f]
[pkrvmbietmlfzoi:66119] [ 8] plumed_master(+0x146dd)[0x5632beefa6dd]
[pkrvmbietmlfzoi:66119] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc02a2a1ca]
[pkrvmbietmlfzoi:66119] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc02a2a28b]
[pkrvmbietmlfzoi:66119] [11] plumed_master(+0x15365)[0x5632beefb365]
[pkrvmbietmlfzoi:66119] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmbietmlfzoi:66118] *** Process received signal ***
[pkrvmbietmlfzoi:66118] Signal: Aborted (6)
[pkrvmbietmlfzoi:66118] Signal code:  (-6)
[pkrvmbietmlfzoi:66118] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4554c45330]
[pkrvmbietmlfzoi:66118] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4554c9eb2c]
[pkrvmbietmlfzoi:66118] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4554c4527e]
[pkrvmbietmlfzoi:66118] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4554c288ff]
[pkrvmbietmlfzoi:66118] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45550a5ff5]
[pkrvmbietmlfzoi:66118] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45550bb0da]
[pkrvmbietmlfzoi:66118] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45550a5a55]
[pkrvmbietmlfzoi:66118] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45550a5a6f]
[pkrvmbietmlfzoi:66118] [ 8] plumed_master(+0x146dd)[0x55745ff686dd]
[pkrvmbietmlfzoi:66118] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4554c2a1ca]
[pkrvmbietmlfzoi:66118] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4554c2a28b]
[pkrvmbietmlfzoi:66118] [11] plumed_master(+0x15365)[0x55745ff69365]
[pkrvmbietmlfzoi:66118] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node pkrvmbietmlfzoi exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
