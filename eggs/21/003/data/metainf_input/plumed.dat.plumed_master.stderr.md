**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervm76f27:10451] *** Process received signal ***
[runnervm76f27:10451] Signal: Aborted (6)
[runnervm76f27:10451] Signal code:  (-6)
[runnervm76f27:10451] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b63245330]
[runnervm76f27:10451] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b6329ec0c]
[runnervm76f27:10451] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b6324527e]
[runnervm76f27:10451] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b632288ff]
[runnervm76f27:10451] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b636a5ff5]
[runnervm76f27:10451] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b636bb0da]
[runnervm76f27:10451] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b636a5a55]
[runnervm76f27:10451] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b636a5a6f]
[runnervm76f27:10451] [ 8] plumed_master(+0x146dd)[0x556bf9fc06dd]
[runnervm76f27:10451] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b6322a1ca]
[runnervm76f27:10451] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b6322a28b]
[runnervm76f27:10451] [11] plumed_master(+0x15365)[0x556bf9fc1365]
[runnervm76f27:10451] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervm76f27:10450] *** Process received signal ***
[runnervm76f27:10450] Signal: Aborted (6)
[runnervm76f27:10450] Signal code:  (-6)
[runnervm76f27:10450] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2bccc45330]
[runnervm76f27:10450] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2bccc9ec0c]
[runnervm76f27:10450] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2bccc4527e]
[runnervm76f27:10450] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2bccc288ff]
[runnervm76f27:10450] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2bcd0a5ff5]
[runnervm76f27:10450] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2bcd0bb0da]
[runnervm76f27:10450] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2bcd0a5a55]
[runnervm76f27:10450] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2bcd0a5a6f]
[runnervm76f27:10450] [ 8] plumed_master(+0x146dd)[0x558ca1cfc6dd]
[runnervm76f27:10450] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2bccc2a1ca]
[runnervm76f27:10450] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2bccc2a28b]
[runnervm76f27:10450] [11] plumed_master(+0x15365)[0x558ca1cfd365]
[runnervm76f27:10450] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node runnervm76f27 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
