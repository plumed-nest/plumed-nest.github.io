**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvmxyh4eaekms:07341] *** Process received signal ***
[pkrvmxyh4eaekms:07341] Signal: Aborted (6)
[pkrvmxyh4eaekms:07341] Signal code:  (-6)
[pkrvmxyh4eaekms:07341] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc4ce445330]
[pkrvmxyh4eaekms:07341] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc4ce49eb2c]
[pkrvmxyh4eaekms:07341] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc4ce44527e]
[pkrvmxyh4eaekms:07341] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4ce4288ff]
[pkrvmxyh4eaekms:07341] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4ce8a5ff5]
[pkrvmxyh4eaekms:07341] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4ce8bb0da]
[pkrvmxyh4eaekms:07341] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4ce8a5a55]
[pkrvmxyh4eaekms:07341] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4ce8a5a6f]
[pkrvmxyh4eaekms:07341] [ 8] plumed_master(+0x146dd)[0x560f275456dd]
[pkrvmxyh4eaekms:07341] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc4ce42a1ca]
[pkrvmxyh4eaekms:07341] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc4ce42a28b]
[pkrvmxyh4eaekms:07341] [11] plumed_master(+0x15365)[0x560f27546365]
[pkrvmxyh4eaekms:07341] *** End of error message ***
</pre>
{% endraw %}
