**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1665-105:05534] *** Process received signal ***
[fv-az1665-105:05534] Signal: Aborted (6)
[fv-az1665-105:05534] Signal code:  (-6)
[fv-az1665-105:05534] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f79b7845330]
[fv-az1665-105:05534] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f79b789eb2c]
[fv-az1665-105:05534] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f79b784527e]
[fv-az1665-105:05534] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79b78288ff]
[fv-az1665-105:05534] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f79b7ca5ff5]
[fv-az1665-105:05534] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f79b7cbb0da]
[fv-az1665-105:05534] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f79b7ca5a55]
[fv-az1665-105:05534] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f79b7ca5a6f]
[fv-az1665-105:05534] [ 8] plumed(+0x146dd)[0x561b315876dd]
[fv-az1665-105:05534] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f79b782a1ca]
[fv-az1665-105:05534] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f79b782a28b]
[fv-az1665-105:05534] [11] plumed(+0x15365)[0x561b31588365]
[fv-az1665-105:05534] *** End of error message ***
</pre>
{% endraw %}
