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
[pkrvmf6wy0o8zjz:65238] *** Process received signal ***
[pkrvmf6wy0o8zjz:65238] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:65238] Signal code:  (-6)
[pkrvmf6wy0o8zjz:65238] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff5b0245330]
[pkrvmf6wy0o8zjz:65238] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff5b029eb2c]
[pkrvmf6wy0o8zjz:65238] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff5b024527e]
[pkrvmf6wy0o8zjz:65238] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5b02288ff]
[pkrvmf6wy0o8zjz:65238] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5b06a5ff5]
[pkrvmf6wy0o8zjz:65238] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5b06bb0da]
[pkrvmf6wy0o8zjz:65238] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5b06a5a55]
[pkrvmf6wy0o8zjz:65238] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5b06a5a6f]
[pkrvmf6wy0o8zjz:65238] [ 8] plumed_master(+0x146dd)[0x564632f3e6dd]
[pkrvmf6wy0o8zjz:65238] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff5b022a1ca]
[pkrvmf6wy0o8zjz:65238] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff5b022a28b]
[pkrvmf6wy0o8zjz:65238] [11] plumed_master(+0x15365)[0x564632f3f365]
[pkrvmf6wy0o8zjz:65238] *** End of error message ***
</pre>
{% endraw %}
