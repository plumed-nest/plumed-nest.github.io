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
[pkrvmpptgkbjq6m:06843] *** Process received signal ***
[pkrvmpptgkbjq6m:06843] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06843] Signal code:  (-6)
[pkrvmpptgkbjq6m:06843] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7b28045330]
[pkrvmpptgkbjq6m:06843] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7b2809eb2c]
[pkrvmpptgkbjq6m:06843] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7b2804527e]
[pkrvmpptgkbjq6m:06843] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7b280288ff]
[pkrvmpptgkbjq6m:06843] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7b284a5ff5]
[pkrvmpptgkbjq6m:06843] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7b284bb0da]
[pkrvmpptgkbjq6m:06843] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7b284a5a55]
[pkrvmpptgkbjq6m:06843] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7b284a5a6f]
[pkrvmpptgkbjq6m:06843] [ 8] plumed_master(+0x146dd)[0x56470364e6dd]
[pkrvmpptgkbjq6m:06843] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7b2802a1ca]
[pkrvmpptgkbjq6m:06843] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7b2802a28b]
[pkrvmpptgkbjq6m:06843] [11] plumed_master(+0x15365)[0x56470364f365]
[pkrvmpptgkbjq6m:06843] *** End of error message ***
</pre>
{% endraw %}
