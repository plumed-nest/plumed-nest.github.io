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
[runnervmeorf1:07312] *** Process received signal ***
[runnervmeorf1:07312] Signal: Aborted (6)
[runnervmeorf1:07312] Signal code:  (-6)
[runnervmeorf1:07312] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1b31845330]
[runnervmeorf1:07312] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1b3189eb2c]
[runnervmeorf1:07312] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1b3184527e]
[runnervmeorf1:07312] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1b318288ff]
[runnervmeorf1:07312] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1b31ca5ff5]
[runnervmeorf1:07312] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1b31cbb0da]
[runnervmeorf1:07312] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1b31ca5a55]
[runnervmeorf1:07312] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1b31ca5a6f]
[runnervmeorf1:07312] [ 8] plumed_master(+0x146dd)[0x55579ee726dd]
[runnervmeorf1:07312] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1b3182a1ca]
[runnervmeorf1:07312] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1b3182a28b]
[runnervmeorf1:07312] [11] plumed_master(+0x15365)[0x55579ee73365]
[runnervmeorf1:07312] *** End of error message ***
</pre>
{% endraw %}
