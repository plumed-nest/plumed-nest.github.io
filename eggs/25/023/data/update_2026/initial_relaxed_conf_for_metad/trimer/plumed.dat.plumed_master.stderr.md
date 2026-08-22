**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/initial_relaxed_conf_for_metad/trimer/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(colvar/RMSDShortcut.cpp:80) PLMD::colvar::RMSDShortcut::RMSDShortcut(const PLMD::ActionOptions&)
missing file prot_ref_a.pdb
[runnervm76f27:05522] *** Process received signal ***
[runnervm76f27:05522] Signal: Aborted (6)
[runnervm76f27:05522] Signal code:  (-6)
[runnervm76f27:05522] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd878845330]
[runnervm76f27:05522] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd87889ec0c]
[runnervm76f27:05522] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd87884527e]
[runnervm76f27:05522] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd8788288ff]
[runnervm76f27:05522] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd878ca5ff5]
[runnervm76f27:05522] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd878cbb0da]
[runnervm76f27:05522] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd878ca5a55]
[runnervm76f27:05522] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd878ca5a6f]
[runnervm76f27:05522] [ 8] plumed_master(+0x146dd)[0x562368c9b6dd]
[runnervm76f27:05522] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd87882a1ca]
[runnervm76f27:05522] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd87882a28b]
[runnervm76f27:05522] [11] plumed_master(+0x15365)[0x562368c9c365]
[runnervm76f27:05522] *** End of error message ***
</pre>
{% endraw %}
