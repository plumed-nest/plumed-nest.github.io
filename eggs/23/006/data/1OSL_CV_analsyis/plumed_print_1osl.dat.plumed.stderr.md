**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[fv-az1701-508:62903] *** Process received signal ***
[fv-az1701-508:62903] Signal: Aborted (6)
[fv-az1701-508:62903] Signal code:  (-6)
[fv-az1701-508:62903] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f03f1445330]
[fv-az1701-508:62903] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f03f149eb2c]
[fv-az1701-508:62903] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f03f144527e]
[fv-az1701-508:62903] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03f14288ff]
[fv-az1701-508:62903] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f03f18a5ff5]
[fv-az1701-508:62903] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f03f18bb0da]
[fv-az1701-508:62903] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f03f18a5a55]
[fv-az1701-508:62903] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f03f18a5a6f]
[fv-az1701-508:62903] [ 8] plumed(+0x146dd)[0x557c620e06dd]
[fv-az1701-508:62903] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f03f142a1ca]
[fv-az1701-508:62903] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f03f142a28b]
[fv-az1701-508:62903] [11] plumed(+0x15365)[0x557c620e1365]
[fv-az1701-508:62903] *** End of error message ***
</pre>
{% endraw %}
