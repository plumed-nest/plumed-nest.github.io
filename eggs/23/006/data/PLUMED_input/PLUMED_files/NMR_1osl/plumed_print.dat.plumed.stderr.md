**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[pkrvmpptgkbjq6m:08021] *** Process received signal ***
[pkrvmpptgkbjq6m:08021] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08021] Signal code:  (-6)
[pkrvmpptgkbjq6m:08021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3831a45330]
[pkrvmpptgkbjq6m:08021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3831a9eb2c]
[pkrvmpptgkbjq6m:08021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3831a4527e]
[pkrvmpptgkbjq6m:08021] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3831a288ff]
[pkrvmpptgkbjq6m:08021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3831ea5ff5]
[pkrvmpptgkbjq6m:08021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3831ebb0da]
[pkrvmpptgkbjq6m:08021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3831ea5a55]
[pkrvmpptgkbjq6m:08021] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3831ea5a6f]
[pkrvmpptgkbjq6m:08021] [ 8] plumed(+0x146dd)[0x5617fee466dd]
[pkrvmpptgkbjq6m:08021] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3831a2a1ca]
[pkrvmpptgkbjq6m:08021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3831a2a28b]
[pkrvmpptgkbjq6m:08021] [11] plumed(+0x15365)[0x5617fee47365]
[pkrvmpptgkbjq6m:08021] *** End of error message ***
</pre>
{% endraw %}
