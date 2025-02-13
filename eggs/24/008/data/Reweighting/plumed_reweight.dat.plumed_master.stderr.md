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
[fv-az1665-105:05550] *** Process received signal ***
[fv-az1665-105:05550] Signal: Aborted (6)
[fv-az1665-105:05550] Signal code:  (-6)
[fv-az1665-105:05550] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fafe7e45330]
[fv-az1665-105:05550] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fafe7e9eb2c]
[fv-az1665-105:05550] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fafe7e4527e]
[fv-az1665-105:05550] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fafe7e288ff]
[fv-az1665-105:05550] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fafe82a5ff5]
[fv-az1665-105:05550] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fafe82bb0da]
[fv-az1665-105:05550] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fafe82a5a55]
[fv-az1665-105:05550] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fafe82a5a6f]
[fv-az1665-105:05550] [ 8] plumed_master(+0x146dd)[0x5631002e36dd]
[fv-az1665-105:05550] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fafe7e2a1ca]
[fv-az1665-105:05550] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fafe7e2a28b]
[fv-az1665-105:05550] [11] plumed_master(+0x15365)[0x5631002e4365]
[fv-az1665-105:05550] *** End of error message ***
</pre>
{% endraw %}
