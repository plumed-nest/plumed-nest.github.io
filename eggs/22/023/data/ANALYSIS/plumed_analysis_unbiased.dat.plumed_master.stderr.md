**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az805-507:11399] *** Process received signal ***
[fv-az805-507:11399] Signal: Aborted (6)
[fv-az805-507:11399] Signal code:  (-6)
[fv-az805-507:11399] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f251c045330]
[fv-az805-507:11399] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f251c09eb2c]
[fv-az805-507:11399] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f251c04527e]
[fv-az805-507:11399] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f251c0288ff]
[fv-az805-507:11399] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f251c4a5ff5]
[fv-az805-507:11399] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f251c4bb0da]
[fv-az805-507:11399] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f251c4a5a55]
[fv-az805-507:11399] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f251c4a5a6f]
[fv-az805-507:11399] [ 8] plumed_master(+0x146dd)[0x5582013716dd]
[fv-az805-507:11399] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f251c02a1ca]
[fv-az805-507:11399] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f251c02a28b]
[fv-az805-507:11399] [11] plumed_master(+0x15365)[0x558201372365]
[fv-az805-507:11399] *** End of error message ***
</pre>
{% endraw %}
