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
[pkrvm7jw40e0xgp:06985] *** Process received signal ***
[pkrvm7jw40e0xgp:06985] Signal: Aborted (6)
[pkrvm7jw40e0xgp:06985] Signal code:  (-6)
[pkrvm7jw40e0xgp:06985] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f97f9e45330]
[pkrvm7jw40e0xgp:06985] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f97f9e9eb2c]
[pkrvm7jw40e0xgp:06985] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f97f9e4527e]
[pkrvm7jw40e0xgp:06985] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97f9e288ff]
[pkrvm7jw40e0xgp:06985] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f97fa2a5ff5]
[pkrvm7jw40e0xgp:06985] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f97fa2bb0da]
[pkrvm7jw40e0xgp:06985] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f97fa2a5a55]
[pkrvm7jw40e0xgp:06985] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f97fa2a5a6f]
[pkrvm7jw40e0xgp:06985] [ 8] plumed(+0x146dd)[0x5619b97b96dd]
[pkrvm7jw40e0xgp:06985] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f97f9e2a1ca]
[pkrvm7jw40e0xgp:06985] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f97f9e2a28b]
[pkrvm7jw40e0xgp:06985] [11] plumed(+0x15365)[0x5619b97ba365]
[pkrvm7jw40e0xgp:06985] *** End of error message ***
</pre>
{% endraw %}
