**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmeorf1:08717] *** Process received signal ***
[runnervmeorf1:08717] Signal: Aborted (6)
[runnervmeorf1:08717] Signal code:  (-6)
[runnervmeorf1:08717] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2968845330]
[runnervmeorf1:08717] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f296889eb2c]
[runnervmeorf1:08717] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f296884527e]
[runnervmeorf1:08717] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f29688288ff]
[runnervmeorf1:08717] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2968ca5ff5]
[runnervmeorf1:08717] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2968cbb0da]
[runnervmeorf1:08717] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2968ca5a55]
[runnervmeorf1:08717] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2968ca5a6f]
[runnervmeorf1:08717] [ 8] plumed_master(+0x146dd)[0x560bb77936dd]
[runnervmeorf1:08717] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f296882a1ca]
[runnervmeorf1:08717] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f296882a28b]
[runnervmeorf1:08717] [11] plumed_master(+0x15365)[0x560bb7794365]
[runnervmeorf1:08717] *** End of error message ***
</pre>
{% endraw %}
