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
[runnervmkj6or:04866] *** Process received signal ***
[runnervmkj6or:04866] Signal: Aborted (6)
[runnervmkj6or:04866] Signal code:  (-6)
[runnervmkj6or:04866] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6fe9a45330]
[runnervmkj6or:04866] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6fe9a9eb2c]
[runnervmkj6or:04866] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6fe9a4527e]
[runnervmkj6or:04866] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6fe9a288ff]
[runnervmkj6or:04866] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6fe9ea5ff5]
[runnervmkj6or:04866] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6fe9ebb0da]
[runnervmkj6or:04866] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6fe9ea5a55]
[runnervmkj6or:04866] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6fe9ea5a6f]
[runnervmkj6or:04866] [ 8] plumed(+0x146dd)[0x55580650a6dd]
[runnervmkj6or:04866] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6fe9a2a1ca]
[runnervmkj6or:04866] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6fe9a2a28b]
[runnervmkj6or:04866] [11] plumed(+0x15365)[0x55580650b365]
[runnervmkj6or:04866] *** End of error message ***
</pre>
{% endraw %}
