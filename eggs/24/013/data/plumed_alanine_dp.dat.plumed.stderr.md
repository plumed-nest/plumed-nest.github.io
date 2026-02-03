**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[runnervmkj6or:06159] *** Process received signal ***
[runnervmkj6or:06159] Signal: Aborted (6)
[runnervmkj6or:06159] Signal code:  (-6)
[runnervmkj6or:06159] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbec5245330]
[runnervmkj6or:06159] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbec529eb2c]
[runnervmkj6or:06159] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbec524527e]
[runnervmkj6or:06159] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbec52288ff]
[runnervmkj6or:06159] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbec56a5ff5]
[runnervmkj6or:06159] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbec56bb0da]
[runnervmkj6or:06159] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbec56a5a55]
[runnervmkj6or:06159] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbec56a5a6f]
[runnervmkj6or:06159] [ 8] plumed(+0x146dd)[0x55a1f3f996dd]
[runnervmkj6or:06159] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbec522a1ca]
[runnervmkj6or:06159] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbec522a28b]
[runnervmkj6or:06159] [11] plumed(+0x15365)[0x55a1f3f9a365]
[runnervmkj6or:06159] *** End of error message ***
</pre>
{% endraw %}
