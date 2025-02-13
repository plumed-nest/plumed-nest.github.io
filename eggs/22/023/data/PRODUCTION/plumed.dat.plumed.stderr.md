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
[fv-az1390-170:09380] *** Process received signal ***
[fv-az1390-170:09380] Signal: Aborted (6)
[fv-az1390-170:09380] Signal code:  (-6)
[fv-az1390-170:09380] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa79645330]
[fv-az1390-170:09380] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa7969eb2c]
[fv-az1390-170:09380] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa7964527e]
[fv-az1390-170:09380] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa796288ff]
[fv-az1390-170:09380] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa79aa5ff5]
[fv-az1390-170:09380] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa79abb0da]
[fv-az1390-170:09380] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa79aa5a55]
[fv-az1390-170:09380] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa79aa5a6f]
[fv-az1390-170:09380] [ 8] plumed(+0x146dd)[0x55801a6816dd]
[fv-az1390-170:09380] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa7962a1ca]
[fv-az1390-170:09380] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa7962a28b]
[fv-az1390-170:09380] [11] plumed(+0x15365)[0x55801a682365]
[fv-az1390-170:09380] *** End of error message ***
</pre>
{% endraw %}
