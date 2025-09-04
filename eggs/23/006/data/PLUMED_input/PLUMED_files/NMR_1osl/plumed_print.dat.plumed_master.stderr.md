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
[pkrvm7jw40e0xgp:07000] *** Process received signal ***
[pkrvm7jw40e0xgp:07000] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07000] Signal code:  (-6)
[pkrvm7jw40e0xgp:07000] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9607445330]
[pkrvm7jw40e0xgp:07000] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f960749eb2c]
[pkrvm7jw40e0xgp:07000] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f960744527e]
[pkrvm7jw40e0xgp:07000] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f96074288ff]
[pkrvm7jw40e0xgp:07000] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f96078a5ff5]
[pkrvm7jw40e0xgp:07000] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f96078bb0da]
[pkrvm7jw40e0xgp:07000] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f96078a5a55]
[pkrvm7jw40e0xgp:07000] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f96078a5a6f]
[pkrvm7jw40e0xgp:07000] [ 8] plumed_master(+0x146dd)[0x55725358d6dd]
[pkrvm7jw40e0xgp:07000] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f960742a1ca]
[pkrvm7jw40e0xgp:07000] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f960742a28b]
[pkrvm7jw40e0xgp:07000] [11] plumed_master(+0x15365)[0x55725358e365]
[pkrvm7jw40e0xgp:07000] *** End of error message ***
</pre>
{% endraw %}
