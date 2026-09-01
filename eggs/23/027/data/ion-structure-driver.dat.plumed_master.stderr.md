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
[runnervmgx7h7:07047] *** Process received signal ***
[runnervmgx7h7:07047] Signal: Aborted (6)
[runnervmgx7h7:07047] Signal code:  (-6)
[runnervmgx7h7:07047] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9948645330]
[runnervmgx7h7:07047] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f994869ec0c]
[runnervmgx7h7:07047] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f994864527e]
[runnervmgx7h7:07047] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f99486288ff]
[runnervmgx7h7:07047] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9948aa5ff5]
[runnervmgx7h7:07047] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9948abb0da]
[runnervmgx7h7:07047] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9948aa5a55]
[runnervmgx7h7:07047] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9948aa5a6f]
[runnervmgx7h7:07047] [ 8] plumed_master(+0x146dd)[0x5627e4c646dd]
[runnervmgx7h7:07047] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f994862a1ca]
[runnervmgx7h7:07047] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f994862a28b]
[runnervmgx7h7:07047] [11] plumed_master(+0x15365)[0x5627e4c65365]
[runnervmgx7h7:07047] *** End of error message ***
</pre>
{% endraw %}
