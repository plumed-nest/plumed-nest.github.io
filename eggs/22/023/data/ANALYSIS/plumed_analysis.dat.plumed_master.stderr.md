**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmw9dnm:08969] *** Process received signal ***
[runnervmw9dnm:08969] Signal: Aborted (6)
[runnervmw9dnm:08969] Signal code:  (-6)
[runnervmw9dnm:08969] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1a1e645330]
[runnervmw9dnm:08969] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1a1e69eb2c]
[runnervmw9dnm:08969] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1a1e64527e]
[runnervmw9dnm:08969] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1a1e6288ff]
[runnervmw9dnm:08969] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1a1eaa5ff5]
[runnervmw9dnm:08969] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1a1eabb0da]
[runnervmw9dnm:08969] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1a1eaa5a55]
[runnervmw9dnm:08969] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1a1eaa5a6f]
[runnervmw9dnm:08969] [ 8] plumed_master(+0x146dd)[0x555cd47c46dd]
[runnervmw9dnm:08969] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1a1e62a1ca]
[runnervmw9dnm:08969] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1a1e62a28b]
[runnervmw9dnm:08969] [11] plumed_master(+0x15365)[0x555cd47c5365]
[runnervmw9dnm:08969] *** End of error message ***
</pre>
{% endraw %}
