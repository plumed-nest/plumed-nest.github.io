**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/monomer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:67) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmeorf1:04714] *** Process received signal ***
[runnervmeorf1:04714] Signal: Aborted (6)
[runnervmeorf1:04714] Signal code:  (-6)
[runnervmeorf1:04714] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f414a645330]
[runnervmeorf1:04714] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f414a69eb2c]
[runnervmeorf1:04714] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f414a64527e]
[runnervmeorf1:04714] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f414a6288ff]
[runnervmeorf1:04714] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f414aaa5ff5]
[runnervmeorf1:04714] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f414aabb0da]
[runnervmeorf1:04714] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f414aaa5a55]
[runnervmeorf1:04714] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f414aaa5a6f]
[runnervmeorf1:04714] [ 8] plumed(+0x146dd)[0x55e4e996c6dd]
[runnervmeorf1:04714] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f414a62a1ca]
[runnervmeorf1:04714] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f414a62a28b]
[runnervmeorf1:04714] [11] plumed(+0x15365)[0x55e4e996d365]
[runnervmeorf1:04714] *** End of error message ***
</pre>
{% endraw %}
