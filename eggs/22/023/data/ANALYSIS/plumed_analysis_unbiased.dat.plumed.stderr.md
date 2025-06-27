**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvmbietmlfzoi:65379] *** Process received signal ***
[pkrvmbietmlfzoi:65379] Signal: Aborted (6)
[pkrvmbietmlfzoi:65379] Signal code:  (-6)
[pkrvmbietmlfzoi:65379] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8131c45330]
[pkrvmbietmlfzoi:65379] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8131c9eb2c]
[pkrvmbietmlfzoi:65379] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8131c4527e]
[pkrvmbietmlfzoi:65379] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8131c288ff]
[pkrvmbietmlfzoi:65379] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f81320a5ff5]
[pkrvmbietmlfzoi:65379] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f81320bb0da]
[pkrvmbietmlfzoi:65379] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f81320a5a55]
[pkrvmbietmlfzoi:65379] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f81320a5a6f]
[pkrvmbietmlfzoi:65379] [ 8] plumed(+0x146dd)[0x556b971af6dd]
[pkrvmbietmlfzoi:65379] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8131c2a1ca]
[pkrvmbietmlfzoi:65379] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8131c2a28b]
[pkrvmbietmlfzoi:65379] [11] plumed(+0x15365)[0x556b971b0365]
[pkrvmbietmlfzoi:65379] *** End of error message ***
</pre>
{% endraw %}
