**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1665-105:60687] *** Process received signal ***
[fv-az1665-105:60687] Signal: Aborted (6)
[fv-az1665-105:60687] Signal code:  (-6)
[fv-az1665-105:60687] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5f36245330]
[fv-az1665-105:60687] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5f3629eb2c]
[fv-az1665-105:60687] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5f3624527e]
[fv-az1665-105:60687] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5f362288ff]
[fv-az1665-105:60687] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5f366a5ff5]
[fv-az1665-105:60687] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5f366bb0da]
[fv-az1665-105:60687] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5f366a5a55]
[fv-az1665-105:60687] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5f366a5a6f]
[fv-az1665-105:60687] [ 8] plumed_master(+0x146dd)[0x55d0f09436dd]
[fv-az1665-105:60687] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5f3622a1ca]
[fv-az1665-105:60687] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5f3622a28b]
[fv-az1665-105:60687] [11] plumed_master(+0x15365)[0x55d0f0944365]
[fv-az1665-105:60687] *** End of error message ***
</pre>
{% endraw %}
