**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmkj6or:11703] *** Process received signal ***
[runnervmkj6or:11703] Signal: Aborted (6)
[runnervmkj6or:11703] Signal code:  (-6)
[runnervmkj6or:11703] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0751e45330]
[runnervmkj6or:11703] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0751e9eb2c]
[runnervmkj6or:11703] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0751e4527e]
[runnervmkj6or:11703] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0751e288ff]
[runnervmkj6or:11703] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07522a5ff5]
[runnervmkj6or:11703] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07522bb0da]
[runnervmkj6or:11703] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07522a5a55]
[runnervmkj6or:11703] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07522a5a6f]
[runnervmkj6or:11703] [ 8] plumed_master(+0x146dd)[0x5586423aa6dd]
[runnervmkj6or:11703] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0751e2a1ca]
[runnervmkj6or:11703] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0751e2a28b]
[runnervmkj6or:11703] [11] plumed_master(+0x15365)[0x5586423ab365]
[runnervmkj6or:11703] *** End of error message ***
</pre>
{% endraw %}
