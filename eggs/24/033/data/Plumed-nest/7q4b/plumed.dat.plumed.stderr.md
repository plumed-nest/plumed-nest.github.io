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
[pkrvm7jw40e0xgp:05927] *** Process received signal ***
[pkrvm7jw40e0xgp:05927] Signal: Aborted (6)
[pkrvm7jw40e0xgp:05927] Signal code:  (-6)
[pkrvm7jw40e0xgp:05927] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fecfc845330]
[pkrvm7jw40e0xgp:05927] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fecfc89eb2c]
[pkrvm7jw40e0xgp:05927] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fecfc84527e]
[pkrvm7jw40e0xgp:05927] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fecfc8288ff]
[pkrvm7jw40e0xgp:05927] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fecfcca5ff5]
[pkrvm7jw40e0xgp:05927] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fecfccbb0da]
[pkrvm7jw40e0xgp:05927] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fecfcca5a55]
[pkrvm7jw40e0xgp:05927] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fecfcca5a6f]
[pkrvm7jw40e0xgp:05927] [ 8] plumed(+0x146dd)[0x55951bac66dd]
[pkrvm7jw40e0xgp:05927] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fecfc82a1ca]
[pkrvm7jw40e0xgp:05927] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fecfc82a28b]
[pkrvm7jw40e0xgp:05927] [11] plumed(+0x15365)[0x55951bac7365]
[pkrvm7jw40e0xgp:05927] *** End of error message ***
</pre>
{% endraw %}
