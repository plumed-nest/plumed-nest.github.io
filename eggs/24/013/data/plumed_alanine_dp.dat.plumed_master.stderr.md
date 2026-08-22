**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[runnervm76f27:06947] *** Process received signal ***
[runnervm76f27:06947] Signal: Aborted (6)
[runnervm76f27:06947] Signal code:  (-6)
[runnervm76f27:06947] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f609d445330]
[runnervm76f27:06947] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f609d49ec0c]
[runnervm76f27:06947] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f609d44527e]
[runnervm76f27:06947] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f609d4288ff]
[runnervm76f27:06947] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f609d8a5ff5]
[runnervm76f27:06947] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f609d8bb0da]
[runnervm76f27:06947] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f609d8a5a55]
[runnervm76f27:06947] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f609d8a5a6f]
[runnervm76f27:06947] [ 8] plumed_master(+0x146dd)[0x55bce01766dd]
[runnervm76f27:06947] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f609d42a1ca]
[runnervm76f27:06947] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f609d42a28b]
[runnervm76f27:06947] [11] plumed_master(+0x15365)[0x55bce0177365]
[runnervm76f27:06947] *** End of error message ***
</pre>
{% endraw %}
