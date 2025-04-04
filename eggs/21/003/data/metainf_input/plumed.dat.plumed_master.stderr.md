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
[fv-az1360-658:10529] *** Process received signal ***
[fv-az1360-658:10529] Signal: Aborted (6)
[fv-az1360-658:10529] Signal code:  (-6)
[fv-az1360-658:10529] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f114a245330]
[fv-az1360-658:10529] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f114a29eb2c]
[fv-az1360-658:10529] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f114a24527e]
[fv-az1360-658:10529] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f114a2288ff]
[fv-az1360-658:10529] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f114a6a5ff5]
[fv-az1360-658:10529] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f114a6bb0da]
[fv-az1360-658:10529] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f114a6a5a55]
[fv-az1360-658:10529] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f114a6a5a6f]
[fv-az1360-658:10529] [ 8] plumed_master(+0x146dd)[0x55b33f0586dd]
[fv-az1360-658:10529] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f114a22a1ca]
[fv-az1360-658:10529] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f114a22a28b]
[fv-az1360-658:10529] [11] plumed_master(+0x15365)[0x55b33f059365]
[fv-az1360-658:10529] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1360-658:10528] *** Process received signal ***
[fv-az1360-658:10528] Signal: Aborted (6)
[fv-az1360-658:10528] Signal code:  (-6)
[fv-az1360-658:10528] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2391645330]
[fv-az1360-658:10528] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f239169eb2c]
[fv-az1360-658:10528] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f239164527e]
[fv-az1360-658:10528] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23916288ff]
[fv-az1360-658:10528] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2391aa5ff5]
[fv-az1360-658:10528] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2391abb0da]
[fv-az1360-658:10528] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2391aa5a55]
[fv-az1360-658:10528] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2391aa5a6f]
[fv-az1360-658:10528] [ 8] plumed_master(+0x146dd)[0x5573499f06dd]
[fv-az1360-658:10528] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f239162a1ca]
[fv-az1360-658:10528] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f239162a28b]
[fv-az1360-658:10528] [11] plumed_master(+0x15365)[0x5573499f1365]
[fv-az1360-658:10528] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az1360-658 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
