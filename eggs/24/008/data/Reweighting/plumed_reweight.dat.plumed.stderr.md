**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmgx7h7:05963] *** Process received signal ***
[runnervmgx7h7:05963] Signal: Aborted (6)
[runnervmgx7h7:05963] Signal code:  (-6)
[runnervmgx7h7:05963] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f50e9845330]
[runnervmgx7h7:05963] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f50e989ec0c]
[runnervmgx7h7:05963] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f50e984527e]
[runnervmgx7h7:05963] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f50e98288ff]
[runnervmgx7h7:05963] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f50e9ca5ff5]
[runnervmgx7h7:05963] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f50e9cbb0da]
[runnervmgx7h7:05963] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f50e9ca5a55]
[runnervmgx7h7:05963] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f50e9ca5a6f]
[runnervmgx7h7:05963] [ 8] plumed(+0x146dd)[0x555908ca66dd]
[runnervmgx7h7:05963] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f50e982a1ca]
[runnervmgx7h7:05963] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f50e982a28b]
[runnervmgx7h7:05963] [11] plumed(+0x15365)[0x555908ca7365]
[runnervmgx7h7:05963] *** End of error message ***
</pre>
{% endraw %}
