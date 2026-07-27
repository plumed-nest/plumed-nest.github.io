**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervmvrwv9:09143] *** Process received signal ***
[runnervmvrwv9:09143] Signal: Aborted (6)
[runnervmvrwv9:09143] Signal code:  (-6)
[runnervmvrwv9:09143] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4dd1a45330]
[runnervmvrwv9:09143] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4dd1a9eb2c]
[runnervmvrwv9:09143] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4dd1a4527e]
[runnervmvrwv9:09143] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4dd1a288ff]
[runnervmvrwv9:09143] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4dd1ea5ff5]
[runnervmvrwv9:09143] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4dd1ebb0da]
[runnervmvrwv9:09143] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4dd1ea5a55]
[runnervmvrwv9:09143] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4dd1ea5a6f]
[runnervmvrwv9:09143] [ 8] plumed(+0x146dd)[0x5625490ab6dd]
[runnervmvrwv9:09143] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4dd1a2a1ca]
[runnervmvrwv9:09143] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4dd1a2a28b]
[runnervmvrwv9:09143] [11] plumed(+0x15365)[0x5625490ac365]
[runnervmvrwv9:09143] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervmvrwv9:09142] *** Process received signal ***
[runnervmvrwv9:09142] Signal: Aborted (6)
[runnervmvrwv9:09142] Signal code:  (-6)
[runnervmvrwv9:09142] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4dde245330]
[runnervmvrwv9:09142] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4dde29eb2c]
[runnervmvrwv9:09142] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4dde24527e]
[runnervmvrwv9:09142] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4dde2288ff]
[runnervmvrwv9:09142] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4dde6a5ff5]
[runnervmvrwv9:09142] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4dde6bb0da]
[runnervmvrwv9:09142] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4dde6a5a55]
[runnervmvrwv9:09142] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4dde6a5a6f]
[runnervmvrwv9:09142] [ 8] plumed(+0x146dd)[0x55c5cfea96dd]
[runnervmvrwv9:09142] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4dde22a1ca]
[runnervmvrwv9:09142] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4dde22a28b]
[runnervmvrwv9:09142] [11] plumed(+0x15365)[0x55c5cfeaa365]
[runnervmvrwv9:09142] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervmvrwv9 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
