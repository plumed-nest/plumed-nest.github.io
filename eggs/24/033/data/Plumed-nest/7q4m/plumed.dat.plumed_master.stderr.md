**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmxyh4eaekms:05912] *** Process received signal ***
[pkrvmxyh4eaekms:05912] Signal: Aborted (6)
[pkrvmxyh4eaekms:05912] Signal code:  (-6)
[pkrvmxyh4eaekms:05912] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4528c45330]
[pkrvmxyh4eaekms:05912] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4528c9eb2c]
[pkrvmxyh4eaekms:05912] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4528c4527e]
[pkrvmxyh4eaekms:05912] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4528c288ff]
[pkrvmxyh4eaekms:05912] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45290a5ff5]
[pkrvmxyh4eaekms:05912] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45290bb0da]
[pkrvmxyh4eaekms:05912] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45290a5a55]
[pkrvmxyh4eaekms:05912] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45290a5a6f]
[pkrvmxyh4eaekms:05912] [ 8] plumed_master(+0x146dd)[0x560bfd0d96dd]
[pkrvmxyh4eaekms:05912] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4528c2a1ca]
[pkrvmxyh4eaekms:05912] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4528c2a28b]
[pkrvmxyh4eaekms:05912] [11] plumed_master(+0x15365)[0x560bfd0da365]
[pkrvmxyh4eaekms:05912] *** End of error message ***
</pre>
{% endraw %}
