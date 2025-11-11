**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/clusters.plmd   
Download: [zipped raw stdout](clusters.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](clusters.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0 : keyword ARG is compulsory for this action
[runnervmw9dnm:11117] *** Process received signal ***
[runnervmw9dnm:11117] Signal: Aborted (6)
[runnervmw9dnm:11117] Signal code:  (-6)
[runnervmw9dnm:11117] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5dade45330]
[runnervmw9dnm:11117] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5dade9eb2c]
[runnervmw9dnm:11117] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5dade4527e]
[runnervmw9dnm:11117] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5dade288ff]
[runnervmw9dnm:11117] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5dae2a5ff5]
[runnervmw9dnm:11117] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5dae2bb0da]
[runnervmw9dnm:11117] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5dae2a5a55]
[runnervmw9dnm:11117] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5dae2a5a6f]
[runnervmw9dnm:11117] [ 8] plumed_master(+0x146dd)[0x55b7eaa156dd]
[runnervmw9dnm:11117] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5dade2a1ca]
[runnervmw9dnm:11117] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5dade2a28b]
[runnervmw9dnm:11117] [11] plumed_master(+0x15365)[0x55b7eaa16365]
[runnervmw9dnm:11117] *** End of error message ***
</pre>
{% endraw %}
