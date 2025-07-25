**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmpptgkbjq6m:06351] *** Process received signal ***
[pkrvmpptgkbjq6m:06351] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06351] Signal code:  (-6)
[pkrvmpptgkbjq6m:06351] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff88f845330]
[pkrvmpptgkbjq6m:06351] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff88f89eb2c]
[pkrvmpptgkbjq6m:06351] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff88f84527e]
[pkrvmpptgkbjq6m:06351] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff88f8288ff]
[pkrvmpptgkbjq6m:06351] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff88fca5ff5]
[pkrvmpptgkbjq6m:06351] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff88fcbb0da]
[pkrvmpptgkbjq6m:06351] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff88fca5a55]
[pkrvmpptgkbjq6m:06351] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff88fca5a6f]
[pkrvmpptgkbjq6m:06351] [ 8] plumed_master(+0x146dd)[0x558016bdc6dd]
[pkrvmpptgkbjq6m:06351] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff88f82a1ca]
[pkrvmpptgkbjq6m:06351] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff88f82a28b]
[pkrvmpptgkbjq6m:06351] [11] plumed_master(+0x15365)[0x558016bdd365]
[pkrvmpptgkbjq6m:06351] *** End of error message ***
</pre>
{% endraw %}
