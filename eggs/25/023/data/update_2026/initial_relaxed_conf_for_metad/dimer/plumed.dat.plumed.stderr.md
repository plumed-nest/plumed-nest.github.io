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
[runnervmgx7h7:05157] *** Process received signal ***
[runnervmgx7h7:05157] Signal: Aborted (6)
[runnervmgx7h7:05157] Signal code:  (-6)
[runnervmgx7h7:05157] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4f5fa45330]
[runnervmgx7h7:05157] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4f5fa9ec0c]
[runnervmgx7h7:05157] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4f5fa4527e]
[runnervmgx7h7:05157] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4f5fa288ff]
[runnervmgx7h7:05157] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4f5fea5ff5]
[runnervmgx7h7:05157] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4f5febb0da]
[runnervmgx7h7:05157] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4f5fea5a55]
[runnervmgx7h7:05157] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4f5fea5a6f]
[runnervmgx7h7:05157] [ 8] plumed(+0x146dd)[0x5636759a66dd]
[runnervmgx7h7:05157] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4f5fa2a1ca]
[runnervmgx7h7:05157] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4f5fa2a28b]
[runnervmgx7h7:05157] [11] plumed(+0x15365)[0x5636759a7365]
[runnervmgx7h7:05157] *** End of error message ***
</pre>
{% endraw %}
