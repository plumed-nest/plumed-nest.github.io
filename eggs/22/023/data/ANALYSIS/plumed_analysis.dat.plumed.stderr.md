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
[fv-az1390-170:09275] *** Process received signal ***
[fv-az1390-170:09275] Signal: Aborted (6)
[fv-az1390-170:09275] Signal code:  (-6)
[fv-az1390-170:09275] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa2e2645330]
[fv-az1390-170:09275] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa2e269eb2c]
[fv-az1390-170:09275] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa2e264527e]
[fv-az1390-170:09275] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa2e26288ff]
[fv-az1390-170:09275] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa2e2aa5ff5]
[fv-az1390-170:09275] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa2e2abb0da]
[fv-az1390-170:09275] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa2e2aa5a55]
[fv-az1390-170:09275] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa2e2aa5a6f]
[fv-az1390-170:09275] [ 8] plumed(+0x146dd)[0x559bfd32b6dd]
[fv-az1390-170:09275] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa2e262a1ca]
[fv-az1390-170:09275] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa2e262a28b]
[fv-az1390-170:09275] [11] plumed(+0x15365)[0x559bfd32c365]
[fv-az1390-170:09275] *** End of error message ***
</pre>
{% endraw %}
