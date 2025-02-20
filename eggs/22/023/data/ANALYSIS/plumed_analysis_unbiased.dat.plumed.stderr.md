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
[fv-az816-356:08414] *** Process received signal ***
[fv-az816-356:08414] Signal: Aborted (6)
[fv-az816-356:08414] Signal code:  (-6)
[fv-az816-356:08414] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9f55e45330]
[fv-az816-356:08414] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9f55e9eb2c]
[fv-az816-356:08414] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9f55e4527e]
[fv-az816-356:08414] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9f55e288ff]
[fv-az816-356:08414] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9f562a5ff5]
[fv-az816-356:08414] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9f562bb0da]
[fv-az816-356:08414] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9f562a5a55]
[fv-az816-356:08414] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9f562a5a6f]
[fv-az816-356:08414] [ 8] plumed(+0x146dd)[0x5615549536dd]
[fv-az816-356:08414] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9f55e2a1ca]
[fv-az816-356:08414] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9f55e2a28b]
[fv-az816-356:08414] [11] plumed(+0x15365)[0x561554954365]
[fv-az816-356:08414] *** End of error message ***
</pre>
{% endraw %}
