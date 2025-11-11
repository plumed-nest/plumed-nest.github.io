**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmw9dnm:09005] *** Process received signal ***
[runnervmw9dnm:09005] Signal: Aborted (6)
[runnervmw9dnm:09005] Signal code:  (-6)
[runnervmw9dnm:09005] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6c72845330]
[runnervmw9dnm:09005] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6c7289eb2c]
[runnervmw9dnm:09005] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6c7284527e]
[runnervmw9dnm:09005] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6c728288ff]
[runnervmw9dnm:09005] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6c72ca5ff5]
[runnervmw9dnm:09005] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6c72cbb0da]
[runnervmw9dnm:09005] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6c72ca5a55]
[runnervmw9dnm:09005] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6c72ca5a6f]
[runnervmw9dnm:09005] [ 8] plumed(+0x146dd)[0x55be6ff7b6dd]
[runnervmw9dnm:09005] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6c7282a1ca]
[runnervmw9dnm:09005] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6c7282a28b]
[runnervmw9dnm:09005] [11] plumed(+0x15365)[0x55be6ff7c365]
[runnervmw9dnm:09005] *** End of error message ***
</pre>
{% endraw %}
