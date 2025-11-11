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
[runnervmw9dnm:07864] *** Process received signal ***
[runnervmw9dnm:07864] Signal: Aborted (6)
[runnervmw9dnm:07864] Signal code:  (-6)
[runnervmw9dnm:07864] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb31d445330]
[runnervmw9dnm:07864] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb31d49eb2c]
[runnervmw9dnm:07864] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb31d44527e]
[runnervmw9dnm:07864] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb31d4288ff]
[runnervmw9dnm:07864] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb31d8a5ff5]
[runnervmw9dnm:07864] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb31d8bb0da]
[runnervmw9dnm:07864] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb31d8a5a55]
[runnervmw9dnm:07864] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb31d8a5a6f]
[runnervmw9dnm:07864] [ 8] plumed_master(+0x146dd)[0x56011e6526dd]
[runnervmw9dnm:07864] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb31d42a1ca]
[runnervmw9dnm:07864] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb31d42a28b]
[runnervmw9dnm:07864] [11] plumed_master(+0x15365)[0x56011e653365]
[runnervmw9dnm:07864] *** End of error message ***
</pre>
{% endraw %}
