**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az1435-511:05892] *** Process received signal ***
[fv-az1435-511:05892] Signal: Aborted (6)
[fv-az1435-511:05892] Signal code:  (-6)
[fv-az1435-511:05892] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff864c42520]
[fv-az1435-511:05892] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff864c969fc]
[fv-az1435-511:05892] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff864c42476]
[fv-az1435-511:05892] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff864c287f3]
[fv-az1435-511:05892] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff8650a2b9e]
[fv-az1435-511:05892] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff8650ae20c]
[fv-az1435-511:05892] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff8650ae277]
[fv-az1435-511:05892] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff8650ae52b]
[fv-az1435-511:05892] [ 8] plumed_master(+0x14274)[0x562a4f6c2274]
[fv-az1435-511:05892] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff864c29d90]
[fv-az1435-511:05892] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff864c29e40]
[fv-az1435-511:05892] [11] plumed_master(+0x14ed5)[0x562a4f6c2ed5]
[fv-az1435-511:05892] *** End of error message ***
</pre>
{% endraw %}
