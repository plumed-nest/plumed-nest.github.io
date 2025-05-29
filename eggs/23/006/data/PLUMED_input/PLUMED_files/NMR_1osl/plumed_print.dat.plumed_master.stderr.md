**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[pkrvmf6wy0o8zjz:63832] *** Process received signal ***
[pkrvmf6wy0o8zjz:63832] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:63832] Signal code:  (-6)
[pkrvmf6wy0o8zjz:63832] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f59fa445330]
[pkrvmf6wy0o8zjz:63832] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f59fa49eb2c]
[pkrvmf6wy0o8zjz:63832] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f59fa44527e]
[pkrvmf6wy0o8zjz:63832] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f59fa4288ff]
[pkrvmf6wy0o8zjz:63832] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f59fa8a5ff5]
[pkrvmf6wy0o8zjz:63832] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f59fa8bb0da]
[pkrvmf6wy0o8zjz:63832] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f59fa8a5a55]
[pkrvmf6wy0o8zjz:63832] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f59fa8a5a6f]
[pkrvmf6wy0o8zjz:63832] [ 8] plumed_master(+0x146dd)[0x5607f3d766dd]
[pkrvmf6wy0o8zjz:63832] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f59fa42a1ca]
[pkrvmf6wy0o8zjz:63832] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f59fa42a28b]
[pkrvmf6wy0o8zjz:63832] [11] plumed_master(+0x15365)[0x5607f3d77365]
[pkrvmf6wy0o8zjz:63832] *** End of error message ***
</pre>
{% endraw %}
