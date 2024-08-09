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
[fv-az1490-855:04052] *** Process received signal ***
[fv-az1490-855:04052] Signal: Aborted (6)
[fv-az1490-855:04052] Signal code:  (-6)
[fv-az1490-855:04052] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f15c3442520]
[fv-az1490-855:04052] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f15c34969fc]
[fv-az1490-855:04052] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f15c3442476]
[fv-az1490-855:04052] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f15c34287f3]
[fv-az1490-855:04052] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f15c38a2b9e]
[fv-az1490-855:04052] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f15c38ae20c]
[fv-az1490-855:04052] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f15c38ae277]
[fv-az1490-855:04052] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f15c38ae52b]
[fv-az1490-855:04052] [ 8] plumed_master(+0x14274)[0x564f3bbf2274]
[fv-az1490-855:04052] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f15c3429d90]
[fv-az1490-855:04052] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f15c3429e40]
[fv-az1490-855:04052] [11] plumed_master(+0x14ed5)[0x564f3bbf2ed5]
[fv-az1490-855:04052] *** End of error message ***
</pre>
{% endraw %}
