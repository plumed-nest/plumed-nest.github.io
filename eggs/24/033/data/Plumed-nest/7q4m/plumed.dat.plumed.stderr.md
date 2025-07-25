**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmpptgkbjq6m:06490] *** Process received signal ***
[pkrvmpptgkbjq6m:06490] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06490] Signal code:  (-6)
[pkrvmpptgkbjq6m:06490] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feb9f645330]
[pkrvmpptgkbjq6m:06490] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feb9f69eb2c]
[pkrvmpptgkbjq6m:06490] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feb9f64527e]
[pkrvmpptgkbjq6m:06490] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feb9f6288ff]
[pkrvmpptgkbjq6m:06490] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feb9faa5ff5]
[pkrvmpptgkbjq6m:06490] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feb9fabb0da]
[pkrvmpptgkbjq6m:06490] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feb9faa5a55]
[pkrvmpptgkbjq6m:06490] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feb9faa5a6f]
[pkrvmpptgkbjq6m:06490] [ 8] plumed(+0x146dd)[0x55dd50b456dd]
[pkrvmpptgkbjq6m:06490] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feb9f62a1ca]
[pkrvmpptgkbjq6m:06490] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feb9f62a28b]
[pkrvmpptgkbjq6m:06490] [11] plumed(+0x15365)[0x55dd50b46365]
[pkrvmpptgkbjq6m:06490] *** End of error message ***
</pre>
{% endraw %}
