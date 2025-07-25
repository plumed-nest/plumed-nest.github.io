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
[pkrvmpptgkbjq6m:09239] *** Process received signal ***
[pkrvmpptgkbjq6m:09239] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09239] Signal code:  (-6)
[pkrvmpptgkbjq6m:09239] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f58d3245330]
[pkrvmpptgkbjq6m:09239] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f58d329eb2c]
[pkrvmpptgkbjq6m:09239] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f58d324527e]
[pkrvmpptgkbjq6m:09239] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f58d32288ff]
[pkrvmpptgkbjq6m:09239] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f58d36a5ff5]
[pkrvmpptgkbjq6m:09239] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f58d36bb0da]
[pkrvmpptgkbjq6m:09239] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f58d36a5a55]
[pkrvmpptgkbjq6m:09239] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f58d36a5a6f]
[pkrvmpptgkbjq6m:09239] [ 8] plumed(+0x146dd)[0x5605b9c076dd]
[pkrvmpptgkbjq6m:09239] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f58d322a1ca]
[pkrvmpptgkbjq6m:09239] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f58d322a28b]
[pkrvmpptgkbjq6m:09239] [11] plumed(+0x15365)[0x5605b9c08365]
[pkrvmpptgkbjq6m:09239] *** End of error message ***
</pre>
{% endraw %}
