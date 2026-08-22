**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervm76f27:08566] *** Process received signal ***
[runnervm76f27:08566] Signal: Aborted (6)
[runnervm76f27:08566] Signal code:  (-6)
[runnervm76f27:08566] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f777e845330]
[runnervm76f27:08566] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f777e89ec0c]
[runnervm76f27:08566] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f777e84527e]
[runnervm76f27:08566] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f777e8288ff]
[runnervm76f27:08566] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f777eca5ff5]
[runnervm76f27:08566] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f777ecbb0da]
[runnervm76f27:08566] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f777eca5a55]
[runnervm76f27:08566] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f777eca5a6f]
[runnervm76f27:08566] [ 8] plumed_master(+0x146dd)[0x5640c30bb6dd]
[runnervm76f27:08566] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f777e82a1ca]
[runnervm76f27:08566] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f777e82a28b]
[runnervm76f27:08566] [11] plumed_master(+0x15365)[0x5640c30bc365]
[runnervm76f27:08566] *** End of error message ***
</pre>
{% endraw %}
