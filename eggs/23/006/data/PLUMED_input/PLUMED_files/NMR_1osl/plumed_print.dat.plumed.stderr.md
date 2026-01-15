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
[runnervmi13qx:33532] *** Process received signal ***
[runnervmi13qx:33532] Signal: Aborted (6)
[runnervmi13qx:33532] Signal code:  (-6)
[runnervmi13qx:33532] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f912b245330]
[runnervmi13qx:33532] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f912b29eb2c]
[runnervmi13qx:33532] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f912b24527e]
[runnervmi13qx:33532] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f912b2288ff]
[runnervmi13qx:33532] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f912b6a5ff5]
[runnervmi13qx:33532] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f912b6bb0da]
[runnervmi13qx:33532] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f912b6a5a55]
[runnervmi13qx:33532] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f912b6a5a6f]
[runnervmi13qx:33532] [ 8] plumed(+0x146dd)[0x55c366a3e6dd]
[runnervmi13qx:33532] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f912b22a1ca]
[runnervmi13qx:33532] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f912b22a28b]
[runnervmi13qx:33532] [11] plumed(+0x15365)[0x55c366a3f365]
[runnervmi13qx:33532] *** End of error message ***
</pre>
{% endraw %}
