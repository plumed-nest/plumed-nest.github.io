**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmmklqx:05222] *** Process received signal ***
[runnervmmklqx:05222] Signal: Aborted (6)
[runnervmmklqx:05222] Signal code:  (-6)
[runnervmmklqx:05222] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa7c7245330]
[runnervmmklqx:05222] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa7c729eb2c]
[runnervmmklqx:05222] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa7c724527e]
[runnervmmklqx:05222] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa7c72288ff]
[runnervmmklqx:05222] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa7c76a5ff5]
[runnervmmklqx:05222] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa7c76bb0da]
[runnervmmklqx:05222] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa7c76a5a55]
[runnervmmklqx:05222] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa7c76a5a6f]
[runnervmmklqx:05222] [ 8] plumed_master(+0x146dd)[0x556e2d1186dd]
[runnervmmklqx:05222] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa7c722a1ca]
[runnervmmklqx:05222] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa7c722a28b]
[runnervmmklqx:05222] [11] plumed_master(+0x15365)[0x556e2d119365]
[runnervmmklqx:05222] *** End of error message ***
</pre>
{% endraw %}
