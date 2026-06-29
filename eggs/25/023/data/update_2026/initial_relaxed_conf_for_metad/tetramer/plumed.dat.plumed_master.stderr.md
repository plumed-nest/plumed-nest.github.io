**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/tetramer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:80) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmmklqx:04898] *** Process received signal ***
[runnervmmklqx:04898] Signal: Aborted (6)
[runnervmmklqx:04898] Signal code:  (-6)
[runnervmmklqx:04898] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1825845330]
[runnervmmklqx:04898] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f182589eb2c]
[runnervmmklqx:04898] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f182584527e]
[runnervmmklqx:04898] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f18258288ff]
[runnervmmklqx:04898] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1825ca5ff5]
[runnervmmklqx:04898] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1825cbb0da]
[runnervmmklqx:04898] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1825ca5a55]
[runnervmmklqx:04898] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1825ca5a6f]
[runnervmmklqx:04898] [ 8] plumed_master(+0x146dd)[0x55cc720256dd]
[runnervmmklqx:04898] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f182582a1ca]
[runnervmmklqx:04898] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f182582a28b]
[runnervmmklqx:04898] [11] plumed_master(+0x15365)[0x55cc72026365]
[runnervmmklqx:04898] *** End of error message ***
</pre>
{% endraw %}
