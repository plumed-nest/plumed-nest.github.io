**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[runnervm76f27:08602] *** Process received signal ***
[runnervm76f27:08602] Signal: Aborted (6)
[runnervm76f27:08602] Signal code:  (-6)
[runnervm76f27:08602] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7fb5445330]
[runnervm76f27:08602] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7fb549ec0c]
[runnervm76f27:08602] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7fb544527e]
[runnervm76f27:08602] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7fb54288ff]
[runnervm76f27:08602] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7fb58a5ff5]
[runnervm76f27:08602] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7fb58bb0da]
[runnervm76f27:08602] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7fb58a5a55]
[runnervm76f27:08602] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7fb58a5a6f]
[runnervm76f27:08602] [ 8] plumed(+0x146dd)[0x55e958c716dd]
[runnervm76f27:08602] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7fb542a1ca]
[runnervm76f27:08602] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7fb542a28b]
[runnervm76f27:08602] [11] plumed(+0x15365)[0x55e958c72365]
[runnervm76f27:08602] *** End of error message ***
</pre>
{% endraw %}
