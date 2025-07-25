**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmpptgkbjq6m:09110] *** Process received signal ***
[pkrvmpptgkbjq6m:09110] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09110] Signal code:  (-6)
[pkrvmpptgkbjq6m:09110] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa549845330]
[pkrvmpptgkbjq6m:09110] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa54989eb2c]
[pkrvmpptgkbjq6m:09110] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa54984527e]
[pkrvmpptgkbjq6m:09110] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa5498288ff]
[pkrvmpptgkbjq6m:09110] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa549ca5ff5]
[pkrvmpptgkbjq6m:09110] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa549cbb0da]
[pkrvmpptgkbjq6m:09110] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa549ca5a55]
[pkrvmpptgkbjq6m:09110] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa549ca5a6f]
[pkrvmpptgkbjq6m:09110] [ 8] plumed_master(+0x146dd)[0x55d2631866dd]
[pkrvmpptgkbjq6m:09110] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa54982a1ca]
[pkrvmpptgkbjq6m:09110] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa54982a28b]
[pkrvmpptgkbjq6m:09110] [11] plumed_master(+0x15365)[0x55d263187365]
[pkrvmpptgkbjq6m:09110] *** End of error message ***
</pre>
{% endraw %}
