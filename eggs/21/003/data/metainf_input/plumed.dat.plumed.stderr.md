**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1657-925:10102] *** Process received signal ***
[fv-az1657-925:10102] Signal: Aborted (6)
[fv-az1657-925:10102] Signal code:  (-6)
[fv-az1657-925:10102] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8904645330]
[fv-az1657-925:10102] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f890469eb2c]
[fv-az1657-925:10102] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f890464527e]
[fv-az1657-925:10102] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f89046288ff]
[fv-az1657-925:10102] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8904aa5ff5]
[fv-az1657-925:10102] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8904abb0da]
[fv-az1657-925:10102] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8904aa5a55]
[fv-az1657-925:10102] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8904aa5a6f]
[fv-az1657-925:10102] [ 8] plumed(+0x146dd)[0x5569b64616dd]
[fv-az1657-925:10102] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f890462a1ca]
[fv-az1657-925:10102] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f890462a28b]
[fv-az1657-925:10102] [11] plumed(+0x15365)[0x5569b6462365]
[fv-az1657-925:10102] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1657-925:10101] *** Process received signal ***
[fv-az1657-925:10101] Signal: Aborted (6)
[fv-az1657-925:10101] Signal code:  (-6)
[fv-az1657-925:10101] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0ba6845330]
[fv-az1657-925:10101] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0ba689eb2c]
[fv-az1657-925:10101] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0ba684527e]
[fv-az1657-925:10101] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0ba68288ff]
[fv-az1657-925:10101] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0ba6ca5ff5]
[fv-az1657-925:10101] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0ba6cbb0da]
[fv-az1657-925:10101] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0ba6ca5a55]
[fv-az1657-925:10101] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0ba6ca5a6f]
[fv-az1657-925:10101] [ 8] plumed(+0x146dd)[0x55be8f1e66dd]
[fv-az1657-925:10101] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0ba682a1ca]
[fv-az1657-925:10101] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0ba682a28b]
[fv-az1657-925:10101] [11] plumed(+0x15365)[0x55be8f1e7365]
[fv-az1657-925:10101] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 1 with PID 0 on node fv-az1657-925 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
