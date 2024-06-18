**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[fv-az1771-923:04149] *** Process received signal ***
[fv-az1771-923:04149] Signal: Aborted (6)
[fv-az1771-923:04149] Signal code:  (-6)
[fv-az1771-923:04149] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5b45642520]
[fv-az1771-923:04149] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5b456969fc]
[fv-az1771-923:04149] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5b45642476]
[fv-az1771-923:04149] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5b456287f3]
[fv-az1771-923:04149] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5b45aa2b9e]
[fv-az1771-923:04149] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5b45aae20c]
[fv-az1771-923:04149] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5b45aae277]
[fv-az1771-923:04149] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5b45aae52b]
[fv-az1771-923:04149] [ 8] plumed_master(+0x14274)[0x557b99360274]
[fv-az1771-923:04149] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5b45629d90]
[fv-az1771-923:04149] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5b45629e40]
[fv-az1771-923:04149] [11] plumed_master(+0x14ed5)[0x557b99360ed5]
[fv-az1771-923:04149] *** End of error message ***
</pre>
{% endraw %}
