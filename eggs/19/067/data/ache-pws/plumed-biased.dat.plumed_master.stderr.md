**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmmklqx:10891] *** Process received signal ***
[runnervmmklqx:10891] Signal: Aborted (6)
[runnervmmklqx:10891] Signal code:  (-6)
[runnervmmklqx:10891] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faee8245330]
[runnervmmklqx:10891] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faee829eb2c]
[runnervmmklqx:10891] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faee824527e]
[runnervmmklqx:10891] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faee82288ff]
[runnervmmklqx:10891] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faee86a5ff5]
[runnervmmklqx:10891] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faee86bb0da]
[runnervmmklqx:10891] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faee86a5a55]
[runnervmmklqx:10891] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faee86a5a6f]
[runnervmmklqx:10891] [ 8] plumed_master(+0x146dd)[0x55814d3a56dd]
[runnervmmklqx:10891] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faee822a1ca]
[runnervmmklqx:10891] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faee822a28b]
[runnervmmklqx:10891] [11] plumed_master(+0x15365)[0x55814d3a6365]
[runnervmmklqx:10891] *** End of error message ***
</pre>
{% endraw %}
