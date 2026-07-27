**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmvrwv9:07660] *** Process received signal ***
[runnervmvrwv9:07660] Signal: Aborted (6)
[runnervmvrwv9:07660] Signal code:  (-6)
[runnervmvrwv9:07660] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe28b045330]
[runnervmvrwv9:07660] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe28b09eb2c]
[runnervmvrwv9:07660] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe28b04527e]
[runnervmvrwv9:07660] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe28b0288ff]
[runnervmvrwv9:07660] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe28b4a5ff5]
[runnervmvrwv9:07660] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe28b4bb0da]
[runnervmvrwv9:07660] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe28b4a5a55]
[runnervmvrwv9:07660] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe28b4a5a6f]
[runnervmvrwv9:07660] [ 8] plumed_master(+0x146dd)[0x56383b25e6dd]
[runnervmvrwv9:07660] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe28b02a1ca]
[runnervmvrwv9:07660] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe28b02a28b]
[runnervmvrwv9:07660] [11] plumed_master(+0x15365)[0x56383b25f365]
[runnervmvrwv9:07660] *** End of error message ***
</pre>
{% endraw %}
