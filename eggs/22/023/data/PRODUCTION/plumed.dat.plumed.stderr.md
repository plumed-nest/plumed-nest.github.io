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
[fv-az805-507:11435] *** Process received signal ***
[fv-az805-507:11435] Signal: Aborted (6)
[fv-az805-507:11435] Signal code:  (-6)
[fv-az805-507:11435] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f35df845330]
[fv-az805-507:11435] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f35df89eb2c]
[fv-az805-507:11435] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f35df84527e]
[fv-az805-507:11435] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f35df8288ff]
[fv-az805-507:11435] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f35dfca5ff5]
[fv-az805-507:11435] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f35dfcbb0da]
[fv-az805-507:11435] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f35dfca5a55]
[fv-az805-507:11435] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f35dfca5a6f]
[fv-az805-507:11435] [ 8] plumed(+0x146dd)[0x55b1face26dd]
[fv-az805-507:11435] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f35df82a1ca]
[fv-az805-507:11435] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f35df82a28b]
[fv-az805-507:11435] [11] plumed(+0x15365)[0x55b1face3365]
[fv-az805-507:11435] *** End of error message ***
</pre>
{% endraw %}
