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
[runnervmi13qx:40104] *** Process received signal ***
[runnervmi13qx:40104] Signal: Aborted (6)
[runnervmi13qx:40104] Signal code:  (-6)
[runnervmi13qx:40104] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f494b245330]
[runnervmi13qx:40104] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f494b29eb2c]
[runnervmi13qx:40104] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f494b24527e]
[runnervmi13qx:40104] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f494b2288ff]
[runnervmi13qx:40104] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f494b6a5ff5]
[runnervmi13qx:40104] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f494b6bb0da]
[runnervmi13qx:40104] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f494b6a5a55]
[runnervmi13qx:40104] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f494b6a5a6f]
[runnervmi13qx:40104] [ 8] plumed(+0x146dd)[0x55a3fa6ee6dd]
[runnervmi13qx:40104] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f494b22a1ca]
[runnervmi13qx:40104] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f494b22a28b]
[runnervmi13qx:40104] [11] plumed(+0x15365)[0x55a3fa6ef365]
[runnervmi13qx:40104] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervmi13qx:40103] *** Process received signal ***
[runnervmi13qx:40103] Signal: Aborted (6)
[runnervmi13qx:40103] Signal code:  (-6)
[runnervmi13qx:40103] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b04045330]
[runnervmi13qx:40103] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b0409eb2c]
[runnervmi13qx:40103] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b0404527e]
[runnervmi13qx:40103] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b040288ff]
[runnervmi13qx:40103] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b044a5ff5]
[runnervmi13qx:40103] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b044bb0da]
[runnervmi13qx:40103] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b044a5a55]
[runnervmi13qx:40103] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b044a5a6f]
[runnervmi13qx:40103] [ 8] plumed(+0x146dd)[0x564a6567a6dd]
[runnervmi13qx:40103] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b0402a1ca]
[runnervmi13qx:40103] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b0402a28b]
[runnervmi13qx:40103] [11] plumed(+0x15365)[0x564a6567b365]
[runnervmi13qx:40103] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervmi13qx exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
