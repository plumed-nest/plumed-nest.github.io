**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvm7jw40e0xgp:10765] *** Process received signal ***
[pkrvm7jw40e0xgp:10765] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10765] Signal code:  (-6)
[pkrvm7jw40e0xgp:10765] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fba24045330]
[pkrvm7jw40e0xgp:10765] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fba2409eb2c]
[pkrvm7jw40e0xgp:10765] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fba2404527e]
[pkrvm7jw40e0xgp:10765] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fba240288ff]
[pkrvm7jw40e0xgp:10765] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fba244a5ff5]
[pkrvm7jw40e0xgp:10765] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fba244bb0da]
[pkrvm7jw40e0xgp:10765] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fba244a5a55]
[pkrvm7jw40e0xgp:10765] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fba244a5a6f]
[pkrvm7jw40e0xgp:10765] [ 8] plumed_master(+0x146dd)[0x55a0860006dd]
[pkrvm7jw40e0xgp:10765] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fba2402a1ca]
[pkrvm7jw40e0xgp:10765] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fba2402a28b]
[pkrvm7jw40e0xgp:10765] [11] plumed_master(+0x15365)[0x55a086001365]
[pkrvm7jw40e0xgp:10765] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[pkrvm7jw40e0xgp:10766] *** Process received signal ***
[pkrvm7jw40e0xgp:10766] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10766] Signal code:  (-6)
[pkrvm7jw40e0xgp:10766] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff8f0845330]
[pkrvm7jw40e0xgp:10766] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff8f089eb2c]
[pkrvm7jw40e0xgp:10766] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff8f084527e]
[pkrvm7jw40e0xgp:10766] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff8f08288ff]
[pkrvm7jw40e0xgp:10766] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff8f0ca5ff5]
[pkrvm7jw40e0xgp:10766] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff8f0cbb0da]
[pkrvm7jw40e0xgp:10766] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff8f0ca5a55]
[pkrvm7jw40e0xgp:10766] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff8f0ca5a6f]
[pkrvm7jw40e0xgp:10766] [ 8] plumed_master(+0x146dd)[0x563eaf3ad6dd]
[pkrvm7jw40e0xgp:10766] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff8f082a1ca]
[pkrvm7jw40e0xgp:10766] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff8f082a28b]
[pkrvm7jw40e0xgp:10766] [11] plumed_master(+0x15365)[0x563eaf3ae365]
[pkrvm7jw40e0xgp:10766] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node pkrvm7jw40e0xgp exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
