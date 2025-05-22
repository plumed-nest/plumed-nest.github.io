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
[pkrvmf6wy0o8zjz:38780] *** Process received signal ***
[pkrvmf6wy0o8zjz:38780] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38780] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38780] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8eaf445330]
[pkrvmf6wy0o8zjz:38780] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8eaf49eb2c]
[pkrvmf6wy0o8zjz:38780] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8eaf44527e]
[pkrvmf6wy0o8zjz:38780] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8eaf4288ff]
[pkrvmf6wy0o8zjz:38780] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8eaf8a5ff5]
[pkrvmf6wy0o8zjz:38780] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8eaf8bb0da]
[pkrvmf6wy0o8zjz:38780] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8eaf8a5a55]
[pkrvmf6wy0o8zjz:38780] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8eaf8a5a6f]
[pkrvmf6wy0o8zjz:38780] [ 8] plumed_master(+0x146dd)[0x560e0dc536dd]
[pkrvmf6wy0o8zjz:38780] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8eaf42a1ca]
[pkrvmf6wy0o8zjz:38780] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8eaf42a28b]
[pkrvmf6wy0o8zjz:38780] [11] plumed_master(+0x15365)[0x560e0dc54365]
[pkrvmf6wy0o8zjz:38780] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvmf6wy0o8zjz:38781] *** Process received signal ***
[pkrvmf6wy0o8zjz:38781] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38781] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38781] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0bf5c45330]
[pkrvmf6wy0o8zjz:38781] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0bf5c9eb2c]
[pkrvmf6wy0o8zjz:38781] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0bf5c4527e]
[pkrvmf6wy0o8zjz:38781] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0bf5c288ff]
[pkrvmf6wy0o8zjz:38781] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0bf60a5ff5]
[pkrvmf6wy0o8zjz:38781] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0bf60bb0da]
[pkrvmf6wy0o8zjz:38781] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0bf60a5a55]
[pkrvmf6wy0o8zjz:38781] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0bf60a5a6f]
[pkrvmf6wy0o8zjz:38781] [ 8] plumed_master(+0x146dd)[0x55ca258ce6dd]
[pkrvmf6wy0o8zjz:38781] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0bf5c2a1ca]
[pkrvmf6wy0o8zjz:38781] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0bf5c2a28b]
[pkrvmf6wy0o8zjz:38781] [11] plumed_master(+0x15365)[0x55ca258cf365]
[pkrvmf6wy0o8zjz:38781] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvmf6wy0o8zjz exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
