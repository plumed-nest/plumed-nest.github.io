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
[fv-az1781-652:65741] *** Process received signal ***
[fv-az1781-652:65741] Signal: Aborted (6)
[fv-az1781-652:65741] Signal code:  (-6)
[fv-az1781-652:65741] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa23445330]
[fv-az1781-652:65741] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa2349eb2c]
[fv-az1781-652:65741] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa2344527e]
[fv-az1781-652:65741] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa234288ff]
[fv-az1781-652:65741] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa238a5ff5]
[fv-az1781-652:65741] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa238bb0da]
[fv-az1781-652:65741] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa238a5a55]
[fv-az1781-652:65741] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa238a5a6f]
[fv-az1781-652:65741] [ 8] plumed_master(+0x146dd)[0x55b3561af6dd]
[fv-az1781-652:65741] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa2342a1ca]
[fv-az1781-652:65741] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa2342a28b]
[fv-az1781-652:65741] [11] plumed_master(+0x15365)[0x55b3561b0365]
[fv-az1781-652:65741] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1781-652:65740] *** Process received signal ***
[fv-az1781-652:65740] Signal: Aborted (6)
[fv-az1781-652:65740] Signal code:  (-6)
[fv-az1781-652:65740] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e69845330]
[fv-az1781-652:65740] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e6989eb2c]
[fv-az1781-652:65740] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e6984527e]
[fv-az1781-652:65740] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e698288ff]
[fv-az1781-652:65740] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e69ca5ff5]
[fv-az1781-652:65740] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e69cbb0da]
[fv-az1781-652:65740] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e69ca5a55]
[fv-az1781-652:65740] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e69ca5a6f]
[fv-az1781-652:65740] [ 8] plumed_master(+0x146dd)[0x55d95d6466dd]
[fv-az1781-652:65740] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e6982a1ca]
[fv-az1781-652:65740] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e6982a28b]
[fv-az1781-652:65740] [11] plumed_master(+0x15365)[0x55d95d647365]
[fv-az1781-652:65740] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az1781-652 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
