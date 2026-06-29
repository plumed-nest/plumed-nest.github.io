**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmmklqx:05273] *** Process received signal ***
[runnervmmklqx:05273] Signal: Aborted (6)
[runnervmmklqx:05273] Signal code:  (-6)
[runnervmmklqx:05273] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f799a645330]
[runnervmmklqx:05273] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f799a69eb2c]
[runnervmmklqx:05273] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f799a64527e]
[runnervmmklqx:05273] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f799a6288ff]
[runnervmmklqx:05273] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f799aaa5ff5]
[runnervmmklqx:05273] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f799aabb0da]
[runnervmmklqx:05273] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f799aaa5a55]
[runnervmmklqx:05273] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f799aaa5a6f]
[runnervmmklqx:05273] [ 8] plumed_master(+0x146dd)[0x561fc807e6dd]
[runnervmmklqx:05273] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f799a62a1ca]
[runnervmmklqx:05273] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f799a62a28b]
[runnervmmklqx:05273] [11] plumed_master(+0x15365)[0x561fc807f365]
[runnervmmklqx:05273] *** End of error message ***
</pre>
{% endraw %}
