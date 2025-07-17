**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmq0rgcvqdmg:06957] *** Process received signal ***
[pkrvmq0rgcvqdmg:06957] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06957] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06957] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffb3da45330]
[pkrvmq0rgcvqdmg:06957] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffb3da9eb2c]
[pkrvmq0rgcvqdmg:06957] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffb3da4527e]
[pkrvmq0rgcvqdmg:06957] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffb3da288ff]
[pkrvmq0rgcvqdmg:06957] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffb3dea5ff5]
[pkrvmq0rgcvqdmg:06957] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffb3debb0da]
[pkrvmq0rgcvqdmg:06957] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffb3dea5a55]
[pkrvmq0rgcvqdmg:06957] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffb3dea5a6f]
[pkrvmq0rgcvqdmg:06957] [ 8] plumed_master(+0x146dd)[0x55fe0cd306dd]
[pkrvmq0rgcvqdmg:06957] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffb3da2a1ca]
[pkrvmq0rgcvqdmg:06957] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffb3da2a28b]
[pkrvmq0rgcvqdmg:06957] [11] plumed_master(+0x15365)[0x55fe0cd31365]
[pkrvmq0rgcvqdmg:06957] *** End of error message ***
</pre>
{% endraw %}
