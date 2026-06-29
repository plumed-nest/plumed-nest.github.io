**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/trimer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:67) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmmklqx:04934] *** Process received signal ***
[runnervmmklqx:04934] Signal: Aborted (6)
[runnervmmklqx:04934] Signal code:  (-6)
[runnervmmklqx:04934] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe528e45330]
[runnervmmklqx:04934] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe528e9eb2c]
[runnervmmklqx:04934] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe528e4527e]
[runnervmmklqx:04934] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe528e288ff]
[runnervmmklqx:04934] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe5292a5ff5]
[runnervmmklqx:04934] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe5292bb0da]
[runnervmmklqx:04934] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe5292a5a55]
[runnervmmklqx:04934] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe5292a5a6f]
[runnervmmklqx:04934] [ 8] plumed(+0x146dd)[0x55d8c91546dd]
[runnervmmklqx:04934] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe528e2a1ca]
[runnervmmklqx:04934] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe528e2a28b]
[runnervmmklqx:04934] [11] plumed(+0x15365)[0x55d8c9155365]
[runnervmmklqx:04934] *** End of error message ***
</pre>
{% endraw %}
