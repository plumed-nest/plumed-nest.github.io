**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[fv-az1360-658:06281] *** Process received signal ***
[fv-az1360-658:06281] Signal: Aborted (6)
[fv-az1360-658:06281] Signal code:  (-6)
[fv-az1360-658:06281] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3820a45330]
[fv-az1360-658:06281] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3820a9eb2c]
[fv-az1360-658:06281] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3820a4527e]
[fv-az1360-658:06281] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3820a288ff]
[fv-az1360-658:06281] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3820ea5ff5]
[fv-az1360-658:06281] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3820ebb0da]
[fv-az1360-658:06281] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3820ea5a55]
[fv-az1360-658:06281] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3820ea5a6f]
[fv-az1360-658:06281] [ 8] plumed(+0x146dd)[0x55da93ceb6dd]
[fv-az1360-658:06281] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3820a2a1ca]
[fv-az1360-658:06281] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3820a2a28b]
[fv-az1360-658:06281] [11] plumed(+0x15365)[0x55da93cec365]
[fv-az1360-658:06281] *** End of error message ***
</pre>
{% endraw %}
