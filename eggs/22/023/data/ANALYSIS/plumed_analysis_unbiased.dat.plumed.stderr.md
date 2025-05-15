**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvmberfyhpb9w:08201] *** Process received signal ***
[pkrvmberfyhpb9w:08201] Signal: Aborted (6)
[pkrvmberfyhpb9w:08201] Signal code:  (-6)
[pkrvmberfyhpb9w:08201] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d7de45330]
[pkrvmberfyhpb9w:08201] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d7de9eb2c]
[pkrvmberfyhpb9w:08201] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d7de4527e]
[pkrvmberfyhpb9w:08201] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d7de288ff]
[pkrvmberfyhpb9w:08201] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d7e2a5ff5]
[pkrvmberfyhpb9w:08201] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d7e2bb0da]
[pkrvmberfyhpb9w:08201] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d7e2a5a55]
[pkrvmberfyhpb9w:08201] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d7e2a5a6f]
[pkrvmberfyhpb9w:08201] [ 8] plumed(+0x146dd)[0x55787e13f6dd]
[pkrvmberfyhpb9w:08201] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d7de2a1ca]
[pkrvmberfyhpb9w:08201] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d7de2a28b]
[pkrvmberfyhpb9w:08201] [11] plumed(+0x15365)[0x55787e140365]
[pkrvmberfyhpb9w:08201] *** End of error message ***
</pre>
{% endraw %}
