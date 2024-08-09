**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[fv-az1490-855:04044] *** Process received signal ***
[fv-az1490-855:04044] Signal: Aborted (6)
[fv-az1490-855:04044] Signal code:  (-6)
[fv-az1490-855:04044] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1850a42520]
[fv-az1490-855:04044] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1850a969fc]
[fv-az1490-855:04044] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1850a42476]
[fv-az1490-855:04044] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1850a287f3]
[fv-az1490-855:04044] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1850ea2b9e]
[fv-az1490-855:04044] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1850eae20c]
[fv-az1490-855:04044] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1850eae277]
[fv-az1490-855:04044] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1850eae52b]
[fv-az1490-855:04044] [ 8] plumed(+0x12f48)[0x560a48a4bf48]
[fv-az1490-855:04044] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1850a29d90]
[fv-az1490-855:04044] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1850a29e40]
[fv-az1490-855:04044] [11] plumed(+0x131e5)[0x560a48a4c1e5]
[fv-az1490-855:04044] *** End of error message ***
</pre>
{% endraw %}
