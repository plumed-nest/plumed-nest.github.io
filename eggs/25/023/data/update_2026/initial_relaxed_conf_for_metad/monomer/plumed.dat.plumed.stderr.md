**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/monomer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:67) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmmklqx:04778] *** Process received signal ***
[runnervmmklqx:04778] Signal: Aborted (6)
[runnervmmklqx:04778] Signal code:  (-6)
[runnervmmklqx:04778] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ee0a45330]
[runnervmmklqx:04778] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ee0a9eb2c]
[runnervmmklqx:04778] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ee0a4527e]
[runnervmmklqx:04778] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ee0a288ff]
[runnervmmklqx:04778] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ee0ea5ff5]
[runnervmmklqx:04778] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ee0ebb0da]
[runnervmmklqx:04778] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ee0ea5a55]
[runnervmmklqx:04778] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ee0ea5a6f]
[runnervmmklqx:04778] [ 8] plumed(+0x146dd)[0x55f9e264e6dd]
[runnervmmklqx:04778] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ee0a2a1ca]
[runnervmmklqx:04778] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ee0a2a28b]
[runnervmmklqx:04778] [11] plumed(+0x15365)[0x55f9e264f365]
[runnervmmklqx:04778] *** End of error message ***
</pre>
{% endraw %}
