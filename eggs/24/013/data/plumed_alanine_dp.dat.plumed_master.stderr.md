**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[fv-az1947-163:60936] *** Process received signal ***
[fv-az1947-163:60936] Signal: Aborted (6)
[fv-az1947-163:60936] Signal code:  (-6)
[fv-az1947-163:60936] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8905645330]
[fv-az1947-163:60936] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f890569eb2c]
[fv-az1947-163:60936] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f890564527e]
[fv-az1947-163:60936] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f89056288ff]
[fv-az1947-163:60936] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8905aa5ff5]
[fv-az1947-163:60936] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8905abb0da]
[fv-az1947-163:60936] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8905aa5a55]
[fv-az1947-163:60936] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8905aa5a6f]
[fv-az1947-163:60936] [ 8] plumed_master(+0x146dd)[0x564981ba06dd]
[fv-az1947-163:60936] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f890562a1ca]
[fv-az1947-163:60936] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f890562a28b]
[fv-az1947-163:60936] [11] plumed_master(+0x15365)[0x564981ba1365]
[fv-az1947-163:60936] *** End of error message ***
</pre>
{% endraw %}
