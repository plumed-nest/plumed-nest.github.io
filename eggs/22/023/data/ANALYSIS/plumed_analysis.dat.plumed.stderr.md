**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmvrwv9:07592] *** Process received signal ***
[runnervmvrwv9:07592] Signal: Aborted (6)
[runnervmvrwv9:07592] Signal code:  (-6)
[runnervmvrwv9:07592] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdc1bc45330]
[runnervmvrwv9:07592] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdc1bc9eb2c]
[runnervmvrwv9:07592] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdc1bc4527e]
[runnervmvrwv9:07592] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdc1bc288ff]
[runnervmvrwv9:07592] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdc1c0a5ff5]
[runnervmvrwv9:07592] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdc1c0bb0da]
[runnervmvrwv9:07592] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdc1c0a5a55]
[runnervmvrwv9:07592] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdc1c0a5a6f]
[runnervmvrwv9:07592] [ 8] plumed(+0x146dd)[0x55618d7806dd]
[runnervmvrwv9:07592] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdc1bc2a1ca]
[runnervmvrwv9:07592] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdc1bc2a28b]
[runnervmvrwv9:07592] [11] plumed(+0x15365)[0x55618d781365]
[runnervmvrwv9:07592] *** End of error message ***
</pre>
{% endraw %}
