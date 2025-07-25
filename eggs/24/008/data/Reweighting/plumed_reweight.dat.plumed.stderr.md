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
[pkrvmpptgkbjq6m:07948] *** Process received signal ***
[pkrvmpptgkbjq6m:07948] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07948] Signal code:  (-6)
[pkrvmpptgkbjq6m:07948] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0e64845330]
[pkrvmpptgkbjq6m:07948] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0e6489eb2c]
[pkrvmpptgkbjq6m:07948] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0e6484527e]
[pkrvmpptgkbjq6m:07948] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0e648288ff]
[pkrvmpptgkbjq6m:07948] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0e64ca5ff5]
[pkrvmpptgkbjq6m:07948] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0e64cbb0da]
[pkrvmpptgkbjq6m:07948] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0e64ca5a55]
[pkrvmpptgkbjq6m:07948] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0e64ca5a6f]
[pkrvmpptgkbjq6m:07948] [ 8] plumed(+0x146dd)[0x558af97626dd]
[pkrvmpptgkbjq6m:07948] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0e6482a1ca]
[pkrvmpptgkbjq6m:07948] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0e6482a28b]
[pkrvmpptgkbjq6m:07948] [11] plumed(+0x15365)[0x558af9763365]
[pkrvmpptgkbjq6m:07948] *** End of error message ***
</pre>
{% endraw %}
