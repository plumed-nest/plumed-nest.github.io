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
[runnervmkj6or:06175] *** Process received signal ***
[runnervmkj6or:06175] Signal: Aborted (6)
[runnervmkj6or:06175] Signal code:  (-6)
[runnervmkj6or:06175] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a84645330]
[runnervmkj6or:06175] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a8469eb2c]
[runnervmkj6or:06175] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a8464527e]
[runnervmkj6or:06175] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a846288ff]
[runnervmkj6or:06175] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a84aa5ff5]
[runnervmkj6or:06175] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a84abb0da]
[runnervmkj6or:06175] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a84aa5a55]
[runnervmkj6or:06175] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a84aa5a6f]
[runnervmkj6or:06175] [ 8] plumed_master(+0x146dd)[0x559391bba6dd]
[runnervmkj6or:06175] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a8462a1ca]
[runnervmkj6or:06175] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a8462a28b]
[runnervmkj6or:06175] [11] plumed_master(+0x15365)[0x559391bbb365]
[runnervmkj6or:06175] *** End of error message ***
</pre>
{% endraw %}
