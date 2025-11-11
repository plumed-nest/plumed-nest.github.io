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
[runnervmw9dnm:06192] *** Process received signal ***
[runnervmw9dnm:06192] Signal: Aborted (6)
[runnervmw9dnm:06192] Signal code:  (-6)
[runnervmw9dnm:06192] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe541645330]
[runnervmw9dnm:06192] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe54169eb2c]
[runnervmw9dnm:06192] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe54164527e]
[runnervmw9dnm:06192] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5416288ff]
[runnervmw9dnm:06192] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe541aa5ff5]
[runnervmw9dnm:06192] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe541abb0da]
[runnervmw9dnm:06192] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe541aa5a55]
[runnervmw9dnm:06192] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe541aa5a6f]
[runnervmw9dnm:06192] [ 8] plumed_master(+0x146dd)[0x55d5a099c6dd]
[runnervmw9dnm:06192] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe54162a1ca]
[runnervmw9dnm:06192] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe54162a28b]
[runnervmw9dnm:06192] [11] plumed_master(+0x15365)[0x55d5a099d365]
[runnervmw9dnm:06192] *** End of error message ***
</pre>
{% endraw %}
