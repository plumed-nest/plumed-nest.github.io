**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/monomer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:67) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmgx7h7:05208] *** Process received signal ***
[runnervmgx7h7:05208] Signal: Aborted (6)
[runnervmgx7h7:05208] Signal code:  (-6)
[runnervmgx7h7:05208] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b30c45330]
[runnervmgx7h7:05208] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b30c9ec0c]
[runnervmgx7h7:05208] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b30c4527e]
[runnervmgx7h7:05208] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b30c288ff]
[runnervmgx7h7:05208] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b310a5ff5]
[runnervmgx7h7:05208] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b310bb0da]
[runnervmgx7h7:05208] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b310a5a55]
[runnervmgx7h7:05208] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b310a5a6f]
[runnervmgx7h7:05208] [ 8] plumed(+0x146dd)[0x5557ae1666dd]
[runnervmgx7h7:05208] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b30c2a1ca]
[runnervmgx7h7:05208] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b30c2a28b]
[runnervmgx7h7:05208] [11] plumed(+0x15365)[0x5557ae167365]
[runnervmgx7h7:05208] *** End of error message ***
</pre>
{% endraw %}
