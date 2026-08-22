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
[runnervm76f27:05420] *** Process received signal ***
[runnervm76f27:05420] Signal: Aborted (6)
[runnervm76f27:05420] Signal code:  (-6)
[runnervm76f27:05420] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc2aca45330]
[runnervm76f27:05420] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc2aca9ec0c]
[runnervm76f27:05420] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc2aca4527e]
[runnervm76f27:05420] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc2aca288ff]
[runnervm76f27:05420] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc2acea5ff5]
[runnervm76f27:05420] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc2acebb0da]
[runnervm76f27:05420] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc2acea5a55]
[runnervm76f27:05420] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc2acea5a6f]
[runnervm76f27:05420] [ 8] plumed_master(+0x146dd)[0x556c38edc6dd]
[runnervm76f27:05420] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc2aca2a1ca]
[runnervm76f27:05420] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc2aca2a28b]
[runnervm76f27:05420] [11] plumed_master(+0x15365)[0x556c38edd365]
[runnervm76f27:05420] *** End of error message ***
</pre>
{% endraw %}
