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
[runnervmeorf1:08710] *** Process received signal ***
[runnervmeorf1:08710] Signal: Aborted (6)
[runnervmeorf1:08710] Signal code:  (-6)
[runnervmeorf1:08710] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23b7045330]
[runnervmeorf1:08710] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23b709eb2c]
[runnervmeorf1:08710] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23b704527e]
[runnervmeorf1:08710] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23b70288ff]
[runnervmeorf1:08710] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23b74a5ff5]
[runnervmeorf1:08710] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23b74bb0da]
[runnervmeorf1:08710] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23b74a5a55]
[runnervmeorf1:08710] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23b74a5a6f]
[runnervmeorf1:08710] [ 8] plumed(+0x146dd)[0x5602373156dd]
[runnervmeorf1:08710] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23b702a1ca]
[runnervmeorf1:08710] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23b702a28b]
[runnervmeorf1:08710] [11] plumed(+0x15365)[0x560237316365]
[runnervmeorf1:08710] *** End of error message ***
</pre>
{% endraw %}
