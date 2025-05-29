**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvmf6wy0o8zjz:65294] *** Process received signal ***
[pkrvmf6wy0o8zjz:65294] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:65294] Signal code:  (-6)
[pkrvmf6wy0o8zjz:65294] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6c49045330]
[pkrvmf6wy0o8zjz:65294] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6c4909eb2c]
[pkrvmf6wy0o8zjz:65294] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6c4904527e]
[pkrvmf6wy0o8zjz:65294] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6c490288ff]
[pkrvmf6wy0o8zjz:65294] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6c494a5ff5]
[pkrvmf6wy0o8zjz:65294] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6c494bb0da]
[pkrvmf6wy0o8zjz:65294] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6c494a5a55]
[pkrvmf6wy0o8zjz:65294] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6c494a5a6f]
[pkrvmf6wy0o8zjz:65294] [ 8] plumed_master(+0x146dd)[0x55eea31236dd]
[pkrvmf6wy0o8zjz:65294] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6c4902a1ca]
[pkrvmf6wy0o8zjz:65294] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6c4902a28b]
[pkrvmf6wy0o8zjz:65294] [11] plumed_master(+0x15365)[0x55eea3124365]
[pkrvmf6wy0o8zjz:65294] *** End of error message ***
</pre>
{% endraw %}
