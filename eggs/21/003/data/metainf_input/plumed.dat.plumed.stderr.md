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
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[runnervm76f27:10416] *** Process received signal ***
[runnervm76f27:10416] Signal: Aborted (6)
[runnervm76f27:10416] Signal code:  (-6)
[runnervm76f27:10417] *** Process received signal ***
[runnervm76f27:10417] Signal: Aborted (6)
[runnervm76f27:10417] Signal code:  (-6)
[runnervm76f27:10416] [ 0] [runnervm76f27:10417] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7eb2a45330]
[runnervm76f27:10416] [ 1] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd29b845330]
[runnervm76f27:10417] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7eb2a9ec0c]
[runnervm76f27:10416] [ 2] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd29b89ec0c]
[runnervm76f27:10417] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7eb2a4527e]
[runnervm76f27:10416] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7eb2a288ff]
[runnervm76f27:10416] [ 4] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd29b84527e]
[runnervm76f27:10417] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7eb2ea5ff5]
[runnervm76f27:10416] [ 5] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd29b8288ff]
[runnervm76f27:10417] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7eb2ebb0da]
[runnervm76f27:10416] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd29bca5ff5]
[runnervm76f27:10417] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7eb2ea5a55]
[runnervm76f27:10416] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7eb2ea5a6f]
[runnervm76f27:10416] [ 8] plumed(+0x146dd)[0x558bae4a06dd]
[runnervm76f27:10416] [ 9] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd29bcbb0da]
[runnervm76f27:10417] [ 6] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7eb2a2a1ca]
[runnervm76f27:10416] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7eb2a2a28b]
[runnervm76f27:10416] [11] plumed(+0x15365)[0x558bae4a1365]
[runnervm76f27:10416] *** End of error message ***
/lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd29bca5a55]
[runnervm76f27:10417] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd29bca5a6f]
[runnervm76f27:10417] [ 8] plumed(+0x146dd)[0x561d3bb746dd]
[runnervm76f27:10417] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd29b82a1ca]
[runnervm76f27:10417] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd29b82a28b]
[runnervm76f27:10417] [11] plumed(+0x15365)[0x561d3bb75365]
[runnervm76f27:10417] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node runnervm76f27 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
