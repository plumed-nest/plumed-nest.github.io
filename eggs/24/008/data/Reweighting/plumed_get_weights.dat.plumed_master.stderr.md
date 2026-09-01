**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmgx7h7:05927] *** Process received signal ***
[runnervmgx7h7:05927] Signal: Aborted (6)
[runnervmgx7h7:05927] Signal code:  (-6)
[runnervmgx7h7:05927] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7f4b445330]
[runnervmgx7h7:05927] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7f4b49ec0c]
[runnervmgx7h7:05927] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7f4b44527e]
[runnervmgx7h7:05927] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7f4b4288ff]
[runnervmgx7h7:05927] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7f4b8a5ff5]
[runnervmgx7h7:05927] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7f4b8bb0da]
[runnervmgx7h7:05927] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7f4b8a5a55]
[runnervmgx7h7:05927] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7f4b8a5a6f]
[runnervmgx7h7:05927] [ 8] plumed_master(+0x146dd)[0x561370c0b6dd]
[runnervmgx7h7:05927] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7f4b42a1ca]
[runnervmgx7h7:05927] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7f4b42a28b]
[runnervmgx7h7:05927] [11] plumed_master(+0x15365)[0x561370c0c365]
[runnervmgx7h7:05927] *** End of error message ***
</pre>
{% endraw %}
