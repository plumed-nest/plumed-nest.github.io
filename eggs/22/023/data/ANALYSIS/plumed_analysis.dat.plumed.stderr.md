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
[fv-az1050-229:64429] *** Process received signal ***
[fv-az1050-229:64429] Signal: Aborted (6)
[fv-az1050-229:64429] Signal code:  (-6)
[fv-az1050-229:64429] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f08dca45330]
[fv-az1050-229:64429] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f08dca9eb2c]
[fv-az1050-229:64429] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f08dca4527e]
[fv-az1050-229:64429] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f08dca288ff]
[fv-az1050-229:64429] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f08dcea5ff5]
[fv-az1050-229:64429] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f08dcebb0da]
[fv-az1050-229:64429] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f08dcea5a55]
[fv-az1050-229:64429] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f08dcea5a6f]
[fv-az1050-229:64429] [ 8] plumed(+0x146dd)[0x55787bf1e6dd]
[fv-az1050-229:64429] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f08dca2a1ca]
[fv-az1050-229:64429] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f08dca2a28b]
[fv-az1050-229:64429] [11] plumed(+0x15365)[0x55787bf1f365]
[fv-az1050-229:64429] *** End of error message ***
</pre>
{% endraw %}
