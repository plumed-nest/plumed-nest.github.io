**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  5FU/iMetaD_Input/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[pkrvmq0rgcvqdmg:06232] *** Process received signal ***
[pkrvmq0rgcvqdmg:06232] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06232] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06232] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3a4a645330]
[pkrvmq0rgcvqdmg:06232] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3a4a69eb2c]
[pkrvmq0rgcvqdmg:06232] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3a4a64527e]
[pkrvmq0rgcvqdmg:06232] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3a4a6288ff]
[pkrvmq0rgcvqdmg:06232] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3a4aaa5ff5]
[pkrvmq0rgcvqdmg:06232] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3a4aabb0da]
[pkrvmq0rgcvqdmg:06232] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3a4aaa5a55]
[pkrvmq0rgcvqdmg:06232] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3a4aaa5a6f]
[pkrvmq0rgcvqdmg:06232] [ 8] plumed_master(+0x146dd)[0x5638f7ae66dd]
[pkrvmq0rgcvqdmg:06232] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3a4a62a1ca]
[pkrvmq0rgcvqdmg:06232] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3a4a62a28b]
[pkrvmq0rgcvqdmg:06232] [11] plumed_master(+0x15365)[0x5638f7ae7365]
[pkrvmq0rgcvqdmg:06232] *** End of error message ***
</pre>
{% endraw %}
