**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[pkrvm7jw40e0xgp:08836] *** Process received signal ***
[pkrvm7jw40e0xgp:08836] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08836] Signal code:  (-6)
[pkrvm7jw40e0xgp:08836] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa857e45330]
[pkrvm7jw40e0xgp:08836] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa857e9eb2c]
[pkrvm7jw40e0xgp:08836] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa857e4527e]
[pkrvm7jw40e0xgp:08836] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa857e288ff]
[pkrvm7jw40e0xgp:08836] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa8582a5ff5]
[pkrvm7jw40e0xgp:08836] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa8582bb0da]
[pkrvm7jw40e0xgp:08836] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa8582a5a55]
[pkrvm7jw40e0xgp:08836] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa8582a5a6f]
[pkrvm7jw40e0xgp:08836] [ 8] plumed(+0x146dd)[0x564719cf16dd]
[pkrvm7jw40e0xgp:08836] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa857e2a1ca]
[pkrvm7jw40e0xgp:08836] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa857e2a28b]
[pkrvm7jw40e0xgp:08836] [11] plumed(+0x15365)[0x564719cf2365]
[pkrvm7jw40e0xgp:08836] *** End of error message ***
</pre>
{% endraw %}
