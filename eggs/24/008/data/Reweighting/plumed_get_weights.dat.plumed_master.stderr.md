**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1983-395:61109] *** Process received signal ***
[fv-az1983-395:61109] Signal: Aborted (6)
[fv-az1983-395:61109] Signal code:  (-6)
[fv-az1983-395:61109] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdb8e645330]
[fv-az1983-395:61109] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdb8e69eb2c]
[fv-az1983-395:61109] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdb8e64527e]
[fv-az1983-395:61109] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdb8e6288ff]
[fv-az1983-395:61109] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdb8eaa5ff5]
[fv-az1983-395:61109] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdb8eabb0da]
[fv-az1983-395:61109] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdb8eaa5a55]
[fv-az1983-395:61109] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdb8eaa5a6f]
[fv-az1983-395:61109] [ 8] plumed_master(+0x146dd)[0x5579b80136dd]
[fv-az1983-395:61109] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdb8e62a1ca]
[fv-az1983-395:61109] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdb8e62a28b]
[fv-az1983-395:61109] [11] plumed_master(+0x15365)[0x5579b8014365]
[fv-az1983-395:61109] *** End of error message ***
</pre>
{% endraw %}
