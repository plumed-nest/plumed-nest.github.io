**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[runnervmvrwv9:05663] *** Process received signal ***
[runnervmvrwv9:05663] Signal: Aborted (6)
[runnervmvrwv9:05663] Signal code:  (-6)
[runnervmvrwv9:05663] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcbbfa45330]
[runnervmvrwv9:05663] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcbbfa9eb2c]
[runnervmvrwv9:05663] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcbbfa4527e]
[runnervmvrwv9:05663] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcbbfa288ff]
[runnervmvrwv9:05663] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcbbfea5ff5]
[runnervmvrwv9:05663] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcbbfebb0da]
[runnervmvrwv9:05663] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcbbfea5a55]
[runnervmvrwv9:05663] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcbbfea5a6f]
[runnervmvrwv9:05663] [ 8] plumed_master(+0x146dd)[0x5617c2a446dd]
[runnervmvrwv9:05663] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcbbfa2a1ca]
[runnervmvrwv9:05663] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcbbfa2a28b]
[runnervmvrwv9:05663] [11] plumed_master(+0x15365)[0x5617c2a45365]
[runnervmvrwv9:05663] *** End of error message ***
</pre>
{% endraw %}
