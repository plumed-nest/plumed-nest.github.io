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
[pkrvm7jw40e0xgp:13926] *** Process received signal ***
[pkrvm7jw40e0xgp:13926] Signal: Aborted (6)
[pkrvm7jw40e0xgp:13926] Signal code:  (-6)
[pkrvm7jw40e0xgp:13926] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb4f8e45330]
[pkrvm7jw40e0xgp:13926] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb4f8e9eb2c]
[pkrvm7jw40e0xgp:13926] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb4f8e4527e]
[pkrvm7jw40e0xgp:13926] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4f8e288ff]
[pkrvm7jw40e0xgp:13926] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4f92a5ff5]
[pkrvm7jw40e0xgp:13926] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4f92bb0da]
[pkrvm7jw40e0xgp:13926] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4f92a5a55]
[pkrvm7jw40e0xgp:13926] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4f92a5a6f]
[pkrvm7jw40e0xgp:13926] [ 8] plumed(+0x146dd)[0x55c05798a6dd]
[pkrvm7jw40e0xgp:13926] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb4f8e2a1ca]
[pkrvm7jw40e0xgp:13926] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb4f8e2a28b]
[pkrvm7jw40e0xgp:13926] [11] plumed(+0x15365)[0x55c05798b365]
[pkrvm7jw40e0xgp:13926] *** End of error message ***
</pre>
{% endraw %}
