**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmq0rgcvqdmg:08588] *** Process received signal ***
[pkrvmq0rgcvqdmg:08588] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08588] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08588] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff666045330]
[pkrvmq0rgcvqdmg:08588] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff66609eb2c]
[pkrvmq0rgcvqdmg:08588] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff66604527e]
[pkrvmq0rgcvqdmg:08588] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff6660288ff]
[pkrvmq0rgcvqdmg:08588] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff6664a5ff5]
[pkrvmq0rgcvqdmg:08588] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff6664bb0da]
[pkrvmq0rgcvqdmg:08588] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff6664a5a55]
[pkrvmq0rgcvqdmg:08588] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff6664a5a6f]
[pkrvmq0rgcvqdmg:08588] [ 8] plumed(+0x146dd)[0x55d9c422e6dd]
[pkrvmq0rgcvqdmg:08588] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff66602a1ca]
[pkrvmq0rgcvqdmg:08588] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff66602a28b]
[pkrvmq0rgcvqdmg:08588] [11] plumed(+0x15365)[0x55d9c422f365]
[pkrvmq0rgcvqdmg:08588] *** End of error message ***
</pre>
{% endraw %}
