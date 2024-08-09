**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az840-554:05707] *** Process received signal ***
[fv-az840-554:05707] Signal: Aborted (6)
[fv-az840-554:05707] Signal code:  (-6)
[fv-az840-554:05707] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f81f2842520]
[fv-az840-554:05707] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f81f28969fc]
[fv-az840-554:05707] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f81f2842476]
[fv-az840-554:05707] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f81f28287f3]
[fv-az840-554:05707] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f81f2ca2b9e]
[fv-az840-554:05707] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f81f2cae20c]
[fv-az840-554:05707] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f81f2cae277]
[fv-az840-554:05707] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f81f2cae52b]
[fv-az840-554:05707] [ 8] plumed_master(+0x14274)[0x55c4e97d4274]
[fv-az840-554:05707] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f81f2829d90]
[fv-az840-554:05707] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f81f2829e40]
[fv-az840-554:05707] [11] plumed_master(+0x14ed5)[0x55c4e97d4ed5]
[fv-az840-554:05707] *** End of error message ***
</pre>
{% endraw %}
