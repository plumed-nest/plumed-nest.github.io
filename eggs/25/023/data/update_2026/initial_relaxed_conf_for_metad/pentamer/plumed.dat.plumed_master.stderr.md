**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/pentamer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:80) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervmeorf1:04781] *** Process received signal ***
[runnervmeorf1:04781] Signal: Aborted (6)
[runnervmeorf1:04781] Signal code:  (-6)
[runnervmeorf1:04781] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f77f2845330]
[runnervmeorf1:04781] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f77f289eb2c]
[runnervmeorf1:04781] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f77f284527e]
[runnervmeorf1:04781] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77f28288ff]
[runnervmeorf1:04781] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77f2ca5ff5]
[runnervmeorf1:04781] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77f2cbb0da]
[runnervmeorf1:04781] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77f2ca5a55]
[runnervmeorf1:04781] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77f2ca5a6f]
[runnervmeorf1:04781] [ 8] plumed_master(+0x146dd)[0x55d07a5016dd]
[runnervmeorf1:04781] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f77f282a1ca]
[runnervmeorf1:04781] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f77f282a28b]
[runnervmeorf1:04781] [11] plumed_master(+0x15365)[0x55d07a502365]
[runnervmeorf1:04781] *** End of error message ***
</pre>
{% endraw %}
