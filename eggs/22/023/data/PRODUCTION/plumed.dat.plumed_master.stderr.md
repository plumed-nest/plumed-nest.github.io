**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[fv-az805-507:11451] *** Process received signal ***
[fv-az805-507:11451] Signal: Aborted (6)
[fv-az805-507:11451] Signal code:  (-6)
[fv-az805-507:11451] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b32645330]
[fv-az805-507:11451] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b3269eb2c]
[fv-az805-507:11451] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b3264527e]
[fv-az805-507:11451] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b326288ff]
[fv-az805-507:11451] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b32aa5ff5]
[fv-az805-507:11451] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b32abb0da]
[fv-az805-507:11451] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b32aa5a55]
[fv-az805-507:11451] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b32aa5a6f]
[fv-az805-507:11451] [ 8] plumed_master(+0x146dd)[0x559000bbd6dd]
[fv-az805-507:11451] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b3262a1ca]
[fv-az805-507:11451] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b3262a28b]
[fv-az805-507:11451] [11] plumed_master(+0x15365)[0x559000bbe365]
[fv-az805-507:11451] *** End of error message ***
</pre>
{% endraw %}
