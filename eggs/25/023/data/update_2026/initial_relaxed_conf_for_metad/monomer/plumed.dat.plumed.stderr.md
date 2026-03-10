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
[runnervm0kj6c:04723] *** Process received signal ***
[runnervm0kj6c:04723] Signal: Aborted (6)
[runnervm0kj6c:04723] Signal code:  (-6)
[runnervm0kj6c:04723] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1258a45330]
[runnervm0kj6c:04723] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1258a9eb2c]
[runnervm0kj6c:04723] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1258a4527e]
[runnervm0kj6c:04723] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1258a288ff]
[runnervm0kj6c:04723] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1258ea5ff5]
[runnervm0kj6c:04723] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1258ebb0da]
[runnervm0kj6c:04723] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1258ea5a55]
[runnervm0kj6c:04723] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1258ea5a6f]
[runnervm0kj6c:04723] [ 8] plumed(+0x146dd)[0x55aab6b706dd]
[runnervm0kj6c:04723] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1258a2a1ca]
[runnervm0kj6c:04723] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1258a2a28b]
[runnervm0kj6c:04723] [11] plumed(+0x15365)[0x55aab6b71365]
[runnervm0kj6c:04723] *** End of error message ***
</pre>
{% endraw %}
