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
[fv-az1937-158:61205] *** Process received signal ***
[fv-az1937-158:61205] Signal: Aborted (6)
[fv-az1937-158:61205] Signal code:  (-6)
[fv-az1937-158:61205] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1742045330]
[fv-az1937-158:61205] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f174209eb2c]
[fv-az1937-158:61205] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f174204527e]
[fv-az1937-158:61205] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f17420288ff]
[fv-az1937-158:61205] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f17424a5ff5]
[fv-az1937-158:61205] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f17424bb0da]
[fv-az1937-158:61205] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f17424a5a55]
[fv-az1937-158:61205] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f17424a5a6f]
[fv-az1937-158:61205] [ 8] plumed_master(+0x146dd)[0x55d923ac26dd]
[fv-az1937-158:61205] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f174202a1ca]
[fv-az1937-158:61205] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f174202a28b]
[fv-az1937-158:61205] [11] plumed_master(+0x15365)[0x55d923ac3365]
[fv-az1937-158:61205] *** End of error message ***
</pre>
{% endraw %}
