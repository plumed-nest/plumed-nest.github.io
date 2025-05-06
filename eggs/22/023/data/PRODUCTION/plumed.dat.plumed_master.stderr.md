**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[fv-az1050-229:64552] *** Process received signal ***
[fv-az1050-229:64552] Signal: Aborted (6)
[fv-az1050-229:64552] Signal code:  (-6)
[fv-az1050-229:64552] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff6ab645330]
[fv-az1050-229:64552] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff6ab69eb2c]
[fv-az1050-229:64552] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff6ab64527e]
[fv-az1050-229:64552] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff6ab6288ff]
[fv-az1050-229:64552] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff6abaa5ff5]
[fv-az1050-229:64552] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff6ababb0da]
[fv-az1050-229:64552] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff6abaa5a55]
[fv-az1050-229:64552] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff6abaa5a6f]
[fv-az1050-229:64552] [ 8] plumed_master(+0x146dd)[0x55c017ea16dd]
[fv-az1050-229:64552] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff6ab62a1ca]
[fv-az1050-229:64552] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff6ab62a28b]
[fv-az1050-229:64552] [11] plumed_master(+0x15365)[0x55c017ea2365]
[fv-az1050-229:64552] *** End of error message ***
</pre>
{% endraw %}
