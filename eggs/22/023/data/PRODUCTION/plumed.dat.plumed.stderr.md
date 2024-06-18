**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[fv-az1435-511:05916] *** Process received signal ***
[fv-az1435-511:05916] Signal: Aborted (6)
[fv-az1435-511:05916] Signal code:  (-6)
[fv-az1435-511:05916] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f81ff642520]
[fv-az1435-511:05916] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f81ff6969fc]
[fv-az1435-511:05916] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f81ff642476]
[fv-az1435-511:05916] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f81ff6287f3]
[fv-az1435-511:05916] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f81ffaa2b9e]
[fv-az1435-511:05916] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f81ffaae20c]
[fv-az1435-511:05916] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f81ffaae277]
[fv-az1435-511:05916] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f81ffaae52b]
[fv-az1435-511:05916] [ 8] plumed(+0x12f48)[0x5565ac8e6f48]
[fv-az1435-511:05916] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f81ff629d90]
[fv-az1435-511:05916] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f81ff629e40]
[fv-az1435-511:05916] [11] plumed(+0x131e5)[0x5565ac8e71e5]
[fv-az1435-511:05916] *** End of error message ***
</pre>
{% endraw %}
