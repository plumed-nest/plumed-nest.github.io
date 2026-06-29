**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/monomer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:80) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmmklqx:04794] *** Process received signal ***
[runnervmmklqx:04794] Signal: Aborted (6)
[runnervmmklqx:04794] Signal code:  (-6)
[runnervmmklqx:04794] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f854e445330]
[runnervmmklqx:04794] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f854e49eb2c]
[runnervmmklqx:04794] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f854e44527e]
[runnervmmklqx:04794] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f854e4288ff]
[runnervmmklqx:04794] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f854e8a5ff5]
[runnervmmklqx:04794] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f854e8bb0da]
[runnervmmklqx:04794] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f854e8a5a55]
[runnervmmklqx:04794] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f854e8a5a6f]
[runnervmmklqx:04794] [ 8] plumed_master(+0x146dd)[0x5634206b56dd]
[runnervmmklqx:04794] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f854e42a1ca]
[runnervmmklqx:04794] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f854e42a28b]
[runnervmmklqx:04794] [11] plumed_master(+0x15365)[0x5634206b6365]
[runnervmmklqx:04794] *** End of error message ***
</pre>
{% endraw %}
