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
[runnervmkj6or:06137] *** Process received signal ***
[runnervmkj6or:06137] Signal: Aborted (6)
[runnervmkj6or:06137] Signal code:  (-6)
[runnervmkj6or:06137] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f30dd645330]
[runnervmkj6or:06137] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f30dd69eb2c]
[runnervmkj6or:06137] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f30dd64527e]
[runnervmkj6or:06137] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f30dd6288ff]
[runnervmkj6or:06137] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f30ddaa5ff5]
[runnervmkj6or:06137] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f30ddabb0da]
[runnervmkj6or:06137] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f30ddaa5a55]
[runnervmkj6or:06137] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f30ddaa5a6f]
[runnervmkj6or:06137] [ 8] plumed(+0x146dd)[0x563c749bd6dd]
[runnervmkj6or:06137] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f30dd62a1ca]
[runnervmkj6or:06137] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f30dd62a28b]
[runnervmkj6or:06137] [11] plumed(+0x15365)[0x563c749be365]
[runnervmkj6or:06137] *** End of error message ***
</pre>
{% endraw %}
