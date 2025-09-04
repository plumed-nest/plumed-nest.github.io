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
[pkrvm7jw40e0xgp:06073] *** Process received signal ***
[pkrvm7jw40e0xgp:06073] Signal: Aborted (6)
[pkrvm7jw40e0xgp:06073] Signal code:  (-6)
[pkrvm7jw40e0xgp:06073] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f71e6c45330]
[pkrvm7jw40e0xgp:06073] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f71e6c9eb2c]
[pkrvm7jw40e0xgp:06073] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f71e6c4527e]
[pkrvm7jw40e0xgp:06073] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71e6c288ff]
[pkrvm7jw40e0xgp:06073] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f71e70a5ff5]
[pkrvm7jw40e0xgp:06073] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f71e70bb0da]
[pkrvm7jw40e0xgp:06073] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f71e70a5a55]
[pkrvm7jw40e0xgp:06073] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f71e70a5a6f]
[pkrvm7jw40e0xgp:06073] [ 8] plumed(+0x146dd)[0x55743c22f6dd]
[pkrvm7jw40e0xgp:06073] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f71e6c2a1ca]
[pkrvm7jw40e0xgp:06073] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f71e6c2a28b]
[pkrvm7jw40e0xgp:06073] [11] plumed(+0x15365)[0x55743c230365]
[pkrvm7jw40e0xgp:06073] *** End of error message ***
</pre>
{% endraw %}
