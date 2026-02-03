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
[runnervmkj6or:06244] *** Process received signal ***
[runnervmkj6or:06244] Signal: Aborted (6)
[runnervmkj6or:06244] Signal code:  (-6)
[runnervmkj6or:06244] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff415445330]
[runnervmkj6or:06244] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff41549eb2c]
[runnervmkj6or:06244] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff41544527e]
[runnervmkj6or:06244] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff4154288ff]
[runnervmkj6or:06244] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff4158a5ff5]
[runnervmkj6or:06244] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff4158bb0da]
[runnervmkj6or:06244] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff4158a5a55]
[runnervmkj6or:06244] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff4158a5a6f]
[runnervmkj6or:06244] [ 8] plumed(+0x146dd)[0x55eca73e36dd]
[runnervmkj6or:06244] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff41542a1ca]
[runnervmkj6or:06244] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff41542a28b]
[runnervmkj6or:06244] [11] plumed(+0x15365)[0x55eca73e4365]
[runnervmkj6or:06244] *** End of error message ***
</pre>
{% endraw %}
