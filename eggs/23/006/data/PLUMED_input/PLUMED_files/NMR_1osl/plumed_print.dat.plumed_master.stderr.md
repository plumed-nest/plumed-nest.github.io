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
[runnervmeorf1:05845] *** Process received signal ***
[runnervmeorf1:05845] Signal: Aborted (6)
[runnervmeorf1:05845] Signal code:  (-6)
[runnervmeorf1:05845] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec98245330]
[runnervmeorf1:05845] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec9829eb2c]
[runnervmeorf1:05845] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec9824527e]
[runnervmeorf1:05845] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec982288ff]
[runnervmeorf1:05845] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec986a5ff5]
[runnervmeorf1:05845] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec986bb0da]
[runnervmeorf1:05845] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec986a5a55]
[runnervmeorf1:05845] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec986a5a6f]
[runnervmeorf1:05845] [ 8] plumed_master(+0x146dd)[0x56182de136dd]
[runnervmeorf1:05845] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec9822a1ca]
[runnervmeorf1:05845] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec9822a28b]
[runnervmeorf1:05845] [11] plumed_master(+0x15365)[0x56182de14365]
[runnervmeorf1:05845] *** End of error message ***
</pre>
{% endraw %}
