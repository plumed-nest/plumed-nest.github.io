**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/dimer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:67) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmmklqx:04726] *** Process received signal ***
[runnervmmklqx:04726] Signal: Aborted (6)
[runnervmmklqx:04726] Signal code:  (-6)
[runnervmmklqx:04726] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0151e45330]
[runnervmmklqx:04726] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0151e9eb2c]
[runnervmmklqx:04726] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0151e4527e]
[runnervmmklqx:04726] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0151e288ff]
[runnervmmklqx:04726] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f01522a5ff5]
[runnervmmklqx:04726] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f01522bb0da]
[runnervmmklqx:04726] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f01522a5a55]
[runnervmmklqx:04726] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f01522a5a6f]
[runnervmmklqx:04726] [ 8] plumed(+0x146dd)[0x5641b36866dd]
[runnervmmklqx:04726] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0151e2a1ca]
[runnervmmklqx:04726] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0151e2a28b]
[runnervmmklqx:04726] [11] plumed(+0x15365)[0x5641b3687365]
[runnervmmklqx:04726] *** End of error message ***
</pre>
{% endraw %}
