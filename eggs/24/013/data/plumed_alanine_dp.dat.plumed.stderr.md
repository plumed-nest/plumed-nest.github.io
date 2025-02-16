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
[fv-az1937-158:61189] *** Process received signal ***
[fv-az1937-158:61189] Signal: Aborted (6)
[fv-az1937-158:61189] Signal code:  (-6)
[fv-az1937-158:61189] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc5f645330]
[fv-az1937-158:61189] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc5f69eb2c]
[fv-az1937-158:61189] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc5f64527e]
[fv-az1937-158:61189] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc5f6288ff]
[fv-az1937-158:61189] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc5faa5ff5]
[fv-az1937-158:61189] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc5fabb0da]
[fv-az1937-158:61189] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc5faa5a55]
[fv-az1937-158:61189] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc5faa5a6f]
[fv-az1937-158:61189] [ 8] plumed(+0x146dd)[0x55994b9eb6dd]
[fv-az1937-158:61189] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc5f62a1ca]
[fv-az1937-158:61189] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc5f62a28b]
[fv-az1937-158:61189] [11] plumed(+0x15365)[0x55994b9ec365]
[fv-az1937-158:61189] *** End of error message ***
</pre>
{% endraw %}
