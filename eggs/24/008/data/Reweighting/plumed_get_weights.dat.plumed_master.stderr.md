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
[fv-az1374-933:06367] *** Process received signal ***
[fv-az1374-933:06367] Signal: Aborted (6)
[fv-az1374-933:06367] Signal code:  (-6)
[fv-az1374-933:06367] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e6f045330]
[fv-az1374-933:06367] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e6f09eb2c]
[fv-az1374-933:06367] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e6f04527e]
[fv-az1374-933:06367] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e6f0288ff]
[fv-az1374-933:06367] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e6f4a5ff5]
[fv-az1374-933:06367] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e6f4bb0da]
[fv-az1374-933:06367] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e6f4a5a55]
[fv-az1374-933:06367] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e6f4a5a6f]
[fv-az1374-933:06367] [ 8] plumed_master(+0x146dd)[0x5593368ff6dd]
[fv-az1374-933:06367] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e6f02a1ca]
[fv-az1374-933:06367] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e6f02a28b]
[fv-az1374-933:06367] [11] plumed_master(+0x15365)[0x559336900365]
[fv-az1374-933:06367] *** End of error message ***
</pre>
{% endraw %}
