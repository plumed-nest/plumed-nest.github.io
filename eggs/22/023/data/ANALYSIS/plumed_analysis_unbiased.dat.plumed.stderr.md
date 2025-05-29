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
[pkrvmf6wy0o8zjz:65278] *** Process received signal ***
[pkrvmf6wy0o8zjz:65278] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:65278] Signal code:  (-6)
[pkrvmf6wy0o8zjz:65278] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f468bc45330]
[pkrvmf6wy0o8zjz:65278] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f468bc9eb2c]
[pkrvmf6wy0o8zjz:65278] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f468bc4527e]
[pkrvmf6wy0o8zjz:65278] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f468bc288ff]
[pkrvmf6wy0o8zjz:65278] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f468c0a5ff5]
[pkrvmf6wy0o8zjz:65278] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f468c0bb0da]
[pkrvmf6wy0o8zjz:65278] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f468c0a5a55]
[pkrvmf6wy0o8zjz:65278] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f468c0a5a6f]
[pkrvmf6wy0o8zjz:65278] [ 8] plumed(+0x146dd)[0x55d93b1456dd]
[pkrvmf6wy0o8zjz:65278] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f468bc2a1ca]
[pkrvmf6wy0o8zjz:65278] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f468bc2a28b]
[pkrvmf6wy0o8zjz:65278] [11] plumed(+0x15365)[0x55d93b146365]
[pkrvmf6wy0o8zjz:65278] *** End of error message ***
</pre>
{% endraw %}
