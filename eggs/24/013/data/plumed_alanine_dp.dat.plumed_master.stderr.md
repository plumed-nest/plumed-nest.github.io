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
[fv-az807-718:61956] *** Process received signal ***
[fv-az807-718:61956] Signal: Aborted (6)
[fv-az807-718:61956] Signal code:  (-6)
[fv-az807-718:61956] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f934d845330]
[fv-az807-718:61956] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f934d89eb2c]
[fv-az807-718:61956] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f934d84527e]
[fv-az807-718:61956] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f934d8288ff]
[fv-az807-718:61956] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f934dca5ff5]
[fv-az807-718:61956] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f934dcbb0da]
[fv-az807-718:61956] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f934dca5a55]
[fv-az807-718:61956] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f934dca5a6f]
[fv-az807-718:61956] [ 8] plumed_master(+0x146dd)[0x55cee9e836dd]
[fv-az807-718:61956] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f934d82a1ca]
[fv-az807-718:61956] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f934d82a28b]
[fv-az807-718:61956] [11] plumed_master(+0x15365)[0x55cee9e84365]
[fv-az807-718:61956] *** End of error message ***
</pre>
{% endraw %}
