**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmmklqx:05206] *** Process received signal ***
[runnervmmklqx:05206] Signal: Aborted (6)
[runnervmmklqx:05206] Signal code:  (-6)
[runnervmmklqx:05206] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0d21045330]
[runnervmmklqx:05206] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0d2109eb2c]
[runnervmmklqx:05206] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0d2104527e]
[runnervmmklqx:05206] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0d210288ff]
[runnervmmklqx:05206] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0d214a5ff5]
[runnervmmklqx:05206] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0d214bb0da]
[runnervmmklqx:05206] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0d214a5a55]
[runnervmmklqx:05206] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0d214a5a6f]
[runnervmmklqx:05206] [ 8] plumed(+0x146dd)[0x555a11eab6dd]
[runnervmmklqx:05206] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0d2102a1ca]
[runnervmmklqx:05206] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0d2102a28b]
[runnervmmklqx:05206] [11] plumed(+0x15365)[0x555a11eac365]
[runnervmmklqx:05206] *** End of error message ***
</pre>
{% endraw %}
