**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[fv-az1719-82:63535] *** Process received signal ***
[fv-az1719-82:63535] Signal: Aborted (6)
[fv-az1719-82:63535] Signal code:  (-6)
[fv-az1719-82:63535] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5670a45330]
[fv-az1719-82:63535] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5670a9eb2c]
[fv-az1719-82:63535] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5670a4527e]
[fv-az1719-82:63535] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5670a288ff]
[fv-az1719-82:63535] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5670ea5ff5]
[fv-az1719-82:63535] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5670ebb0da]
[fv-az1719-82:63535] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5670ea5a55]
[fv-az1719-82:63535] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5670ea5a6f]
[fv-az1719-82:63535] [ 8] plumed(+0x146dd)[0x5591c78df6dd]
[fv-az1719-82:63535] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5670a2a1ca]
[fv-az1719-82:63535] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5670a2a28b]
[fv-az1719-82:63535] [11] plumed(+0x15365)[0x5591c78e0365]
[fv-az1719-82:63535] *** End of error message ***
</pre>
{% endraw %}
