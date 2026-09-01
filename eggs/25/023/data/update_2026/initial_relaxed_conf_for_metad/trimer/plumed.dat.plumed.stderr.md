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
[runnervmgx7h7:05365] *** Process received signal ***
[runnervmgx7h7:05365] Signal: Aborted (6)
[runnervmgx7h7:05365] Signal code:  (-6)
[runnervmgx7h7:05365] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ae0c45330]
[runnervmgx7h7:05365] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ae0c9ec0c]
[runnervmgx7h7:05365] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ae0c4527e]
[runnervmgx7h7:05365] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ae0c288ff]
[runnervmgx7h7:05365] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ae10a5ff5]
[runnervmgx7h7:05365] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ae10bb0da]
[runnervmgx7h7:05365] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ae10a5a55]
[runnervmgx7h7:05365] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ae10a5a6f]
[runnervmgx7h7:05365] [ 8] plumed(+0x146dd)[0x5595c13dd6dd]
[runnervmgx7h7:05365] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ae0c2a1ca]
[runnervmgx7h7:05365] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ae0c2a28b]
[runnervmgx7h7:05365] [11] plumed(+0x15365)[0x5595c13de365]
[runnervmgx7h7:05365] *** End of error message ***
</pre>
{% endraw %}
