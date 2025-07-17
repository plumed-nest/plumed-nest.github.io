**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s43 : missing SWITCH11 keyword
[pkrvmq0rgcvqdmg:11754] *** Process received signal ***
[pkrvmq0rgcvqdmg:11754] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11754] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11754] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe4a9045330]
[pkrvmq0rgcvqdmg:11754] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe4a909eb2c]
[pkrvmq0rgcvqdmg:11754] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe4a904527e]
[pkrvmq0rgcvqdmg:11754] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe4a90288ff]
[pkrvmq0rgcvqdmg:11754] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe4a94a5ff5]
[pkrvmq0rgcvqdmg:11754] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe4a94bb0da]
[pkrvmq0rgcvqdmg:11754] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe4a94a5a55]
[pkrvmq0rgcvqdmg:11754] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe4a94a5a6f]
[pkrvmq0rgcvqdmg:11754] [ 8] plumed_master(+0x146dd)[0x561a892476dd]
[pkrvmq0rgcvqdmg:11754] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe4a902a1ca]
[pkrvmq0rgcvqdmg:11754] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe4a902a28b]
[pkrvmq0rgcvqdmg:11754] [11] plumed_master(+0x15365)[0x561a89248365]
[pkrvmq0rgcvqdmg:11754] *** End of error message ***
</pre>
{% endraw %}
