**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[runnervmvrwv9:05138] *** Process received signal ***
[runnervmvrwv9:05138] Signal: Aborted (6)
[runnervmvrwv9:05138] Signal code:  (-6)
[runnervmvrwv9:05138] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe3d6845330]
[runnervmvrwv9:05138] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe3d689eb2c]
[runnervmvrwv9:05138] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe3d684527e]
[runnervmvrwv9:05138] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe3d68288ff]
[runnervmvrwv9:05138] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe3d6ca5ff5]
[runnervmvrwv9:05138] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe3d6cbb0da]
[runnervmvrwv9:05138] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe3d6ca5a55]
[runnervmvrwv9:05138] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe3d6ca5a6f]
[runnervmvrwv9:05138] [ 8] plumed(+0x146dd)[0x55b2473ed6dd]
[runnervmvrwv9:05138] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe3d682a1ca]
[runnervmvrwv9:05138] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe3d682a28b]
[runnervmvrwv9:05138] [11] plumed(+0x15365)[0x55b2473ee365]
[runnervmvrwv9:05138] *** End of error message ***
</pre>
{% endraw %}
