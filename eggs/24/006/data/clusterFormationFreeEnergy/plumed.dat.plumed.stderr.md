**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[runnervmmklqx:06169] *** Process received signal ***
[runnervmmklqx:06169] Signal: Aborted (6)
[runnervmmklqx:06169] Signal code:  (-6)
[runnervmmklqx:06169] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3bc2245330]
[runnervmmklqx:06169] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3bc229eb2c]
[runnervmmklqx:06169] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3bc224527e]
[runnervmmklqx:06169] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3bc22288ff]
[runnervmmklqx:06169] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3bc26a5ff5]
[runnervmmklqx:06169] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3bc26bb0da]
[runnervmmklqx:06169] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3bc26a5a55]
[runnervmmklqx:06169] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3bc26a5a6f]
[runnervmmklqx:06169] [ 8] plumed(+0x146dd)[0x55de0bd626dd]
[runnervmmklqx:06169] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3bc222a1ca]
[runnervmmklqx:06169] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3bc222a28b]
[runnervmmklqx:06169] [11] plumed(+0x15365)[0x55de0bd63365]
[runnervmmklqx:06169] *** End of error message ***
</pre>
{% endraw %}
