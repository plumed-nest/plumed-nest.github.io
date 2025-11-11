**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmw9dnm:08953] *** Process received signal ***
[runnervmw9dnm:08953] Signal: Aborted (6)
[runnervmw9dnm:08953] Signal code:  (-6)
[runnervmw9dnm:08953] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f043ca45330]
[runnervmw9dnm:08953] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f043ca9eb2c]
[runnervmw9dnm:08953] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f043ca4527e]
[runnervmw9dnm:08953] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f043ca288ff]
[runnervmw9dnm:08953] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f043cea5ff5]
[runnervmw9dnm:08953] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f043cebb0da]
[runnervmw9dnm:08953] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f043cea5a55]
[runnervmw9dnm:08953] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f043cea5a6f]
[runnervmw9dnm:08953] [ 8] plumed(+0x146dd)[0x559cb42216dd]
[runnervmw9dnm:08953] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f043ca2a1ca]
[runnervmw9dnm:08953] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f043ca2a28b]
[runnervmw9dnm:08953] [11] plumed(+0x15365)[0x559cb4222365]
[runnervmw9dnm:08953] *** End of error message ***
</pre>
{% endraw %}
