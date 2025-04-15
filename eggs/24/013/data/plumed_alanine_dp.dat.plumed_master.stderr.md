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
[fv-az1277-646:61122] *** Process received signal ***
[fv-az1277-646:61122] Signal: Aborted (6)
[fv-az1277-646:61122] Signal code:  (-6)
[fv-az1277-646:61122] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1534845330]
[fv-az1277-646:61122] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f153489eb2c]
[fv-az1277-646:61122] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f153484527e]
[fv-az1277-646:61122] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f15348288ff]
[fv-az1277-646:61122] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1534ca5ff5]
[fv-az1277-646:61122] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1534cbb0da]
[fv-az1277-646:61122] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1534ca5a55]
[fv-az1277-646:61122] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1534ca5a6f]
[fv-az1277-646:61122] [ 8] plumed_master(+0x146dd)[0x55e95d3116dd]
[fv-az1277-646:61122] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f153482a1ca]
[fv-az1277-646:61122] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f153482a28b]
[fv-az1277-646:61122] [11] plumed_master(+0x15365)[0x55e95d312365]
[fv-az1277-646:61122] *** End of error message ***
</pre>
{% endraw %}
