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
[fv-az1719-82:68221] *** Process received signal ***
[fv-az1719-82:68221] Signal: Aborted (6)
[fv-az1719-82:68221] Signal code:  (-6)
[fv-az1719-82:68221] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb771645330]
[fv-az1719-82:68221] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb77169eb2c]
[fv-az1719-82:68221] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb77164527e]
[fv-az1719-82:68221] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb7716288ff]
[fv-az1719-82:68221] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb771aa5ff5]
[fv-az1719-82:68221] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb771abb0da]
[fv-az1719-82:68221] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb771aa5a55]
[fv-az1719-82:68221] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb771aa5a6f]
[fv-az1719-82:68221] [ 8] plumed_master(+0x146dd)[0x55e2414bd6dd]
[fv-az1719-82:68221] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb77162a1ca]
[fv-az1719-82:68221] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb77162a28b]
[fv-az1719-82:68221] [11] plumed_master(+0x15365)[0x55e2414be365]
[fv-az1719-82:68221] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1719-82:68220] *** Process received signal ***
[fv-az1719-82:68220] Signal: Aborted (6)
[fv-az1719-82:68220] Signal code:  (-6)
[fv-az1719-82:68220] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f667a445330]
[fv-az1719-82:68220] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f667a49eb2c]
[fv-az1719-82:68220] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f667a44527e]
[fv-az1719-82:68220] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f667a4288ff]
[fv-az1719-82:68220] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f667a8a5ff5]
[fv-az1719-82:68220] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f667a8bb0da]
[fv-az1719-82:68220] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f667a8a5a55]
[fv-az1719-82:68220] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f667a8a5a6f]
[fv-az1719-82:68220] [ 8] plumed_master(+0x146dd)[0x5608dfd456dd]
[fv-az1719-82:68220] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f667a42a1ca]
[fv-az1719-82:68220] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f667a42a28b]
[fv-az1719-82:68220] [11] plumed_master(+0x15365)[0x5608dfd46365]
[fv-az1719-82:68220] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az1719-82 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
