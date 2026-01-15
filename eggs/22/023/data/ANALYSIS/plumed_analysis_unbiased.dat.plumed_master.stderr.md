**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmmtnos:34547] *** Process received signal ***
[runnervmmtnos:34547] Signal: Aborted (6)
[runnervmmtnos:34547] Signal code:  (-6)
[runnervmmtnos:34547] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f66f7245330]
[runnervmmtnos:34547] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f66f729eb2c]
[runnervmmtnos:34547] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f66f724527e]
[runnervmmtnos:34547] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f66f72288ff]
[runnervmmtnos:34547] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f66f76a5ff5]
[runnervmmtnos:34547] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f66f76bb0da]
[runnervmmtnos:34547] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f66f76a5a55]
[runnervmmtnos:34547] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f66f76a5a6f]
[runnervmmtnos:34547] [ 8] plumed_master(+0x146dd)[0x556cd4f406dd]
[runnervmmtnos:34547] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f66f722a1ca]
[runnervmmtnos:34547] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f66f722a28b]
[runnervmmtnos:34547] [11] plumed_master(+0x15365)[0x556cd4f41365]
[runnervmmtnos:34547] *** End of error message ***
</pre>
{% endraw %}
