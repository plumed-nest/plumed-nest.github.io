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
[pkrvmq0rgcvqdmg:12028] *** Process received signal ***
[pkrvmq0rgcvqdmg:12028] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12028] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12028] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3947445330]
[pkrvmq0rgcvqdmg:12028] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f394749eb2c]
[pkrvmq0rgcvqdmg:12028] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f394744527e]
[pkrvmq0rgcvqdmg:12028] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f39474288ff]
[pkrvmq0rgcvqdmg:12028] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f39478a5ff5]
[pkrvmq0rgcvqdmg:12028] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f39478bb0da]
[pkrvmq0rgcvqdmg:12028] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f39478a5a55]
[pkrvmq0rgcvqdmg:12028] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f39478a5a6f]
[pkrvmq0rgcvqdmg:12028] [ 8] plumed_master(+0x146dd)[0x55f5db1dc6dd]
[pkrvmq0rgcvqdmg:12028] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f394742a1ca]
[pkrvmq0rgcvqdmg:12028] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f394742a28b]
[pkrvmq0rgcvqdmg:12028] [11] plumed_master(+0x15365)[0x55f5db1dd365]
[pkrvmq0rgcvqdmg:12028] *** End of error message ***
</pre>
{% endraw %}
