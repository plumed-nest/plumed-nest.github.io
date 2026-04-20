**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[runnervmeorf1:07194] *** Process received signal ***
[runnervmeorf1:07194] Signal: Aborted (6)
[runnervmeorf1:07194] Signal code:  (-6)
[runnervmeorf1:07194] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f36fc845330]
[runnervmeorf1:07194] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f36fc89eb2c]
[runnervmeorf1:07194] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f36fc84527e]
[runnervmeorf1:07194] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36fc8288ff]
[runnervmeorf1:07194] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f36fcca5ff5]
[runnervmeorf1:07194] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f36fccbb0da]
[runnervmeorf1:07194] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f36fcca5a55]
[runnervmeorf1:07194] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f36fcca5a6f]
[runnervmeorf1:07194] [ 8] plumed_master(+0x146dd)[0x560d5f25c6dd]
[runnervmeorf1:07194] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f36fc82a1ca]
[runnervmeorf1:07194] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f36fc82a28b]
[runnervmeorf1:07194] [11] plumed_master(+0x15365)[0x560d5f25d365]
[runnervmeorf1:07194] *** End of error message ***
</pre>
{% endraw %}
