**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/dimer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:67) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervm0kj6c:04669] *** Process received signal ***
[runnervm0kj6c:04669] Signal: Aborted (6)
[runnervm0kj6c:04669] Signal code:  (-6)
[runnervm0kj6c:04669] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5831845330]
[runnervm0kj6c:04669] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f583189eb2c]
[runnervm0kj6c:04669] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f583184527e]
[runnervm0kj6c:04669] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f58318288ff]
[runnervm0kj6c:04669] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5831ca5ff5]
[runnervm0kj6c:04669] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5831cbb0da]
[runnervm0kj6c:04669] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5831ca5a55]
[runnervm0kj6c:04669] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5831ca5a6f]
[runnervm0kj6c:04669] [ 8] plumed(+0x146dd)[0x561f695566dd]
[runnervm0kj6c:04669] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f583182a1ca]
[runnervm0kj6c:04669] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f583182a28b]
[runnervm0kj6c:04669] [11] plumed(+0x15365)[0x561f69557365]
[runnervm0kj6c:04669] *** End of error message ***
</pre>
{% endraw %}
