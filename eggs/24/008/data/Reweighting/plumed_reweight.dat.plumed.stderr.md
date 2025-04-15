**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1047-397:62067] *** Process received signal ***
[fv-az1047-397:62067] Signal: Aborted (6)
[fv-az1047-397:62067] Signal code:  (-6)
[fv-az1047-397:62067] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7826e45330]
[fv-az1047-397:62067] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7826e9eb2c]
[fv-az1047-397:62067] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7826e4527e]
[fv-az1047-397:62067] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7826e288ff]
[fv-az1047-397:62067] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f78272a5ff5]
[fv-az1047-397:62067] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f78272bb0da]
[fv-az1047-397:62067] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f78272a5a55]
[fv-az1047-397:62067] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f78272a5a6f]
[fv-az1047-397:62067] [ 8] plumed(+0x146dd)[0x5569b71866dd]
[fv-az1047-397:62067] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7826e2a1ca]
[fv-az1047-397:62067] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7826e2a28b]
[fv-az1047-397:62067] [11] plumed(+0x15365)[0x5569b7187365]
[fv-az1047-397:62067] *** End of error message ***
</pre>
{% endraw %}
