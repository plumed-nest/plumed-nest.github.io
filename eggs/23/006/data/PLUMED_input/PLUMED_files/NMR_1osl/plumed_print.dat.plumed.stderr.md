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
[runnervmeorf1:05830] *** Process received signal ***
[runnervmeorf1:05830] Signal: Aborted (6)
[runnervmeorf1:05830] Signal code:  (-6)
[runnervmeorf1:05830] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe10445330]
[runnervmeorf1:05830] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe1049eb2c]
[runnervmeorf1:05830] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe1044527e]
[runnervmeorf1:05830] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe104288ff]
[runnervmeorf1:05830] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe108a5ff5]
[runnervmeorf1:05830] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe108bb0da]
[runnervmeorf1:05830] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe108a5a55]
[runnervmeorf1:05830] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe108a5a6f]
[runnervmeorf1:05830] [ 8] plumed(+0x146dd)[0x55cb7a23a6dd]
[runnervmeorf1:05830] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe1042a1ca]
[runnervmeorf1:05830] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe1042a28b]
[runnervmeorf1:05830] [11] plumed(+0x15365)[0x55cb7a23b365]
[runnervmeorf1:05830] *** End of error message ***
</pre>
{% endraw %}
