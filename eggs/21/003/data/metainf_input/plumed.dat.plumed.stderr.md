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
[fv-az1374-933:11869] *** Process received signal ***
[fv-az1374-933:11869] Signal: Aborted (6)
[fv-az1374-933:11869] Signal code:  (-6)
[fv-az1374-933:11869] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feb78845330]
[fv-az1374-933:11869] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feb7889eb2c]
[fv-az1374-933:11869] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feb7884527e]
[fv-az1374-933:11869] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feb788288ff]
[fv-az1374-933:11869] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feb78ca5ff5]
[fv-az1374-933:11869] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feb78cbb0da]
[fv-az1374-933:11869] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feb78ca5a55]
[fv-az1374-933:11869] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feb78ca5a6f]
[fv-az1374-933:11869] [ 8] plumed(+0x146dd)[0x55938c9106dd]
[fv-az1374-933:11869] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feb7882a1ca]
[fv-az1374-933:11869] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feb7882a28b]
[fv-az1374-933:11869] [11] plumed(+0x15365)[0x55938c911365]
[fv-az1374-933:11869] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1374-933:11870] *** Process received signal ***
[fv-az1374-933:11870] Signal: Aborted (6)
[fv-az1374-933:11870] Signal code:  (-6)
[fv-az1374-933:11870] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb9cbc45330]
[fv-az1374-933:11870] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb9cbc9eb2c]
[fv-az1374-933:11870] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb9cbc4527e]
[fv-az1374-933:11870] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb9cbc288ff]
[fv-az1374-933:11870] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb9cc0a5ff5]
[fv-az1374-933:11870] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb9cc0bb0da]
[fv-az1374-933:11870] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb9cc0a5a55]
[fv-az1374-933:11870] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb9cc0a5a6f]
[fv-az1374-933:11870] [ 8] plumed(+0x146dd)[0x564aeabdb6dd]
[fv-az1374-933:11870] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb9cbc2a1ca]
[fv-az1374-933:11870] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb9cbc2a28b]
[fv-az1374-933:11870] [11] plumed(+0x15365)[0x564aeabdc365]
[fv-az1374-933:11870] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az1374-933 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
