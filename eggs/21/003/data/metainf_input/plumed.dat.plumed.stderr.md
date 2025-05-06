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
[fv-az1781-652:65706] *** Process received signal ***
[fv-az1781-652:65706] Signal: Aborted (6)
[fv-az1781-652:65706] Signal code:  (-6)
[fv-az1781-652:65706] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6854245330]
[fv-az1781-652:65706] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f685429eb2c]
[fv-az1781-652:65706] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f685424527e]
[fv-az1781-652:65706] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68542288ff]
[fv-az1781-652:65706] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68546a5ff5]
[fv-az1781-652:65706] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68546bb0da]
[fv-az1781-652:65706] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68546a5a55]
[fv-az1781-652:65706] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68546a5a6f]
[fv-az1781-652:65706] [ 8] plumed(+0x146dd)[0x5626c89026dd]
[fv-az1781-652:65706] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f685422a1ca]
[fv-az1781-652:65706] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f685422a28b]
[fv-az1781-652:65706] [11] plumed(+0x15365)[0x5626c8903365]
[fv-az1781-652:65706] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1781-652:65707] *** Process received signal ***
[fv-az1781-652:65707] Signal: Aborted (6)
[fv-az1781-652:65707] Signal code:  (-6)
[fv-az1781-652:65707] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf10245330]
[fv-az1781-652:65707] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf1029eb2c]
[fv-az1781-652:65707] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf1024527e]
[fv-az1781-652:65707] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf102288ff]
[fv-az1781-652:65707] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf106a5ff5]
[fv-az1781-652:65707] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf106bb0da]
[fv-az1781-652:65707] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf106a5a55]
[fv-az1781-652:65707] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf106a5a6f]
[fv-az1781-652:65707] [ 8] plumed(+0x146dd)[0x56412ae6f6dd]
[fv-az1781-652:65707] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf1022a1ca]
[fv-az1781-652:65707] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf1022a28b]
[fv-az1781-652:65707] [11] plumed(+0x15365)[0x56412ae70365]
[fv-az1781-652:65707] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az1781-652 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
