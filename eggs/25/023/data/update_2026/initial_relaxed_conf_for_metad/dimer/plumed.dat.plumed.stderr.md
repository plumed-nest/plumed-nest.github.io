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
[runnervm76f27:05298] *** Process received signal ***
[runnervm76f27:05298] Signal: Aborted (6)
[runnervm76f27:05298] Signal code:  (-6)
[runnervm76f27:05298] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f43445330]
[runnervm76f27:05298] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f4349ec0c]
[runnervm76f27:05298] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f4344527e]
[runnervm76f27:05298] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f434288ff]
[runnervm76f27:05298] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f438a5ff5]
[runnervm76f27:05298] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f438bb0da]
[runnervm76f27:05298] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f438a5a55]
[runnervm76f27:05298] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f438a5a6f]
[runnervm76f27:05298] [ 8] plumed(+0x146dd)[0x55f0c72ae6dd]
[runnervm76f27:05298] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f4342a1ca]
[runnervm76f27:05298] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f4342a28b]
[runnervm76f27:05298] [11] plumed(+0x15365)[0x55f0c72af365]
[runnervm76f27:05298] *** End of error message ***
</pre>
{% endraw %}
