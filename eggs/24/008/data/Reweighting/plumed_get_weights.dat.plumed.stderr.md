**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1047-397:62014] *** Process received signal ***
[fv-az1047-397:62014] Signal: Aborted (6)
[fv-az1047-397:62014] Signal code:  (-6)
[fv-az1047-397:62014] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdc26c45330]
[fv-az1047-397:62014] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdc26c9eb2c]
[fv-az1047-397:62014] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdc26c4527e]
[fv-az1047-397:62014] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdc26c288ff]
[fv-az1047-397:62014] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdc270a5ff5]
[fv-az1047-397:62014] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdc270bb0da]
[fv-az1047-397:62014] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdc270a5a55]
[fv-az1047-397:62014] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdc270a5a6f]
[fv-az1047-397:62014] [ 8] plumed(+0x146dd)[0x5595c0dce6dd]
[fv-az1047-397:62014] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdc26c2a1ca]
[fv-az1047-397:62014] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdc26c2a28b]
[fv-az1047-397:62014] [11] plumed(+0x15365)[0x5595c0dcf365]
[fv-az1047-397:62014] *** End of error message ***
</pre>
{% endraw %}
