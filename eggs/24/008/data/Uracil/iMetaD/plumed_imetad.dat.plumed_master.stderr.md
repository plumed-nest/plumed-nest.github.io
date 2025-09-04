**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Uracil/iMetaD/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[pkrvm7jw40e0xgp:08479] *** Process received signal ***
[pkrvm7jw40e0xgp:08479] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08479] Signal code:  (-6)
[pkrvm7jw40e0xgp:08479] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0e64445330]
[pkrvm7jw40e0xgp:08479] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0e6449eb2c]
[pkrvm7jw40e0xgp:08479] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0e6444527e]
[pkrvm7jw40e0xgp:08479] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0e644288ff]
[pkrvm7jw40e0xgp:08479] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0e648a5ff5]
[pkrvm7jw40e0xgp:08479] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0e648bb0da]
[pkrvm7jw40e0xgp:08479] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0e648a5a55]
[pkrvm7jw40e0xgp:08479] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0e648a5a6f]
[pkrvm7jw40e0xgp:08479] [ 8] plumed_master(+0x146dd)[0x560cce2c86dd]
[pkrvm7jw40e0xgp:08479] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0e6442a1ca]
[pkrvm7jw40e0xgp:08479] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0e6442a28b]
[pkrvm7jw40e0xgp:08479] [11] plumed_master(+0x15365)[0x560cce2c9365]
[pkrvm7jw40e0xgp:08479] *** End of error message ***
</pre>
{% endraw %}
