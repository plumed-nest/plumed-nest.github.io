**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvm7jw40e0xgp:08101] *** Process received signal ***
[pkrvm7jw40e0xgp:08101] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08101] Signal code:  (-6)
[pkrvm7jw40e0xgp:08101] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4122445330]
[pkrvm7jw40e0xgp:08101] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f412249eb2c]
[pkrvm7jw40e0xgp:08101] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f412244527e]
[pkrvm7jw40e0xgp:08101] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f41224288ff]
[pkrvm7jw40e0xgp:08101] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41228a5ff5]
[pkrvm7jw40e0xgp:08101] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41228bb0da]
[pkrvm7jw40e0xgp:08101] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41228a5a55]
[pkrvm7jw40e0xgp:08101] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41228a5a6f]
[pkrvm7jw40e0xgp:08101] [ 8] plumed(+0x146dd)[0x564d69fe36dd]
[pkrvm7jw40e0xgp:08101] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f412242a1ca]
[pkrvm7jw40e0xgp:08101] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f412242a28b]
[pkrvm7jw40e0xgp:08101] [11] plumed(+0x15365)[0x564d69fe4365]
[pkrvm7jw40e0xgp:08101] *** End of error message ***
</pre>
{% endraw %}
