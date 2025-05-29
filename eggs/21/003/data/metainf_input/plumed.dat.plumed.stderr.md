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
[pkrvmf6wy0o8zjz:66206] *** Process received signal ***
[pkrvmf6wy0o8zjz:66206] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:66206] Signal code:  (-6)
[pkrvmf6wy0o8zjz:66206] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdfa0c45330]
[pkrvmf6wy0o8zjz:66206] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdfa0c9eb2c]
[pkrvmf6wy0o8zjz:66206] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdfa0c4527e]
[pkrvmf6wy0o8zjz:66206] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdfa0c288ff]
[pkrvmf6wy0o8zjz:66206] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdfa10a5ff5]
[pkrvmf6wy0o8zjz:66206] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdfa10bb0da]
[pkrvmf6wy0o8zjz:66206] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdfa10a5a55]
[pkrvmf6wy0o8zjz:66206] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdfa10a5a6f]
[pkrvmf6wy0o8zjz:66206] [ 8] plumed(+0x146dd)[0x5625166cf6dd]
[pkrvmf6wy0o8zjz:66206] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdfa0c2a1ca]
[pkrvmf6wy0o8zjz:66206] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdfa0c2a28b]
[pkrvmf6wy0o8zjz:66206] [11] plumed(+0x15365)[0x5625166d0365]
[pkrvmf6wy0o8zjz:66206] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmf6wy0o8zjz:66205] *** Process received signal ***
[pkrvmf6wy0o8zjz:66205] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:66205] Signal code:  (-6)
[pkrvmf6wy0o8zjz:66205] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcd48845330]
[pkrvmf6wy0o8zjz:66205] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcd4889eb2c]
[pkrvmf6wy0o8zjz:66205] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcd4884527e]
[pkrvmf6wy0o8zjz:66205] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcd488288ff]
[pkrvmf6wy0o8zjz:66205] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcd48ca5ff5]
[pkrvmf6wy0o8zjz:66205] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcd48cbb0da]
[pkrvmf6wy0o8zjz:66205] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcd48ca5a55]
[pkrvmf6wy0o8zjz:66205] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcd48ca5a6f]
[pkrvmf6wy0o8zjz:66205] [ 8] plumed(+0x146dd)[0x55b1b4ac36dd]
[pkrvmf6wy0o8zjz:66205] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcd4882a1ca]
[pkrvmf6wy0o8zjz:66205] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcd4882a28b]
[pkrvmf6wy0o8zjz:66205] [11] plumed(+0x15365)[0x55b1b4ac4365]
[pkrvmf6wy0o8zjz:66205] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node pkrvmf6wy0o8zjz exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
