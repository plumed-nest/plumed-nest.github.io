**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ccl-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:11965] *** Process received signal ***
[pkrvmq0rgcvqdmg:11965] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11965] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11965] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa93cc45330]
[pkrvmq0rgcvqdmg:11965] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa93cc9eb2c]
[pkrvmq0rgcvqdmg:11965] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa93cc4527e]
[pkrvmq0rgcvqdmg:11965] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa93cc288ff]
[pkrvmq0rgcvqdmg:11965] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa93d0a5ff5]
[pkrvmq0rgcvqdmg:11965] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa93d0bb0da]
[pkrvmq0rgcvqdmg:11965] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa93d0a5a55]
[pkrvmq0rgcvqdmg:11965] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa93d0a5a6f]
[pkrvmq0rgcvqdmg:11965] [ 8] plumed_master(+0x146dd)[0x561b5c32d6dd]
[pkrvmq0rgcvqdmg:11965] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa93cc2a1ca]
[pkrvmq0rgcvqdmg:11965] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa93cc2a28b]
[pkrvmq0rgcvqdmg:11965] [11] plumed_master(+0x15365)[0x561b5c32e365]
[pkrvmq0rgcvqdmg:11965] *** End of error message ***
</pre>
{% endraw %}
