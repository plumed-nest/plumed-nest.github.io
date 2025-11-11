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
[runnervmw9dnm:09056] *** Process received signal ***
[runnervmw9dnm:09056] Signal: Aborted (6)
[runnervmw9dnm:09056] Signal code:  (-6)
[runnervmw9dnm:09056] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a24e45330]
[runnervmw9dnm:09056] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a24e9eb2c]
[runnervmw9dnm:09056] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a24e4527e]
[runnervmw9dnm:09056] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a24e288ff]
[runnervmw9dnm:09056] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a252a5ff5]
[runnervmw9dnm:09056] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a252bb0da]
[runnervmw9dnm:09056] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a252a5a55]
[runnervmw9dnm:09056] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a252a5a6f]
[runnervmw9dnm:09056] [ 8] plumed(+0x146dd)[0x55a9f38846dd]
[runnervmw9dnm:09056] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a24e2a1ca]
[runnervmw9dnm:09056] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a24e2a28b]
[runnervmw9dnm:09056] [11] plumed(+0x15365)[0x55a9f3885365]
[runnervmw9dnm:09056] *** End of error message ***
</pre>
{% endraw %}
