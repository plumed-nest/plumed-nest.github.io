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
[runnervm76f27:05366] *** Process received signal ***
[runnervm76f27:05366] Signal: Aborted (6)
[runnervm76f27:05366] Signal code:  (-6)
[runnervm76f27:05366] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7eff9c845330]
[runnervm76f27:05366] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7eff9c89ec0c]
[runnervm76f27:05366] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7eff9c84527e]
[runnervm76f27:05366] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7eff9c8288ff]
[runnervm76f27:05366] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7eff9cca5ff5]
[runnervm76f27:05366] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7eff9ccbb0da]
[runnervm76f27:05366] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7eff9cca5a55]
[runnervm76f27:05366] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7eff9cca5a6f]
[runnervm76f27:05366] [ 8] plumed_master(+0x146dd)[0x55de260146dd]
[runnervm76f27:05366] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7eff9c82a1ca]
[runnervm76f27:05366] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7eff9c82a28b]
[runnervm76f27:05366] [11] plumed_master(+0x15365)[0x55de26015365]
[runnervm76f27:05366] *** End of error message ***
</pre>
{% endraw %}
