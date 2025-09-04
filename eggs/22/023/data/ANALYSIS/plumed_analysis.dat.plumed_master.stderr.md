**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[pkrvm7jw40e0xgp:08117] *** Process received signal ***
[pkrvm7jw40e0xgp:08117] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08117] Signal code:  (-6)
[pkrvm7jw40e0xgp:08117] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd4ab245330]
[pkrvm7jw40e0xgp:08117] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd4ab29eb2c]
[pkrvm7jw40e0xgp:08117] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd4ab24527e]
[pkrvm7jw40e0xgp:08117] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4ab2288ff]
[pkrvm7jw40e0xgp:08117] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4ab6a5ff5]
[pkrvm7jw40e0xgp:08117] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4ab6bb0da]
[pkrvm7jw40e0xgp:08117] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4ab6a5a55]
[pkrvm7jw40e0xgp:08117] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4ab6a5a6f]
[pkrvm7jw40e0xgp:08117] [ 8] plumed_master(+0x146dd)[0x5648cc7da6dd]
[pkrvm7jw40e0xgp:08117] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd4ab22a1ca]
[pkrvm7jw40e0xgp:08117] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd4ab22a28b]
[pkrvm7jw40e0xgp:08117] [11] plumed_master(+0x15365)[0x5648cc7db365]
[pkrvm7jw40e0xgp:08117] *** End of error message ***
</pre>
{% endraw %}
