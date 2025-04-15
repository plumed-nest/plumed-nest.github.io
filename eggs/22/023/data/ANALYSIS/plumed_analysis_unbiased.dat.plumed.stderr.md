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
[fv-az1719-82:63483] *** Process received signal ***
[fv-az1719-82:63483] Signal: Aborted (6)
[fv-az1719-82:63483] Signal code:  (-6)
[fv-az1719-82:63483] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f66f2245330]
[fv-az1719-82:63483] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f66f229eb2c]
[fv-az1719-82:63483] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f66f224527e]
[fv-az1719-82:63483] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f66f22288ff]
[fv-az1719-82:63483] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f66f26a5ff5]
[fv-az1719-82:63483] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f66f26bb0da]
[fv-az1719-82:63483] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f66f26a5a55]
[fv-az1719-82:63483] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f66f26a5a6f]
[fv-az1719-82:63483] [ 8] plumed(+0x146dd)[0x5591fac156dd]
[fv-az1719-82:63483] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f66f222a1ca]
[fv-az1719-82:63483] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f66f222a28b]
[fv-az1719-82:63483] [11] plumed(+0x15365)[0x5591fac16365]
[fv-az1719-82:63483] *** End of error message ***
</pre>
{% endraw %}
