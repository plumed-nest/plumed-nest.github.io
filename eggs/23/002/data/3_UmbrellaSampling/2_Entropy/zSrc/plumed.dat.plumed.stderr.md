**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvm7jw40e0xgp:07838] *** Process received signal ***
[pkrvm7jw40e0xgp:07838] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07838] Signal code:  (-6)
[pkrvm7jw40e0xgp:07838] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d93245330]
[pkrvm7jw40e0xgp:07838] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d9329eb2c]
[pkrvm7jw40e0xgp:07838] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d9324527e]
[pkrvm7jw40e0xgp:07838] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d932288ff]
[pkrvm7jw40e0xgp:07838] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d936a5ff5]
[pkrvm7jw40e0xgp:07838] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d936bb0da]
[pkrvm7jw40e0xgp:07838] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d936a5a55]
[pkrvm7jw40e0xgp:07838] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d936a5a6f]
[pkrvm7jw40e0xgp:07838] [ 8] plumed(+0x146dd)[0x56453152c6dd]
[pkrvm7jw40e0xgp:07838] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d9322a1ca]
[pkrvm7jw40e0xgp:07838] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d9322a28b]
[pkrvm7jw40e0xgp:07838] [11] plumed(+0x15365)[0x56453152d365]
[pkrvm7jw40e0xgp:07838] *** End of error message ***
</pre>
{% endraw %}
