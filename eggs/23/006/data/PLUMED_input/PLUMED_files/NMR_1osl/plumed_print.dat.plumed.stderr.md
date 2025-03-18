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
[fv-az1267-279:63341] *** Process received signal ***
[fv-az1267-279:63341] Signal: Aborted (6)
[fv-az1267-279:63341] Signal code:  (-6)
[fv-az1267-279:63341] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff4a7045330]
[fv-az1267-279:63341] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff4a709eb2c]
[fv-az1267-279:63341] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff4a704527e]
[fv-az1267-279:63341] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff4a70288ff]
[fv-az1267-279:63341] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff4a74a5ff5]
[fv-az1267-279:63341] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff4a74bb0da]
[fv-az1267-279:63341] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff4a74a5a55]
[fv-az1267-279:63341] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff4a74a5a6f]
[fv-az1267-279:63341] [ 8] plumed(+0x146dd)[0x55be6a0f96dd]
[fv-az1267-279:63341] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff4a702a1ca]
[fv-az1267-279:63341] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff4a702a28b]
[fv-az1267-279:63341] [11] plumed(+0x15365)[0x55be6a0fa365]
[fv-az1267-279:63341] *** End of error message ***
</pre>
{% endraw %}
