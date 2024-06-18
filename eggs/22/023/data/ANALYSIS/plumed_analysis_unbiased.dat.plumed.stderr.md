**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az1435-511:05884] *** Process received signal ***
[fv-az1435-511:05884] Signal: Aborted (6)
[fv-az1435-511:05884] Signal code:  (-6)
[fv-az1435-511:05884] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0a36042520]
[fv-az1435-511:05884] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0a360969fc]
[fv-az1435-511:05884] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0a36042476]
[fv-az1435-511:05884] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0a360287f3]
[fv-az1435-511:05884] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0a364a2b9e]
[fv-az1435-511:05884] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0a364ae20c]
[fv-az1435-511:05884] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0a364ae277]
[fv-az1435-511:05884] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0a364ae52b]
[fv-az1435-511:05884] [ 8] plumed(+0x12f48)[0x559b95c24f48]
[fv-az1435-511:05884] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0a36029d90]
[fv-az1435-511:05884] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0a36029e40]
[fv-az1435-511:05884] [11] plumed(+0x131e5)[0x559b95c251e5]
[fv-az1435-511:05884] *** End of error message ***
</pre>
{% endraw %}
