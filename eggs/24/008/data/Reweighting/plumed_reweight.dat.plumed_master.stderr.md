**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmpptgkbjq6m:07964] *** Process received signal ***
[pkrvmpptgkbjq6m:07964] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07964] Signal code:  (-6)
[pkrvmpptgkbjq6m:07964] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ffb445330]
[pkrvmpptgkbjq6m:07964] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ffb49eb2c]
[pkrvmpptgkbjq6m:07964] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ffb44527e]
[pkrvmpptgkbjq6m:07964] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ffb4288ff]
[pkrvmpptgkbjq6m:07964] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ffb8a5ff5]
[pkrvmpptgkbjq6m:07964] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ffb8bb0da]
[pkrvmpptgkbjq6m:07964] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ffb8a5a55]
[pkrvmpptgkbjq6m:07964] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ffb8a5a6f]
[pkrvmpptgkbjq6m:07964] [ 8] plumed_master(+0x146dd)[0x55c0658f66dd]
[pkrvmpptgkbjq6m:07964] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ffb42a1ca]
[pkrvmpptgkbjq6m:07964] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ffb42a28b]
[pkrvmpptgkbjq6m:07964] [11] plumed_master(+0x15365)[0x55c0658f7365]
[pkrvmpptgkbjq6m:07964] *** End of error message ***
</pre>
{% endraw %}
