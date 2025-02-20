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
[fv-az816-356:08362] *** Process received signal ***
[fv-az816-356:08362] Signal: Aborted (6)
[fv-az816-356:08362] Signal code:  (-6)
[fv-az816-356:08362] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f51b5245330]
[fv-az816-356:08362] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f51b529eb2c]
[fv-az816-356:08362] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f51b524527e]
[fv-az816-356:08362] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f51b52288ff]
[fv-az816-356:08362] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f51b56a5ff5]
[fv-az816-356:08362] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f51b56bb0da]
[fv-az816-356:08362] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f51b56a5a55]
[fv-az816-356:08362] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f51b56a5a6f]
[fv-az816-356:08362] [ 8] plumed(+0x146dd)[0x56353a5486dd]
[fv-az816-356:08362] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f51b522a1ca]
[fv-az816-356:08362] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f51b522a28b]
[fv-az816-356:08362] [11] plumed(+0x15365)[0x56353a549365]
[fv-az816-356:08362] *** End of error message ***
</pre>
{% endraw %}
