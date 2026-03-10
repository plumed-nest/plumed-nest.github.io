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
[runnervm0kj6c:04741] *** Process received signal ***
[runnervm0kj6c:04741] Signal: Aborted (6)
[runnervm0kj6c:04741] Signal code:  (-6)
[runnervm0kj6c:04741] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f892ea45330]
[runnervm0kj6c:04741] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f892ea9eb2c]
[runnervm0kj6c:04741] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f892ea4527e]
[runnervm0kj6c:04741] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f892ea288ff]
[runnervm0kj6c:04741] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f892eea5ff5]
[runnervm0kj6c:04741] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f892eebb0da]
[runnervm0kj6c:04741] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f892eea5a55]
[runnervm0kj6c:04741] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f892eea5a6f]
[runnervm0kj6c:04741] [ 8] plumed_master(+0x146dd)[0x560964ca86dd]
[runnervm0kj6c:04741] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f892ea2a1ca]
[runnervm0kj6c:04741] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f892ea2a28b]
[runnervm0kj6c:04741] [11] plumed_master(+0x15365)[0x560964ca9365]
[runnervm0kj6c:04741] *** End of error message ***
</pre>
{% endraw %}
