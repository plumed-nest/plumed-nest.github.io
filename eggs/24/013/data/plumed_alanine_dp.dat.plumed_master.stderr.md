**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[fv-az1983-395:61000] *** Process received signal ***
[fv-az1983-395:61000] Signal: Aborted (6)
[fv-az1983-395:61000] Signal code:  (-6)
[fv-az1983-395:61000] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad3b845330]
[fv-az1983-395:61000] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad3b89eb2c]
[fv-az1983-395:61000] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad3b84527e]
[fv-az1983-395:61000] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad3b8288ff]
[fv-az1983-395:61000] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad3bca5ff5]
[fv-az1983-395:61000] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad3bcbb0da]
[fv-az1983-395:61000] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad3bca5a55]
[fv-az1983-395:61000] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad3bca5a6f]
[fv-az1983-395:61000] [ 8] plumed_master(+0x146dd)[0x55f4576716dd]
[fv-az1983-395:61000] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad3b82a1ca]
[fv-az1983-395:61000] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad3b82a28b]
[fv-az1983-395:61000] [11] plumed_master(+0x15365)[0x55f457672365]
[fv-az1983-395:61000] *** End of error message ***
</pre>
{% endraw %}
