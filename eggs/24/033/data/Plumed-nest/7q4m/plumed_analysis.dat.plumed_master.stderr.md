**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @252 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[pkrvmxyh4eaekms:05956] *** Process received signal ***
[pkrvmxyh4eaekms:05956] Signal: Aborted (6)
[pkrvmxyh4eaekms:05956] Signal code:  (-6)
[pkrvmxyh4eaekms:05956] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc6c6c45330]
[pkrvmxyh4eaekms:05956] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc6c6c9eb2c]
[pkrvmxyh4eaekms:05956] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc6c6c4527e]
[pkrvmxyh4eaekms:05956] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6c6c288ff]
[pkrvmxyh4eaekms:05956] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6c70a5ff5]
[pkrvmxyh4eaekms:05956] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6c70bb0da]
[pkrvmxyh4eaekms:05956] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6c70a5a55]
[pkrvmxyh4eaekms:05956] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6c70a5a6f]
[pkrvmxyh4eaekms:05956] [ 8] plumed_master(+0x146dd)[0x563c549376dd]
[pkrvmxyh4eaekms:05956] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc6c6c2a1ca]
[pkrvmxyh4eaekms:05956] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc6c6c2a28b]
[pkrvmxyh4eaekms:05956] [11] plumed_master(+0x15365)[0x563c54938365]
[pkrvmxyh4eaekms:05956] *** End of error message ***
</pre>
{% endraw %}
