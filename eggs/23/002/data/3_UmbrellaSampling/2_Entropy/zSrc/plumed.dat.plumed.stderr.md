**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmpptgkbjq6m:09094] *** Process received signal ***
[pkrvmpptgkbjq6m:09094] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09094] Signal code:  (-6)
[pkrvmpptgkbjq6m:09094] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1915e45330]
[pkrvmpptgkbjq6m:09094] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1915e9eb2c]
[pkrvmpptgkbjq6m:09094] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1915e4527e]
[pkrvmpptgkbjq6m:09094] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1915e288ff]
[pkrvmpptgkbjq6m:09094] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f19162a5ff5]
[pkrvmpptgkbjq6m:09094] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f19162bb0da]
[pkrvmpptgkbjq6m:09094] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f19162a5a55]
[pkrvmpptgkbjq6m:09094] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f19162a5a6f]
[pkrvmpptgkbjq6m:09094] [ 8] plumed(+0x146dd)[0x55d46daff6dd]
[pkrvmpptgkbjq6m:09094] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1915e2a1ca]
[pkrvmpptgkbjq6m:09094] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1915e2a28b]
[pkrvmpptgkbjq6m:09094] [11] plumed(+0x15365)[0x55d46db00365]
[pkrvmpptgkbjq6m:09094] *** End of error message ***
</pre>
{% endraw %}
