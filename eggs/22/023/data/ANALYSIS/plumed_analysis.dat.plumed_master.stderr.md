**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervm0kj6c:07613] *** Process received signal ***
[runnervm0kj6c:07613] Signal: Aborted (6)
[runnervm0kj6c:07613] Signal code:  (-6)
[runnervm0kj6c:07613] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e88645330]
[runnervm0kj6c:07613] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e8869eb2c]
[runnervm0kj6c:07613] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e8864527e]
[runnervm0kj6c:07613] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e886288ff]
[runnervm0kj6c:07613] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e88aa5ff5]
[runnervm0kj6c:07613] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e88abb0da]
[runnervm0kj6c:07613] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e88aa5a55]
[runnervm0kj6c:07613] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e88aa5a6f]
[runnervm0kj6c:07613] [ 8] plumed_master(+0x146dd)[0x55ec426566dd]
[runnervm0kj6c:07613] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e8862a1ca]
[runnervm0kj6c:07613] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e8862a28b]
[runnervm0kj6c:07613] [11] plumed_master(+0x15365)[0x55ec42657365]
[runnervm0kj6c:07613] *** End of error message ***
</pre>
{% endraw %}
