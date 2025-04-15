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
[fv-az1047-397:62084] *** Process received signal ***
[fv-az1047-397:62084] Signal: Aborted (6)
[fv-az1047-397:62084] Signal code:  (-6)
[fv-az1047-397:62084] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f175dc45330]
[fv-az1047-397:62084] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f175dc9eb2c]
[fv-az1047-397:62084] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f175dc4527e]
[fv-az1047-397:62084] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f175dc288ff]
[fv-az1047-397:62084] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f175e0a5ff5]
[fv-az1047-397:62084] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f175e0bb0da]
[fv-az1047-397:62084] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f175e0a5a55]
[fv-az1047-397:62084] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f175e0a5a6f]
[fv-az1047-397:62084] [ 8] plumed_master(+0x146dd)[0x5603dcb976dd]
[fv-az1047-397:62084] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f175dc2a1ca]
[fv-az1047-397:62084] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f175dc2a28b]
[fv-az1047-397:62084] [11] plumed_master(+0x15365)[0x5603dcb98365]
[fv-az1047-397:62084] *** End of error message ***
</pre>
{% endraw %}
