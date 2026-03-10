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
[runnervm0kj6c:09076] *** Process received signal ***
[runnervm0kj6c:09076] Signal: Aborted (6)
[runnervm0kj6c:09076] Signal code:  (-6)
[runnervm0kj6c:09076] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fac9ac45330]
[runnervm0kj6c:09076] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fac9ac9eb2c]
[runnervm0kj6c:09076] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fac9ac4527e]
[runnervm0kj6c:09076] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fac9ac288ff]
[runnervm0kj6c:09076] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fac9b0a5ff5]
[runnervm0kj6c:09076] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fac9b0bb0da]
[runnervm0kj6c:09076] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fac9b0a5a55]
[runnervm0kj6c:09076] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fac9b0a5a6f]
[runnervm0kj6c:09076] [ 8] plumed(+0x146dd)[0x55f870b476dd]
[runnervm0kj6c:09076] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fac9ac2a1ca]
[runnervm0kj6c:09076] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fac9ac2a28b]
[runnervm0kj6c:09076] [11] plumed(+0x15365)[0x55f870b48365]
[runnervm0kj6c:09076] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervm0kj6c:09075] *** Process received signal ***
[runnervm0kj6c:09075] Signal: Aborted (6)
[runnervm0kj6c:09075] Signal code:  (-6)
[runnervm0kj6c:09075] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e12445330]
[runnervm0kj6c:09075] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e1249eb2c]
[runnervm0kj6c:09075] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e1244527e]
[runnervm0kj6c:09075] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e124288ff]
[runnervm0kj6c:09075] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e128a5ff5]
[runnervm0kj6c:09075] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e128bb0da]
[runnervm0kj6c:09075] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e128a5a55]
[runnervm0kj6c:09075] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e128a5a6f]
[runnervm0kj6c:09075] [ 8] plumed(+0x146dd)[0x55c6060ad6dd]
[runnervm0kj6c:09075] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e1242a1ca]
[runnervm0kj6c:09075] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e1242a28b]
[runnervm0kj6c:09075] [11] plumed(+0x15365)[0x55c6060ae365]
[runnervm0kj6c:09075] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervm0kj6c exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
