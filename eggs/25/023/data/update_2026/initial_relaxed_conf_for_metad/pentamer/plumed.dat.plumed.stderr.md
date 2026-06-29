**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/pentamer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:67) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmmklqx:04830] *** Process received signal ***
[runnervmmklqx:04830] Signal: Aborted (6)
[runnervmmklqx:04830] Signal code:  (-6)
[runnervmmklqx:04830] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f40cda45330]
[runnervmmklqx:04830] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f40cda9eb2c]
[runnervmmklqx:04830] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f40cda4527e]
[runnervmmklqx:04830] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f40cda288ff]
[runnervmmklqx:04830] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f40cdea5ff5]
[runnervmmklqx:04830] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f40cdebb0da]
[runnervmmklqx:04830] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f40cdea5a55]
[runnervmmklqx:04830] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f40cdea5a6f]
[runnervmmklqx:04830] [ 8] plumed(+0x146dd)[0x5584cc27e6dd]
[runnervmmklqx:04830] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f40cda2a1ca]
[runnervmmklqx:04830] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f40cda2a28b]
[runnervmmklqx:04830] [11] plumed(+0x15365)[0x5584cc27f365]
[runnervmmklqx:04830] *** End of error message ***
</pre>
{% endraw %}
