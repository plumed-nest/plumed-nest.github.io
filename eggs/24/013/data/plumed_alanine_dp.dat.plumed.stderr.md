**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[runnervm76f27:06931] *** Process received signal ***
[runnervm76f27:06931] Signal: Aborted (6)
[runnervm76f27:06931] Signal code:  (-6)
[runnervm76f27:06931] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0097245330]
[runnervm76f27:06931] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f009729ec0c]
[runnervm76f27:06931] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f009724527e]
[runnervm76f27:06931] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f00972288ff]
[runnervm76f27:06931] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f00976a5ff5]
[runnervm76f27:06931] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f00976bb0da]
[runnervm76f27:06931] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f00976a5a55]
[runnervm76f27:06931] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f00976a5a6f]
[runnervm76f27:06931] [ 8] plumed(+0x146dd)[0x5598f2b696dd]
[runnervm76f27:06931] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f009722a1ca]
[runnervm76f27:06931] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f009722a28b]
[runnervm76f27:06931] [11] plumed(+0x15365)[0x5598f2b6a365]
[runnervm76f27:06931] *** End of error message ***
</pre>
{% endraw %}
