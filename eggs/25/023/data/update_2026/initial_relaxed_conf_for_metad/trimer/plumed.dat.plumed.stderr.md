**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/trimer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:67) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervm0kj6c:04879] *** Process received signal ***
[runnervm0kj6c:04879] Signal: Aborted (6)
[runnervm0kj6c:04879] Signal code:  (-6)
[runnervm0kj6c:04879] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8366c45330]
[runnervm0kj6c:04879] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8366c9eb2c]
[runnervm0kj6c:04879] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8366c4527e]
[runnervm0kj6c:04879] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8366c288ff]
[runnervm0kj6c:04879] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83670a5ff5]
[runnervm0kj6c:04879] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83670bb0da]
[runnervm0kj6c:04879] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83670a5a55]
[runnervm0kj6c:04879] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83670a5a6f]
[runnervm0kj6c:04879] [ 8] plumed(+0x146dd)[0x56231b1aa6dd]
[runnervm0kj6c:04879] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8366c2a1ca]
[runnervm0kj6c:04879] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8366c2a28b]
[runnervm0kj6c:04879] [11] plumed(+0x15365)[0x56231b1ab365]
[runnervm0kj6c:04879] *** End of error message ***
</pre>
{% endraw %}
