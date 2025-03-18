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
[fv-az1377-740:64877] *** Process received signal ***
[fv-az1377-740:64877] Signal: Aborted (6)
[fv-az1377-740:64877] Signal code:  (-6)
[fv-az1377-740:64877] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6262045330]
[fv-az1377-740:64877] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f626209eb2c]
[fv-az1377-740:64877] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f626204527e]
[fv-az1377-740:64877] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62620288ff]
[fv-az1377-740:64877] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62624a5ff5]
[fv-az1377-740:64877] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62624bb0da]
[fv-az1377-740:64877] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62624a5a55]
[fv-az1377-740:64877] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62624a5a6f]
[fv-az1377-740:64877] [ 8] plumed(+0x146dd)[0x5607fe3d96dd]
[fv-az1377-740:64877] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f626202a1ca]
[fv-az1377-740:64877] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f626202a28b]
[fv-az1377-740:64877] [11] plumed(+0x15365)[0x5607fe3da365]
[fv-az1377-740:64877] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1377-740:64876] *** Process received signal ***
[fv-az1377-740:64876] Signal: Aborted (6)
[fv-az1377-740:64876] Signal code:  (-6)
[fv-az1377-740:64876] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f17a1245330]
[fv-az1377-740:64876] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f17a129eb2c]
[fv-az1377-740:64876] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f17a124527e]
[fv-az1377-740:64876] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f17a12288ff]
[fv-az1377-740:64876] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f17a16a5ff5]
[fv-az1377-740:64876] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f17a16bb0da]
[fv-az1377-740:64876] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f17a16a5a55]
[fv-az1377-740:64876] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f17a16a5a6f]
[fv-az1377-740:64876] [ 8] plumed(+0x146dd)[0x56138f7bc6dd]
[fv-az1377-740:64876] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f17a122a1ca]
[fv-az1377-740:64876] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f17a122a28b]
[fv-az1377-740:64876] [11] plumed(+0x15365)[0x56138f7bd365]
[fv-az1377-740:64876] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az1377-740 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
