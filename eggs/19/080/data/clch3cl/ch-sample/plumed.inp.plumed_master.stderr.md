**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:09528] *** Process received signal ***
[pkrvmxyh4eaekms:09528] Signal: Aborted (6)
[pkrvmxyh4eaekms:09528] Signal code:  (-6)
[pkrvmxyh4eaekms:09528] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f71c2445330]
[pkrvmxyh4eaekms:09528] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f71c249eb2c]
[pkrvmxyh4eaekms:09528] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f71c244527e]
[pkrvmxyh4eaekms:09528] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71c24288ff]
[pkrvmxyh4eaekms:09528] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f71c28a5ff5]
[pkrvmxyh4eaekms:09528] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f71c28bb0da]
[pkrvmxyh4eaekms:09528] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f71c28a5a55]
[pkrvmxyh4eaekms:09528] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f71c28a5a6f]
[pkrvmxyh4eaekms:09528] [ 8] plumed_master(+0x146dd)[0x558c8856e6dd]
[pkrvmxyh4eaekms:09528] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f71c242a1ca]
[pkrvmxyh4eaekms:09528] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f71c242a28b]
[pkrvmxyh4eaekms:09528] [11] plumed_master(+0x15365)[0x558c8856f365]
[pkrvmxyh4eaekms:09528] *** End of error message ***
</pre>
{% endraw %}
