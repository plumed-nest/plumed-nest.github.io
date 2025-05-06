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
[fv-az807-718:61940] *** Process received signal ***
[fv-az807-718:61940] Signal: Aborted (6)
[fv-az807-718:61940] Signal code:  (-6)
[fv-az807-718:61940] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1025e45330]
[fv-az807-718:61940] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1025e9eb2c]
[fv-az807-718:61940] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1025e4527e]
[fv-az807-718:61940] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1025e288ff]
[fv-az807-718:61940] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f10262a5ff5]
[fv-az807-718:61940] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f10262bb0da]
[fv-az807-718:61940] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f10262a5a55]
[fv-az807-718:61940] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f10262a5a6f]
[fv-az807-718:61940] [ 8] plumed(+0x146dd)[0x5571c15db6dd]
[fv-az807-718:61940] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1025e2a1ca]
[fv-az807-718:61940] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1025e2a28b]
[fv-az807-718:61940] [11] plumed(+0x15365)[0x5571c15dc365]
[fv-az807-718:61940] *** End of error message ***
</pre>
{% endraw %}
