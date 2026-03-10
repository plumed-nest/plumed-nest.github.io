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
[runnervm0kj6c:04726] *** Process received signal ***
[runnervm0kj6c:04726] Signal: Aborted (6)
[runnervm0kj6c:04726] Signal code:  (-6)
[runnervm0kj6c:04726] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f12da445330]
[runnervm0kj6c:04726] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f12da49eb2c]
[runnervm0kj6c:04726] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f12da44527e]
[runnervm0kj6c:04726] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f12da4288ff]
[runnervm0kj6c:04726] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12da8a5ff5]
[runnervm0kj6c:04726] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12da8bb0da]
[runnervm0kj6c:04726] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12da8a5a55]
[runnervm0kj6c:04726] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12da8a5a6f]
[runnervm0kj6c:04726] [ 8] plumed(+0x146dd)[0x56400a42a6dd]
[runnervm0kj6c:04726] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f12da42a1ca]
[runnervm0kj6c:04726] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f12da42a28b]
[runnervm0kj6c:04726] [11] plumed(+0x15365)[0x56400a42b365]
[runnervm0kj6c:04726] *** End of error message ***
</pre>
{% endraw %}
