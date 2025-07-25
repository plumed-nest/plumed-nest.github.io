**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmpptgkbjq6m:09043] *** Process received signal ***
[pkrvmpptgkbjq6m:09043] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09043] Signal code:  (-6)
[pkrvmpptgkbjq6m:09043] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4327a45330]
[pkrvmpptgkbjq6m:09043] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4327a9eb2c]
[pkrvmpptgkbjq6m:09043] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4327a4527e]
[pkrvmpptgkbjq6m:09043] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4327a288ff]
[pkrvmpptgkbjq6m:09043] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4327ea5ff5]
[pkrvmpptgkbjq6m:09043] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4327ebb0da]
[pkrvmpptgkbjq6m:09043] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4327ea5a55]
[pkrvmpptgkbjq6m:09043] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4327ea5a6f]
[pkrvmpptgkbjq6m:09043] [ 8] plumed(+0x146dd)[0x55f939db66dd]
[pkrvmpptgkbjq6m:09043] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4327a2a1ca]
[pkrvmpptgkbjq6m:09043] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4327a2a28b]
[pkrvmpptgkbjq6m:09043] [11] plumed(+0x15365)[0x55f939db7365]
[pkrvmpptgkbjq6m:09043] *** End of error message ***
</pre>
{% endraw %}
