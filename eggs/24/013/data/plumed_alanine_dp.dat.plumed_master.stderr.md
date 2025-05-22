**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[pkrvmf6wy0o8zjz:35026] *** Process received signal ***
[pkrvmf6wy0o8zjz:35026] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:35026] Signal code:  (-6)
[pkrvmf6wy0o8zjz:35026] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2011645330]
[pkrvmf6wy0o8zjz:35026] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f201169eb2c]
[pkrvmf6wy0o8zjz:35026] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f201164527e]
[pkrvmf6wy0o8zjz:35026] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f20116288ff]
[pkrvmf6wy0o8zjz:35026] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2011aa5ff5]
[pkrvmf6wy0o8zjz:35026] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2011abb0da]
[pkrvmf6wy0o8zjz:35026] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2011aa5a55]
[pkrvmf6wy0o8zjz:35026] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2011aa5a6f]
[pkrvmf6wy0o8zjz:35026] [ 8] plumed_master(+0x146dd)[0x55a2c5caa6dd]
[pkrvmf6wy0o8zjz:35026] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f201162a1ca]
[pkrvmf6wy0o8zjz:35026] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f201162a28b]
[pkrvmf6wy0o8zjz:35026] [11] plumed_master(+0x15365)[0x55a2c5cab365]
[pkrvmf6wy0o8zjz:35026] *** End of error message ***
</pre>
{% endraw %}
