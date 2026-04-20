**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/tetramer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:80) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmeorf1:04834] *** Process received signal ***
[runnervmeorf1:04834] Signal: Aborted (6)
[runnervmeorf1:04834] Signal code:  (-6)
[runnervmeorf1:04834] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd1e0445330]
[runnervmeorf1:04834] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd1e049eb2c]
[runnervmeorf1:04834] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd1e044527e]
[runnervmeorf1:04834] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd1e04288ff]
[runnervmeorf1:04834] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd1e08a5ff5]
[runnervmeorf1:04834] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd1e08bb0da]
[runnervmeorf1:04834] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd1e08a5a55]
[runnervmeorf1:04834] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd1e08a5a6f]
[runnervmeorf1:04834] [ 8] plumed_master(+0x146dd)[0x55841a4b66dd]
[runnervmeorf1:04834] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd1e042a1ca]
[runnervmeorf1:04834] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd1e042a28b]
[runnervmeorf1:04834] [11] plumed_master(+0x15365)[0x55841a4b7365]
[runnervmeorf1:04834] *** End of error message ***
</pre>
{% endraw %}
