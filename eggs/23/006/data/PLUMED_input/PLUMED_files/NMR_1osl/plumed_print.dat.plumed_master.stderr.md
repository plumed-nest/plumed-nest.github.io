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
[pkrvmpptgkbjq6m:08037] *** Process received signal ***
[pkrvmpptgkbjq6m:08037] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08037] Signal code:  (-6)
[pkrvmpptgkbjq6m:08037] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa4ebc45330]
[pkrvmpptgkbjq6m:08037] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa4ebc9eb2c]
[pkrvmpptgkbjq6m:08037] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa4ebc4527e]
[pkrvmpptgkbjq6m:08037] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4ebc288ff]
[pkrvmpptgkbjq6m:08037] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4ec0a5ff5]
[pkrvmpptgkbjq6m:08037] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4ec0bb0da]
[pkrvmpptgkbjq6m:08037] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4ec0a5a55]
[pkrvmpptgkbjq6m:08037] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4ec0a5a6f]
[pkrvmpptgkbjq6m:08037] [ 8] plumed_master(+0x146dd)[0x5625168326dd]
[pkrvmpptgkbjq6m:08037] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa4ebc2a1ca]
[pkrvmpptgkbjq6m:08037] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa4ebc2a28b]
[pkrvmpptgkbjq6m:08037] [11] plumed_master(+0x15365)[0x562516833365]
[pkrvmpptgkbjq6m:08037] *** End of error message ***
</pre>
{% endraw %}
