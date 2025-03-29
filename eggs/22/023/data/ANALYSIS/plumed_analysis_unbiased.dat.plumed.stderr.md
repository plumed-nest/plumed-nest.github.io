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
[fv-az1909-454:63480] *** Process received signal ***
[fv-az1909-454:63480] Signal: Aborted (6)
[fv-az1909-454:63480] Signal code:  (-6)
[fv-az1909-454:63480] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0261645330]
[fv-az1909-454:63480] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f026169eb2c]
[fv-az1909-454:63480] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f026164527e]
[fv-az1909-454:63480] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02616288ff]
[fv-az1909-454:63480] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0261aa5ff5]
[fv-az1909-454:63480] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0261abb0da]
[fv-az1909-454:63480] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0261aa5a55]
[fv-az1909-454:63480] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0261aa5a6f]
[fv-az1909-454:63480] [ 8] plumed(+0x146dd)[0x556c4957a6dd]
[fv-az1909-454:63480] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f026162a1ca]
[fv-az1909-454:63480] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f026162a28b]
[fv-az1909-454:63480] [11] plumed(+0x15365)[0x556c4957b365]
[fv-az1909-454:63480] *** End of error message ***
</pre>
{% endraw %}
