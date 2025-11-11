**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmw9dnm:07896] *** Process received signal ***
[runnervmw9dnm:07896] Signal: Aborted (6)
[runnervmw9dnm:07896] Signal code:  (-6)
[runnervmw9dnm:07896] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f83c8445330]
[runnervmw9dnm:07896] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f83c849eb2c]
[runnervmw9dnm:07896] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f83c844527e]
[runnervmw9dnm:07896] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83c84288ff]
[runnervmw9dnm:07896] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83c88a5ff5]
[runnervmw9dnm:07896] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83c88bb0da]
[runnervmw9dnm:07896] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83c88a5a55]
[runnervmw9dnm:07896] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83c88a5a6f]
[runnervmw9dnm:07896] [ 8] plumed_master(+0x146dd)[0x55bc8dedd6dd]
[runnervmw9dnm:07896] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f83c842a1ca]
[runnervmw9dnm:07896] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f83c842a28b]
[runnervmw9dnm:07896] [11] plumed_master(+0x15365)[0x55bc8dede365]
[runnervmw9dnm:07896] *** End of error message ***
</pre>
{% endraw %}
