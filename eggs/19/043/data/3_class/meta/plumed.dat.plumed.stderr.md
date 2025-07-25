**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmpptgkbjq6m:12718] *** Process received signal ***
[pkrvmpptgkbjq6m:12718] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12718] Signal code:  (-6)
[pkrvmpptgkbjq6m:12718] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe429c45330]
[pkrvmpptgkbjq6m:12718] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe429c9eb2c]
[pkrvmpptgkbjq6m:12718] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe429c4527e]
[pkrvmpptgkbjq6m:12718] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe429c288ff]
[pkrvmpptgkbjq6m:12718] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe42a0a5ff5]
[pkrvmpptgkbjq6m:12718] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe42a0bb0da]
[pkrvmpptgkbjq6m:12718] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe42a0a5a55]
[pkrvmpptgkbjq6m:12718] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe42a0a5a6f]
[pkrvmpptgkbjq6m:12718] [ 8] plumed(+0x146dd)[0x55d6a6e696dd]
[pkrvmpptgkbjq6m:12718] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe429c2a1ca]
[pkrvmpptgkbjq6m:12718] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe429c2a28b]
[pkrvmpptgkbjq6m:12718] [11] plumed(+0x15365)[0x55d6a6e6a365]
[pkrvmpptgkbjq6m:12718] *** End of error message ***
</pre>
{% endraw %}
