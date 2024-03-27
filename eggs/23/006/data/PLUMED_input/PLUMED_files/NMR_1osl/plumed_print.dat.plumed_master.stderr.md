**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[fv-az1210-136:68044] *** Process received signal ***
[fv-az1210-136:68044] Signal: Aborted (6)
[fv-az1210-136:68044] Signal code:  (-6)
[fv-az1210-136:68044] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa8d3842520]
[fv-az1210-136:68044] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa8d38969fc]
[fv-az1210-136:68044] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa8d3842476]
[fv-az1210-136:68044] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa8d38287f3]
[fv-az1210-136:68044] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fa8d3ca4f26]
[fv-az1210-136:68044] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fa8d3cb6d9c]
[fv-az1210-136:68044] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fa8d3cb6e07]
[fv-az1210-136:68044] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa8d3cb70bb]
[fv-az1210-136:68044] [ 8] plumed_master(+0x12e7f)[0x55e218637e7f]
[fv-az1210-136:68044] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa8d3829d90]
[fv-az1210-136:68044] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa8d3829e40]
[fv-az1210-136:68044] [11] plumed_master(+0x13115)[0x55e218638115]
[fv-az1210-136:68044] *** End of error message ***
</pre>
{% endraw %}
