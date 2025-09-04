**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[pkrvm7jw40e0xgp:08852] *** Process received signal ***
[pkrvm7jw40e0xgp:08852] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08852] Signal code:  (-6)
[pkrvm7jw40e0xgp:08852] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc265645330]
[pkrvm7jw40e0xgp:08852] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc26569eb2c]
[pkrvm7jw40e0xgp:08852] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc26564527e]
[pkrvm7jw40e0xgp:08852] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc2656288ff]
[pkrvm7jw40e0xgp:08852] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc265aa5ff5]
[pkrvm7jw40e0xgp:08852] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc265abb0da]
[pkrvm7jw40e0xgp:08852] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc265aa5a55]
[pkrvm7jw40e0xgp:08852] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc265aa5a6f]
[pkrvm7jw40e0xgp:08852] [ 8] plumed_master(+0x146dd)[0x55f3d8ca66dd]
[pkrvm7jw40e0xgp:08852] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc26562a1ca]
[pkrvm7jw40e0xgp:08852] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc26562a28b]
[pkrvm7jw40e0xgp:08852] [11] plumed_master(+0x15365)[0x55f3d8ca7365]
[pkrvm7jw40e0xgp:08852] *** End of error message ***
</pre>
{% endraw %}
