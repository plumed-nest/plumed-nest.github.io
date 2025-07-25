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
[pkrvmpptgkbjq6m:06507] *** Process received signal ***
[pkrvmpptgkbjq6m:06507] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06507] Signal code:  (-6)
[pkrvmpptgkbjq6m:06507] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1aff045330]
[pkrvmpptgkbjq6m:06507] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1aff09eb2c]
[pkrvmpptgkbjq6m:06507] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1aff04527e]
[pkrvmpptgkbjq6m:06507] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1aff0288ff]
[pkrvmpptgkbjq6m:06507] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1aff4a5ff5]
[pkrvmpptgkbjq6m:06507] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1aff4bb0da]
[pkrvmpptgkbjq6m:06507] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1aff4a5a55]
[pkrvmpptgkbjq6m:06507] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1aff4a5a6f]
[pkrvmpptgkbjq6m:06507] [ 8] plumed_master(+0x146dd)[0x55bf868226dd]
[pkrvmpptgkbjq6m:06507] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1aff02a1ca]
[pkrvmpptgkbjq6m:06507] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1aff02a28b]
[pkrvmpptgkbjq6m:06507] [11] plumed_master(+0x15365)[0x55bf86823365]
[pkrvmpptgkbjq6m:06507] *** End of error message ***
</pre>
{% endraw %}
