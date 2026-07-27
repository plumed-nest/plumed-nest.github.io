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
[runnervmvrwv9:04965] *** Process received signal ***
[runnervmvrwv9:04965] Signal: Aborted (6)
[runnervmvrwv9:04965] Signal code:  (-6)
[runnervmvrwv9:04965] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f614ae45330]
[runnervmvrwv9:04965] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f614ae9eb2c]
[runnervmvrwv9:04965] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f614ae4527e]
[runnervmvrwv9:04965] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f614ae288ff]
[runnervmvrwv9:04965] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f614b2a5ff5]
[runnervmvrwv9:04965] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f614b2bb0da]
[runnervmvrwv9:04965] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f614b2a5a55]
[runnervmvrwv9:04965] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f614b2a5a6f]
[runnervmvrwv9:04965] [ 8] plumed(+0x146dd)[0x55df30cf06dd]
[runnervmvrwv9:04965] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f614ae2a1ca]
[runnervmvrwv9:04965] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f614ae2a28b]
[runnervmvrwv9:04965] [11] plumed(+0x15365)[0x55df30cf1365]
[runnervmvrwv9:04965] *** End of error message ***
</pre>
{% endraw %}
