**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmq0rgcvqdmg:09012] *** Process received signal ***
[pkrvmq0rgcvqdmg:09012] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09012] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09012] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5c3d845330]
[pkrvmq0rgcvqdmg:09012] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5c3d89eb2c]
[pkrvmq0rgcvqdmg:09012] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5c3d84527e]
[pkrvmq0rgcvqdmg:09012] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5c3d8288ff]
[pkrvmq0rgcvqdmg:09012] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5c3dca5ff5]
[pkrvmq0rgcvqdmg:09012] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5c3dcbb0da]
[pkrvmq0rgcvqdmg:09012] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5c3dca5a55]
[pkrvmq0rgcvqdmg:09012] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5c3dca5a6f]
[pkrvmq0rgcvqdmg:09012] [ 8] plumed(+0x146dd)[0x5570ab96c6dd]
[pkrvmq0rgcvqdmg:09012] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5c3d82a1ca]
[pkrvmq0rgcvqdmg:09012] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5c3d82a28b]
[pkrvmq0rgcvqdmg:09012] [11] plumed(+0x15365)[0x5570ab96d365]
[pkrvmq0rgcvqdmg:09012] *** End of error message ***
</pre>
{% endraw %}
