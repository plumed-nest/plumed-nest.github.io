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
[fv-az1771-923:04140] *** Process received signal ***
[fv-az1771-923:04140] Signal: Aborted (6)
[fv-az1771-923:04140] Signal code:  (-6)
[fv-az1771-923:04140] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6480442520]
[fv-az1771-923:04140] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f64804969fc]
[fv-az1771-923:04140] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6480442476]
[fv-az1771-923:04140] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f64804287f3]
[fv-az1771-923:04140] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f64808a2b9e]
[fv-az1771-923:04140] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f64808ae20c]
[fv-az1771-923:04140] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f64808ae277]
[fv-az1771-923:04140] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f64808ae52b]
[fv-az1771-923:04140] [ 8] plumed(+0x12f48)[0x55b62ad7df48]
[fv-az1771-923:04140] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6480429d90]
[fv-az1771-923:04140] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6480429e40]
[fv-az1771-923:04140] [11] plumed(+0x131e5)[0x55b62ad7e1e5]
[fv-az1771-923:04140] *** End of error message ***
</pre>
{% endraw %}
