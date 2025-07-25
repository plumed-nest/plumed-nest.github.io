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
[pkrvmpptgkbjq6m:09290] *** Process received signal ***
[pkrvmpptgkbjq6m:09290] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09290] Signal code:  (-6)
[pkrvmpptgkbjq6m:09290] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f58afa45330]
[pkrvmpptgkbjq6m:09290] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f58afa9eb2c]
[pkrvmpptgkbjq6m:09290] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f58afa4527e]
[pkrvmpptgkbjq6m:09290] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f58afa288ff]
[pkrvmpptgkbjq6m:09290] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f58afea5ff5]
[pkrvmpptgkbjq6m:09290] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f58afebb0da]
[pkrvmpptgkbjq6m:09290] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f58afea5a55]
[pkrvmpptgkbjq6m:09290] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f58afea5a6f]
[pkrvmpptgkbjq6m:09290] [ 8] plumed(+0x146dd)[0x55847d0446dd]
[pkrvmpptgkbjq6m:09290] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f58afa2a1ca]
[pkrvmpptgkbjq6m:09290] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f58afa2a28b]
[pkrvmpptgkbjq6m:09290] [11] plumed(+0x15365)[0x55847d045365]
[pkrvmpptgkbjq6m:09290] *** End of error message ***
</pre>
{% endraw %}
