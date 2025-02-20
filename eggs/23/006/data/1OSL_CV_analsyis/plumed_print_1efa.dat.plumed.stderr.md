**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1efa.dat   
Download: [zipped raw stdout](plumed_print_1efa.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1efa.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_noTet_99sbws_proc_mod_resID.pdb
[fv-az816-356:07231] *** Process received signal ***
[fv-az816-356:07231] Signal: Aborted (6)
[fv-az816-356:07231] Signal code:  (-6)
[fv-az816-356:07231] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f90c9e45330]
[fv-az816-356:07231] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f90c9e9eb2c]
[fv-az816-356:07231] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f90c9e4527e]
[fv-az816-356:07231] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f90c9e288ff]
[fv-az816-356:07231] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f90ca2a5ff5]
[fv-az816-356:07231] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f90ca2bb0da]
[fv-az816-356:07231] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f90ca2a5a55]
[fv-az816-356:07231] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f90ca2a5a6f]
[fv-az816-356:07231] [ 8] plumed(+0x146dd)[0x5637c7db26dd]
[fv-az816-356:07231] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f90c9e2a1ca]
[fv-az816-356:07231] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f90c9e2a28b]
[fv-az816-356:07231] [11] plumed(+0x15365)[0x5637c7db3365]
[fv-az816-356:07231] *** End of error message ***
</pre>
{% endraw %}
