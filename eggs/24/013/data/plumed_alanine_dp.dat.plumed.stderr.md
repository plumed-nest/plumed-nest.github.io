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
[fv-az801-114:05025] *** Process received signal ***
[fv-az801-114:05025] Signal: Aborted (6)
[fv-az801-114:05025] Signal code:  (-6)
[fv-az801-114:05025] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9b49c42520]
[fv-az801-114:05025] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9b49c969fc]
[fv-az801-114:05025] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9b49c42476]
[fv-az801-114:05025] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9b49c287f3]
[fv-az801-114:05025] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9b4a0a2b9e]
[fv-az801-114:05025] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9b4a0ae20c]
[fv-az801-114:05025] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9b4a0ae277]
[fv-az801-114:05025] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9b4a0ae52b]
[fv-az801-114:05025] [ 8] plumed(+0x14254)[0x55c80c0ac254]
[fv-az801-114:05025] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9b49c29d90]
[fv-az801-114:05025] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9b49c29e40]
[fv-az801-114:05025] [11] plumed(+0x14eb5)[0x55c80c0aceb5]
[fv-az801-114:05025] *** End of error message ***
</pre>
{% endraw %}
