**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmpptgkbjq6m:12734] *** Process received signal ***
[pkrvmpptgkbjq6m:12734] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12734] Signal code:  (-6)
[pkrvmpptgkbjq6m:12734] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7ac4445330]
[pkrvmpptgkbjq6m:12734] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7ac449eb2c]
[pkrvmpptgkbjq6m:12734] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7ac444527e]
[pkrvmpptgkbjq6m:12734] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7ac44288ff]
[pkrvmpptgkbjq6m:12734] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7ac48a5ff5]
[pkrvmpptgkbjq6m:12734] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7ac48bb0da]
[pkrvmpptgkbjq6m:12734] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7ac48a5a55]
[pkrvmpptgkbjq6m:12734] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7ac48a5a6f]
[pkrvmpptgkbjq6m:12734] [ 8] plumed_master(+0x146dd)[0x55e2a411b6dd]
[pkrvmpptgkbjq6m:12734] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7ac442a1ca]
[pkrvmpptgkbjq6m:12734] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7ac442a28b]
[pkrvmpptgkbjq6m:12734] [11] plumed_master(+0x15365)[0x55e2a411c365]
[pkrvmpptgkbjq6m:12734] *** End of error message ***
</pre>
{% endraw %}
