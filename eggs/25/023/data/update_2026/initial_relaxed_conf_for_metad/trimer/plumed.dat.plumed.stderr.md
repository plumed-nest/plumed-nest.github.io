**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/trimer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:67) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervm76f27:05506] *** Process received signal ***
[runnervm76f27:05506] Signal: Aborted (6)
[runnervm76f27:05506] Signal code:  (-6)
[runnervm76f27:05506] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2661c45330]
[runnervm76f27:05506] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2661c9ec0c]
[runnervm76f27:05506] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2661c4527e]
[runnervm76f27:05506] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2661c288ff]
[runnervm76f27:05506] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f26620a5ff5]
[runnervm76f27:05506] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f26620bb0da]
[runnervm76f27:05506] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f26620a5a55]
[runnervm76f27:05506] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f26620a5a6f]
[runnervm76f27:05506] [ 8] plumed(+0x146dd)[0x561b982b96dd]
[runnervm76f27:05506] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2661c2a1ca]
[runnervm76f27:05506] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2661c2a28b]
[runnervm76f27:05506] [11] plumed(+0x15365)[0x561b982ba365]
[runnervm76f27:05506] *** End of error message ***
</pre>
{% endraw %}
