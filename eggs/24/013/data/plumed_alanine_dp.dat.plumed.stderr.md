**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[fv-az1947-163:60920] *** Process received signal ***
[fv-az1947-163:60920] Signal: Aborted (6)
[fv-az1947-163:60920] Signal code:  (-6)
[fv-az1947-163:60920] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f15f0c45330]
[fv-az1947-163:60920] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f15f0c9eb2c]
[fv-az1947-163:60920] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f15f0c4527e]
[fv-az1947-163:60920] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f15f0c288ff]
[fv-az1947-163:60920] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f15f10a5ff5]
[fv-az1947-163:60920] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f15f10bb0da]
[fv-az1947-163:60920] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f15f10a5a55]
[fv-az1947-163:60920] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f15f10a5a6f]
[fv-az1947-163:60920] [ 8] plumed(+0x146dd)[0x5615db0836dd]
[fv-az1947-163:60920] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f15f0c2a1ca]
[fv-az1947-163:60920] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f15f0c2a28b]
[fv-az1947-163:60920] [11] plumed(+0x15365)[0x5615db084365]
[fv-az1947-163:60920] *** End of error message ***
</pre>
{% endraw %}
