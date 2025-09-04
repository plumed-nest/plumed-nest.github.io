**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[pkrvm7jw40e0xgp:08222] *** Process received signal ***
[pkrvm7jw40e0xgp:08222] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08222] Signal code:  (-6)
[pkrvm7jw40e0xgp:08222] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f95cea45330]
[pkrvm7jw40e0xgp:08222] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f95cea9eb2c]
[pkrvm7jw40e0xgp:08222] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f95cea4527e]
[pkrvm7jw40e0xgp:08222] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95cea288ff]
[pkrvm7jw40e0xgp:08222] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f95ceea5ff5]
[pkrvm7jw40e0xgp:08222] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f95ceebb0da]
[pkrvm7jw40e0xgp:08222] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f95ceea5a55]
[pkrvm7jw40e0xgp:08222] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f95ceea5a6f]
[pkrvm7jw40e0xgp:08222] [ 8] plumed_master(+0x146dd)[0x5563c04036dd]
[pkrvm7jw40e0xgp:08222] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f95cea2a1ca]
[pkrvm7jw40e0xgp:08222] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f95cea2a28b]
[pkrvm7jw40e0xgp:08222] [11] plumed_master(+0x15365)[0x5563c0404365]
[pkrvm7jw40e0xgp:08222] *** End of error message ***
</pre>
{% endraw %}
