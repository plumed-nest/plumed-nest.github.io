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
[pkrvmq0rgcvqdmg:06992] *** Process received signal ***
[pkrvmq0rgcvqdmg:06992] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06992] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06992] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0201c45330]
[pkrvmq0rgcvqdmg:06992] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0201c9eb2c]
[pkrvmq0rgcvqdmg:06992] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0201c4527e]
[pkrvmq0rgcvqdmg:06992] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0201c288ff]
[pkrvmq0rgcvqdmg:06992] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f02020a5ff5]
[pkrvmq0rgcvqdmg:06992] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f02020bb0da]
[pkrvmq0rgcvqdmg:06992] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f02020a5a55]
[pkrvmq0rgcvqdmg:06992] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f02020a5a6f]
[pkrvmq0rgcvqdmg:06992] [ 8] plumed(+0x146dd)[0x560d0f43e6dd]
[pkrvmq0rgcvqdmg:06992] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0201c2a1ca]
[pkrvmq0rgcvqdmg:06992] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0201c2a28b]
[pkrvmq0rgcvqdmg:06992] [11] plumed(+0x15365)[0x560d0f43f365]
[pkrvmq0rgcvqdmg:06992] *** End of error message ***
</pre>
{% endraw %}
