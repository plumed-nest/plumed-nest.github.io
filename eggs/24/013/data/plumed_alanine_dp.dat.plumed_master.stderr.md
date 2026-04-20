**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[runnervmeorf1:05315] *** Process received signal ***
[runnervmeorf1:05315] Signal: Aborted (6)
[runnervmeorf1:05315] Signal code:  (-6)
[runnervmeorf1:05315] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5a43645330]
[runnervmeorf1:05315] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5a4369eb2c]
[runnervmeorf1:05315] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5a4364527e]
[runnervmeorf1:05315] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5a436288ff]
[runnervmeorf1:05315] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5a43aa5ff5]
[runnervmeorf1:05315] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5a43abb0da]
[runnervmeorf1:05315] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5a43aa5a55]
[runnervmeorf1:05315] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5a43aa5a6f]
[runnervmeorf1:05315] [ 8] plumed_master(+0x146dd)[0x564d9893a6dd]
[runnervmeorf1:05315] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5a4362a1ca]
[runnervmeorf1:05315] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5a4362a28b]
[runnervmeorf1:05315] [11] plumed_master(+0x15365)[0x564d9893b365]
[runnervmeorf1:05315] *** End of error message ***
</pre>
{% endraw %}
