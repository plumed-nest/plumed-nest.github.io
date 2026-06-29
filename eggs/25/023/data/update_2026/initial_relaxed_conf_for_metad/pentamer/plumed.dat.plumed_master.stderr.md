**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/pentamer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:80) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmmklqx:04846] *** Process received signal ***
[runnervmmklqx:04846] Signal: Aborted (6)
[runnervmmklqx:04846] Signal code:  (-6)
[runnervmmklqx:04846] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe4f045330]
[runnervmmklqx:04846] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe4f09eb2c]
[runnervmmklqx:04846] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe4f04527e]
[runnervmmklqx:04846] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe4f0288ff]
[runnervmmklqx:04846] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe4f4a5ff5]
[runnervmmklqx:04846] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe4f4bb0da]
[runnervmmklqx:04846] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe4f4a5a55]
[runnervmmklqx:04846] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe4f4a5a6f]
[runnervmmklqx:04846] [ 8] plumed_master(+0x146dd)[0x55793e26f6dd]
[runnervmmklqx:04846] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe4f02a1ca]
[runnervmmklqx:04846] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe4f02a28b]
[runnervmmklqx:04846] [11] plumed_master(+0x15365)[0x55793e270365]
[runnervmmklqx:04846] *** End of error message ***
</pre>
{% endraw %}
