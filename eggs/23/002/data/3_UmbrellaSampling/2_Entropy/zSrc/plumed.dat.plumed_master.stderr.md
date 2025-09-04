**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvm7jw40e0xgp:07854] *** Process received signal ***
[pkrvm7jw40e0xgp:07854] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07854] Signal code:  (-6)
[pkrvm7jw40e0xgp:07854] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efcc9245330]
[pkrvm7jw40e0xgp:07854] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efcc929eb2c]
[pkrvm7jw40e0xgp:07854] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efcc924527e]
[pkrvm7jw40e0xgp:07854] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efcc92288ff]
[pkrvm7jw40e0xgp:07854] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efcc96a5ff5]
[pkrvm7jw40e0xgp:07854] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efcc96bb0da]
[pkrvm7jw40e0xgp:07854] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efcc96a5a55]
[pkrvm7jw40e0xgp:07854] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efcc96a5a6f]
[pkrvm7jw40e0xgp:07854] [ 8] plumed_master(+0x146dd)[0x55f6752606dd]
[pkrvm7jw40e0xgp:07854] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efcc922a1ca]
[pkrvm7jw40e0xgp:07854] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efcc922a28b]
[pkrvm7jw40e0xgp:07854] [11] plumed_master(+0x15365)[0x55f675261365]
[pkrvm7jw40e0xgp:07854] *** End of error message ***
</pre>
{% endraw %}
