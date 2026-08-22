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
[runnervm76f27:05455] *** Process received signal ***
[runnervm76f27:05455] Signal: Aborted (6)
[runnervm76f27:05455] Signal code:  (-6)
[runnervm76f27:05455] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd158e45330]
[runnervm76f27:05455] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd158e9ec0c]
[runnervm76f27:05455] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd158e4527e]
[runnervm76f27:05455] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd158e288ff]
[runnervm76f27:05455] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd1592a5ff5]
[runnervm76f27:05455] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd1592bb0da]
[runnervm76f27:05455] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd1592a5a55]
[runnervm76f27:05455] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd1592a5a6f]
[runnervm76f27:05455] [ 8] plumed(+0x146dd)[0x5622ecd256dd]
[runnervm76f27:05455] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd158e2a1ca]
[runnervm76f27:05455] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd158e2a28b]
[runnervm76f27:05455] [11] plumed(+0x15365)[0x5622ecd26365]
[runnervm76f27:05455] *** End of error message ***
</pre>
{% endraw %}
