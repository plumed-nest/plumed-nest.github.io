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
[pkrvmbietmlfzoi:06617] *** Process received signal ***
[pkrvmbietmlfzoi:06617] Signal: Aborted (6)
[pkrvmbietmlfzoi:06617] Signal code:  (-6)
[pkrvmbietmlfzoi:06617] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f99fc845330]
[pkrvmbietmlfzoi:06617] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f99fc89eb2c]
[pkrvmbietmlfzoi:06617] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f99fc84527e]
[pkrvmbietmlfzoi:06617] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f99fc8288ff]
[pkrvmbietmlfzoi:06617] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f99fcca5ff5]
[pkrvmbietmlfzoi:06617] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f99fccbb0da]
[pkrvmbietmlfzoi:06617] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f99fcca5a55]
[pkrvmbietmlfzoi:06617] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f99fcca5a6f]
[pkrvmbietmlfzoi:06617] [ 8] plumed_master(+0x146dd)[0x56225df346dd]
[pkrvmbietmlfzoi:06617] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f99fc82a1ca]
[pkrvmbietmlfzoi:06617] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f99fc82a28b]
[pkrvmbietmlfzoi:06617] [11] plumed_master(+0x15365)[0x56225df35365]
[pkrvmbietmlfzoi:06617] *** End of error message ***
</pre>
{% endraw %}
