**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervm0kj6c:07598] *** Process received signal ***
[runnervm0kj6c:07598] Signal: Aborted (6)
[runnervm0kj6c:07598] Signal code:  (-6)
[runnervm0kj6c:07598] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9af2045330]
[runnervm0kj6c:07598] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9af209eb2c]
[runnervm0kj6c:07598] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9af204527e]
[runnervm0kj6c:07598] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9af20288ff]
[runnervm0kj6c:07598] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9af24a5ff5]
[runnervm0kj6c:07598] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9af24bb0da]
[runnervm0kj6c:07598] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9af24a5a55]
[runnervm0kj6c:07598] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9af24a5a6f]
[runnervm0kj6c:07598] [ 8] plumed(+0x146dd)[0x563bdde0e6dd]
[runnervm0kj6c:07598] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9af202a1ca]
[runnervm0kj6c:07598] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9af202a28b]
[runnervm0kj6c:07598] [11] plumed(+0x15365)[0x563bdde0f365]
[runnervm0kj6c:07598] *** End of error message ***
</pre>
{% endraw %}
