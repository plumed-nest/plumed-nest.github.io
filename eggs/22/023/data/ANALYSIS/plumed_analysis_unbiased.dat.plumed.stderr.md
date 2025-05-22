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
[pkrvmf6wy0o8zjz:35743] *** Process received signal ***
[pkrvmf6wy0o8zjz:35743] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:35743] Signal code:  (-6)
[pkrvmf6wy0o8zjz:35743] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc9d8245330]
[pkrvmf6wy0o8zjz:35743] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc9d829eb2c]
[pkrvmf6wy0o8zjz:35743] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc9d824527e]
[pkrvmf6wy0o8zjz:35743] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc9d82288ff]
[pkrvmf6wy0o8zjz:35743] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc9d86a5ff5]
[pkrvmf6wy0o8zjz:35743] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc9d86bb0da]
[pkrvmf6wy0o8zjz:35743] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc9d86a5a55]
[pkrvmf6wy0o8zjz:35743] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc9d86a5a6f]
[pkrvmf6wy0o8zjz:35743] [ 8] plumed(+0x146dd)[0x558678d2d6dd]
[pkrvmf6wy0o8zjz:35743] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc9d822a1ca]
[pkrvmf6wy0o8zjz:35743] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc9d822a28b]
[pkrvmf6wy0o8zjz:35743] [11] plumed(+0x15365)[0x558678d2e365]
[pkrvmf6wy0o8zjz:35743] *** End of error message ***
</pre>
{% endraw %}
