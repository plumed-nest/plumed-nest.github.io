**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[fv-az1267-279:63289] *** Process received signal ***
[fv-az1267-279:63289] Signal: Aborted (6)
[fv-az1267-279:63289] Signal code:  (-6)
[fv-az1267-279:63289] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f01a45330]
[fv-az1267-279:63289] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f01a9eb2c]
[fv-az1267-279:63289] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f01a4527e]
[fv-az1267-279:63289] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f01a288ff]
[fv-az1267-279:63289] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f01ea5ff5]
[fv-az1267-279:63289] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f01ebb0da]
[fv-az1267-279:63289] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f01ea5a55]
[fv-az1267-279:63289] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f01ea5a6f]
[fv-az1267-279:63289] [ 8] plumed(+0x146dd)[0x5632914796dd]
[fv-az1267-279:63289] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f01a2a1ca]
[fv-az1267-279:63289] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f01a2a28b]
[fv-az1267-279:63289] [11] plumed(+0x15365)[0x56329147a365]
[fv-az1267-279:63289] *** End of error message ***
</pre>
{% endraw %}
