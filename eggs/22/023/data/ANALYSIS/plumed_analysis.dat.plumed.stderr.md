**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervm76f27:08499] *** Process received signal ***
[runnervm76f27:08499] Signal: Aborted (6)
[runnervm76f27:08499] Signal code:  (-6)
[runnervm76f27:08499] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd54a245330]
[runnervm76f27:08499] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd54a29ec0c]
[runnervm76f27:08499] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd54a24527e]
[runnervm76f27:08499] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd54a2288ff]
[runnervm76f27:08499] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd54a6a5ff5]
[runnervm76f27:08499] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd54a6bb0da]
[runnervm76f27:08499] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd54a6a5a55]
[runnervm76f27:08499] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd54a6a5a6f]
[runnervm76f27:08499] [ 8] plumed(+0x146dd)[0x5572a1e9e6dd]
[runnervm76f27:08499] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd54a22a1ca]
[runnervm76f27:08499] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd54a22a28b]
[runnervm76f27:08499] [11] plumed(+0x15365)[0x5572a1e9f365]
[runnervm76f27:08499] *** End of error message ***
</pre>
{% endraw %}
