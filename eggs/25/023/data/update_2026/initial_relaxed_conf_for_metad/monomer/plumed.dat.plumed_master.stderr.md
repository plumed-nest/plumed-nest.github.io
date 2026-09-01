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
[runnervmgx7h7:05224] *** Process received signal ***
[runnervmgx7h7:05224] Signal: Aborted (6)
[runnervmgx7h7:05224] Signal code:  (-6)
[runnervmgx7h7:05224] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f290da45330]
[runnervmgx7h7:05224] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f290da9ec0c]
[runnervmgx7h7:05224] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f290da4527e]
[runnervmgx7h7:05224] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f290da288ff]
[runnervmgx7h7:05224] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f290dea5ff5]
[runnervmgx7h7:05224] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f290debb0da]
[runnervmgx7h7:05224] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f290dea5a55]
[runnervmgx7h7:05224] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f290dea5a6f]
[runnervmgx7h7:05224] [ 8] plumed_master(+0x146dd)[0x561fa1c896dd]
[runnervmgx7h7:05224] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f290da2a1ca]
[runnervmgx7h7:05224] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f290da2a28b]
[runnervmgx7h7:05224] [11] plumed_master(+0x15365)[0x561fa1c8a365]
[runnervmgx7h7:05224] *** End of error message ***
</pre>
{% endraw %}
