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
[fv-az1046-619:07063] *** Process received signal ***
[fv-az1046-619:07063] Signal: Aborted (6)
[fv-az1046-619:07063] Signal code:  (-6)
[fv-az1046-619:07063] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb89b645330]
[fv-az1046-619:07063] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb89b69eb2c]
[fv-az1046-619:07063] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb89b64527e]
[fv-az1046-619:07063] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb89b6288ff]
[fv-az1046-619:07063] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb89baa5ff5]
[fv-az1046-619:07063] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb89babb0da]
[fv-az1046-619:07063] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb89baa5a55]
[fv-az1046-619:07063] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb89baa5a6f]
[fv-az1046-619:07063] [ 8] plumed_master(+0x146dd)[0x5620102a36dd]
[fv-az1046-619:07063] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb89b62a1ca]
[fv-az1046-619:07063] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb89b62a28b]
[fv-az1046-619:07063] [11] plumed_master(+0x15365)[0x5620102a4365]
[fv-az1046-619:07063] *** End of error message ***
</pre>
{% endraw %}
