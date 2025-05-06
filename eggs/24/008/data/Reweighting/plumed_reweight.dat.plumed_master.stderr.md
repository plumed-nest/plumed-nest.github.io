**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az2209-645:61165] *** Process received signal ***
[fv-az2209-645:61165] Signal: Aborted (6)
[fv-az2209-645:61165] Signal code:  (-6)
[fv-az2209-645:61165] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f378fe45330]
[fv-az2209-645:61165] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f378fe9eb2c]
[fv-az2209-645:61165] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f378fe4527e]
[fv-az2209-645:61165] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f378fe288ff]
[fv-az2209-645:61165] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f37902a5ff5]
[fv-az2209-645:61165] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f37902bb0da]
[fv-az2209-645:61165] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f37902a5a55]
[fv-az2209-645:61165] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f37902a5a6f]
[fv-az2209-645:61165] [ 8] plumed_master(+0x146dd)[0x5643cb0306dd]
[fv-az2209-645:61165] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f378fe2a1ca]
[fv-az2209-645:61165] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f378fe2a28b]
[fv-az2209-645:61165] [11] plumed_master(+0x15365)[0x5643cb031365]
[fv-az2209-645:61165] *** End of error message ***
</pre>
{% endraw %}
