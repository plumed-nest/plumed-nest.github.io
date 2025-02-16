**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1665-105:60740] *** Process received signal ***
[fv-az1665-105:60740] Signal: Aborted (6)
[fv-az1665-105:60740] Signal code:  (-6)
[fv-az1665-105:60740] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4eb5645330]
[fv-az1665-105:60740] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4eb569eb2c]
[fv-az1665-105:60740] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4eb564527e]
[fv-az1665-105:60740] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4eb56288ff]
[fv-az1665-105:60740] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4eb5aa5ff5]
[fv-az1665-105:60740] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4eb5abb0da]
[fv-az1665-105:60740] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4eb5aa5a55]
[fv-az1665-105:60740] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4eb5aa5a6f]
[fv-az1665-105:60740] [ 8] plumed_master(+0x146dd)[0x5593e054b6dd]
[fv-az1665-105:60740] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4eb562a1ca]
[fv-az1665-105:60740] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4eb562a28b]
[fv-az1665-105:60740] [11] plumed_master(+0x15365)[0x5593e054c365]
[fv-az1665-105:60740] *** End of error message ***
</pre>
{% endraw %}
