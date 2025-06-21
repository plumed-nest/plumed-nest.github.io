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
[pkrvmxyh4eaekms:07756] *** Process received signal ***
[pkrvmxyh4eaekms:07756] Signal: Aborted (6)
[pkrvmxyh4eaekms:07756] Signal code:  (-6)
[pkrvmxyh4eaekms:07756] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd777645330]
[pkrvmxyh4eaekms:07756] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd77769eb2c]
[pkrvmxyh4eaekms:07756] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd77764527e]
[pkrvmxyh4eaekms:07756] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7776288ff]
[pkrvmxyh4eaekms:07756] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd777aa5ff5]
[pkrvmxyh4eaekms:07756] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd777abb0da]
[pkrvmxyh4eaekms:07756] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd777aa5a55]
[pkrvmxyh4eaekms:07756] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd777aa5a6f]
[pkrvmxyh4eaekms:07756] [ 8] plumed_master(+0x146dd)[0x5654cd55b6dd]
[pkrvmxyh4eaekms:07756] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd77762a1ca]
[pkrvmxyh4eaekms:07756] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd77762a28b]
[pkrvmxyh4eaekms:07756] [11] plumed_master(+0x15365)[0x5654cd55c365]
[pkrvmxyh4eaekms:07756] *** End of error message ***
</pre>
{% endraw %}
