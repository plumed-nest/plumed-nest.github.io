**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/tetramer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:67) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmmklqx:04882] *** Process received signal ***
[runnervmmklqx:04882] Signal: Aborted (6)
[runnervmmklqx:04882] Signal code:  (-6)
[runnervmmklqx:04882] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb669445330]
[runnervmmklqx:04882] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb66949eb2c]
[runnervmmklqx:04882] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb66944527e]
[runnervmmklqx:04882] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb6694288ff]
[runnervmmklqx:04882] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb6698a5ff5]
[runnervmmklqx:04882] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb6698bb0da]
[runnervmmklqx:04882] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb6698a5a55]
[runnervmmklqx:04882] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb6698a5a6f]
[runnervmmklqx:04882] [ 8] plumed(+0x146dd)[0x5641e2c666dd]
[runnervmmklqx:04882] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb66942a1ca]
[runnervmmklqx:04882] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb66942a28b]
[runnervmmklqx:04882] [11] plumed(+0x15365)[0x5641e2c67365]
[runnervmmklqx:04882] *** End of error message ***
</pre>
{% endraw %}
