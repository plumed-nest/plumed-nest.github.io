**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmpptgkbjq6m:07910] *** Process received signal ***
[pkrvmpptgkbjq6m:07910] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07910] Signal code:  (-6)
[pkrvmpptgkbjq6m:07910] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa8df045330]
[pkrvmpptgkbjq6m:07910] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa8df09eb2c]
[pkrvmpptgkbjq6m:07910] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa8df04527e]
[pkrvmpptgkbjq6m:07910] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa8df0288ff]
[pkrvmpptgkbjq6m:07910] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa8df4a5ff5]
[pkrvmpptgkbjq6m:07910] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa8df4bb0da]
[pkrvmpptgkbjq6m:07910] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa8df4a5a55]
[pkrvmpptgkbjq6m:07910] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa8df4a5a6f]
[pkrvmpptgkbjq6m:07910] [ 8] plumed_master(+0x146dd)[0x556845b8f6dd]
[pkrvmpptgkbjq6m:07910] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa8df02a1ca]
[pkrvmpptgkbjq6m:07910] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa8df02a28b]
[pkrvmpptgkbjq6m:07910] [11] plumed_master(+0x15365)[0x556845b90365]
[pkrvmpptgkbjq6m:07910] *** End of error message ***
</pre>
{% endraw %}
