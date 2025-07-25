**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmpptgkbjq6m:06335] *** Process received signal ***
[pkrvmpptgkbjq6m:06335] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06335] Signal code:  (-6)
[pkrvmpptgkbjq6m:06335] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f370f245330]
[pkrvmpptgkbjq6m:06335] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f370f29eb2c]
[pkrvmpptgkbjq6m:06335] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f370f24527e]
[pkrvmpptgkbjq6m:06335] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f370f2288ff]
[pkrvmpptgkbjq6m:06335] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f370f6a5ff5]
[pkrvmpptgkbjq6m:06335] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f370f6bb0da]
[pkrvmpptgkbjq6m:06335] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f370f6a5a55]
[pkrvmpptgkbjq6m:06335] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f370f6a5a6f]
[pkrvmpptgkbjq6m:06335] [ 8] plumed(+0x146dd)[0x5619503796dd]
[pkrvmpptgkbjq6m:06335] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f370f22a1ca]
[pkrvmpptgkbjq6m:06335] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f370f22a28b]
[pkrvmpptgkbjq6m:06335] [11] plumed(+0x15365)[0x56195037a365]
[pkrvmpptgkbjq6m:06335] *** End of error message ***
</pre>
{% endraw %}
