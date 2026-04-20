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
[runnervmeorf1:04870] *** Process received signal ***
[runnervmeorf1:04870] Signal: Aborted (6)
[runnervmeorf1:04870] Signal code:  (-6)
[runnervmeorf1:04870] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f36d2445330]
[runnervmeorf1:04870] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f36d249eb2c]
[runnervmeorf1:04870] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f36d244527e]
[runnervmeorf1:04870] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36d24288ff]
[runnervmeorf1:04870] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f36d28a5ff5]
[runnervmeorf1:04870] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f36d28bb0da]
[runnervmeorf1:04870] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f36d28a5a55]
[runnervmeorf1:04870] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f36d28a5a6f]
[runnervmeorf1:04870] [ 8] plumed(+0x146dd)[0x5571a70c26dd]
[runnervmeorf1:04870] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f36d242a1ca]
[runnervmeorf1:04870] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f36d242a28b]
[runnervmeorf1:04870] [11] plumed(+0x15365)[0x5571a70c3365]
[runnervmeorf1:04870] *** End of error message ***
</pre>
{% endraw %}
