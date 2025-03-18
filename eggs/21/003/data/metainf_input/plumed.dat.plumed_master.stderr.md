**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1377-740:64916] *** Process received signal ***
[fv-az1377-740:64916] Signal: Aborted (6)
[fv-az1377-740:64916] Signal code:  (-6)
[fv-az1377-740:64916] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3daee45330]
[fv-az1377-740:64916] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3daee9eb2c]
[fv-az1377-740:64916] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3daee4527e]
[fv-az1377-740:64916] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3daee288ff]
[fv-az1377-740:64916] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3daf2a5ff5]
[fv-az1377-740:64916] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3daf2bb0da]
[fv-az1377-740:64916] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3daf2a5a55]
[fv-az1377-740:64916] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3daf2a5a6f]
[fv-az1377-740:64916] [ 8] plumed_master(+0x146dd)[0x55aa1db2f6dd]
[fv-az1377-740:64916] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3daee2a1ca]
[fv-az1377-740:64916] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3daee2a28b]
[fv-az1377-740:64916] [11] plumed_master(+0x15365)[0x55aa1db30365]
[fv-az1377-740:64916] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1377-740:64915] *** Process received signal ***
[fv-az1377-740:64915] Signal: Aborted (6)
[fv-az1377-740:64915] Signal code:  (-6)
[fv-az1377-740:64915] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc359845330]
[fv-az1377-740:64915] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc35989eb2c]
[fv-az1377-740:64915] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc35984527e]
[fv-az1377-740:64915] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc3598288ff]
[fv-az1377-740:64915] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc359ca5ff5]
[fv-az1377-740:64915] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc359cbb0da]
[fv-az1377-740:64915] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc359ca5a55]
[fv-az1377-740:64915] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc359ca5a6f]
[fv-az1377-740:64915] [ 8] plumed_master(+0x146dd)[0x555d00ad86dd]
[fv-az1377-740:64915] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc35982a1ca]
[fv-az1377-740:64915] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc35982a28b]
[fv-az1377-740:64915] [11] plumed_master(+0x15365)[0x555d00ad9365]
[fv-az1377-740:64915] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az1377-740 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
