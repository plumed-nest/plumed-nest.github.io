**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvm7jw40e0xgp:08733] *** Process received signal ***
[pkrvm7jw40e0xgp:08733] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08733] Signal code:  (-6)
[pkrvm7jw40e0xgp:08733] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f80b2e45330]
[pkrvm7jw40e0xgp:08733] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f80b2e9eb2c]
[pkrvm7jw40e0xgp:08733] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f80b2e4527e]
[pkrvm7jw40e0xgp:08733] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f80b2e288ff]
[pkrvm7jw40e0xgp:08733] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f80b32a5ff5]
[pkrvm7jw40e0xgp:08733] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f80b32bb0da]
[pkrvm7jw40e0xgp:08733] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f80b32a5a55]
[pkrvm7jw40e0xgp:08733] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f80b32a5a6f]
[pkrvm7jw40e0xgp:08733] [ 8] plumed(+0x146dd)[0x55cd8c7276dd]
[pkrvm7jw40e0xgp:08733] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f80b2e2a1ca]
[pkrvm7jw40e0xgp:08733] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f80b2e2a28b]
[pkrvm7jw40e0xgp:08733] [11] plumed(+0x15365)[0x55cd8c728365]
[pkrvm7jw40e0xgp:08733] *** End of error message ***
</pre>
{% endraw %}
