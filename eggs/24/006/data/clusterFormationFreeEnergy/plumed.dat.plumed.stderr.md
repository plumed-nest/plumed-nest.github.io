**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:07356] *** Process received signal ***
[pkrvm7jw40e0xgp:07356] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07356] Signal code:  (-6)
[pkrvm7jw40e0xgp:07356] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f83f0e45330]
[pkrvm7jw40e0xgp:07356] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f83f0e9eb2c]
[pkrvm7jw40e0xgp:07356] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f83f0e4527e]
[pkrvm7jw40e0xgp:07356] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83f0e288ff]
[pkrvm7jw40e0xgp:07356] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83f12a5ff5]
[pkrvm7jw40e0xgp:07356] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83f12bb0da]
[pkrvm7jw40e0xgp:07356] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83f12a5a55]
[pkrvm7jw40e0xgp:07356] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83f12a5a6f]
[pkrvm7jw40e0xgp:07356] [ 8] plumed(+0x146dd)[0x55b8b1deb6dd]
[pkrvm7jw40e0xgp:07356] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f83f0e2a1ca]
[pkrvm7jw40e0xgp:07356] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f83f0e2a28b]
[pkrvm7jw40e0xgp:07356] [11] plumed(+0x15365)[0x55b8b1dec365]
[pkrvm7jw40e0xgp:07356] *** End of error message ***
</pre>
{% endraw %}
