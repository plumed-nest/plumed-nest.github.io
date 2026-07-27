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
[runnervmvrwv9:05067] *** Process received signal ***
[runnervmvrwv9:05067] Signal: Aborted (6)
[runnervmvrwv9:05067] Signal code:  (-6)
[runnervmvrwv9:05067] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fea42245330]
[runnervmvrwv9:05067] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fea4229eb2c]
[runnervmvrwv9:05067] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fea4224527e]
[runnervmvrwv9:05067] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fea422288ff]
[runnervmvrwv9:05067] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fea426a5ff5]
[runnervmvrwv9:05067] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fea426bb0da]
[runnervmvrwv9:05067] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fea426a5a55]
[runnervmvrwv9:05067] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fea426a5a6f]
[runnervmvrwv9:05067] [ 8] plumed(+0x146dd)[0x55c02f2096dd]
[runnervmvrwv9:05067] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fea4222a1ca]
[runnervmvrwv9:05067] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fea4222a28b]
[runnervmvrwv9:05067] [11] plumed(+0x15365)[0x55c02f20a365]
[runnervmvrwv9:05067] *** End of error message ***
</pre>
{% endraw %}
