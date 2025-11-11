**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[runnervmw9dnm:06094] *** Process received signal ***
[runnervmw9dnm:06094] Signal: Aborted (6)
[runnervmw9dnm:06094] Signal code:  (-6)
[runnervmw9dnm:06094] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcb5e845330]
[runnervmw9dnm:06094] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcb5e89eb2c]
[runnervmw9dnm:06094] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcb5e84527e]
[runnervmw9dnm:06094] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcb5e8288ff]
[runnervmw9dnm:06094] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcb5eca5ff5]
[runnervmw9dnm:06094] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcb5ecbb0da]
[runnervmw9dnm:06094] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcb5eca5a55]
[runnervmw9dnm:06094] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcb5eca5a6f]
[runnervmw9dnm:06094] [ 8] plumed(+0x146dd)[0x563ec25106dd]
[runnervmw9dnm:06094] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcb5e82a1ca]
[runnervmw9dnm:06094] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcb5e82a28b]
[runnervmw9dnm:06094] [11] plumed(+0x15365)[0x563ec2511365]
[runnervmw9dnm:06094] *** End of error message ***
</pre>
{% endraw %}
