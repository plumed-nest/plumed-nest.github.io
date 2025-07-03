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
[pkrvmbietmlfzoi:08261] *** Process received signal ***
[pkrvmbietmlfzoi:08261] Signal: Aborted (6)
[pkrvmbietmlfzoi:08261] Signal code:  (-6)
[pkrvmbietmlfzoi:08261] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f21cfa45330]
[pkrvmbietmlfzoi:08261] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f21cfa9eb2c]
[pkrvmbietmlfzoi:08261] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f21cfa4527e]
[pkrvmbietmlfzoi:08261] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f21cfa288ff]
[pkrvmbietmlfzoi:08261] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f21cfea5ff5]
[pkrvmbietmlfzoi:08261] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f21cfebb0da]
[pkrvmbietmlfzoi:08261] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f21cfea5a55]
[pkrvmbietmlfzoi:08261] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f21cfea5a6f]
[pkrvmbietmlfzoi:08261] [ 8] plumed_master(+0x146dd)[0x561428d3d6dd]
[pkrvmbietmlfzoi:08261] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f21cfa2a1ca]
[pkrvmbietmlfzoi:08261] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f21cfa2a28b]
[pkrvmbietmlfzoi:08261] [11] plumed_master(+0x15365)[0x561428d3e365]
[pkrvmbietmlfzoi:08261] *** End of error message ***
</pre>
{% endraw %}
