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
[fv-az1390-170:07348] *** Process received signal ***
[fv-az1390-170:07348] Signal: Aborted (6)
[fv-az1390-170:07348] Signal code:  (-6)
[fv-az1390-170:07348] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb4eb845330]
[fv-az1390-170:07348] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb4eb89eb2c]
[fv-az1390-170:07348] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb4eb84527e]
[fv-az1390-170:07348] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4eb8288ff]
[fv-az1390-170:07348] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4ebca5ff5]
[fv-az1390-170:07348] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4ebcbb0da]
[fv-az1390-170:07348] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4ebca5a55]
[fv-az1390-170:07348] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4ebca5a6f]
[fv-az1390-170:07348] [ 8] plumed(+0x146dd)[0x55fa7626e6dd]
[fv-az1390-170:07348] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb4eb82a1ca]
[fv-az1390-170:07348] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb4eb82a28b]
[fv-az1390-170:07348] [11] plumed(+0x15365)[0x55fa7626f365]
[fv-az1390-170:07348] *** End of error message ***
</pre>
{% endraw %}
