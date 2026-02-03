**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[runnervmkj6or:05200] *** Process received signal ***
[runnervmkj6or:05200] Signal: Aborted (6)
[runnervmkj6or:05200] Signal code:  (-6)
[runnervmkj6or:05200] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0ca0045330]
[runnervmkj6or:05200] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0ca009eb2c]
[runnervmkj6or:05200] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0ca004527e]
[runnervmkj6or:05200] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0ca00288ff]
[runnervmkj6or:05200] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0ca04a5ff5]
[runnervmkj6or:05200] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0ca04bb0da]
[runnervmkj6or:05200] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0ca04a5a55]
[runnervmkj6or:05200] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0ca04a5a6f]
[runnervmkj6or:05200] [ 8] plumed_master(+0x146dd)[0x558f290056dd]
[runnervmkj6or:05200] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0ca002a1ca]
[runnervmkj6or:05200] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0ca002a28b]
[runnervmkj6or:05200] [11] plumed_master(+0x15365)[0x558f29006365]
[runnervmkj6or:05200] *** End of error message ***
</pre>
{% endraw %}
