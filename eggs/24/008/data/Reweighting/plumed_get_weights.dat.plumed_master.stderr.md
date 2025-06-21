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
[pkrvmxyh4eaekms:07699] *** Process received signal ***
[pkrvmxyh4eaekms:07699] Signal: Aborted (6)
[pkrvmxyh4eaekms:07699] Signal code:  (-6)
[pkrvmxyh4eaekms:07699] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb8ff045330]
[pkrvmxyh4eaekms:07699] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb8ff09eb2c]
[pkrvmxyh4eaekms:07699] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb8ff04527e]
[pkrvmxyh4eaekms:07699] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8ff0288ff]
[pkrvmxyh4eaekms:07699] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8ff4a5ff5]
[pkrvmxyh4eaekms:07699] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8ff4bb0da]
[pkrvmxyh4eaekms:07699] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8ff4a5a55]
[pkrvmxyh4eaekms:07699] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8ff4a5a6f]
[pkrvmxyh4eaekms:07699] [ 8] plumed_master(+0x146dd)[0x558bcfda26dd]
[pkrvmxyh4eaekms:07699] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb8ff02a1ca]
[pkrvmxyh4eaekms:07699] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb8ff02a28b]
[pkrvmxyh4eaekms:07699] [11] plumed_master(+0x15365)[0x558bcfda3365]
[pkrvmxyh4eaekms:07699] *** End of error message ***
</pre>
{% endraw %}
