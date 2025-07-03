**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s29 : cannot understand the following words from the input line : LOWMEM
[pkrvmbietmlfzoi:08618] *** Process received signal ***
[pkrvmbietmlfzoi:08618] Signal: Aborted (6)
[pkrvmbietmlfzoi:08618] Signal code:  (-6)
[pkrvmbietmlfzoi:08618] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f48d7845330]
[pkrvmbietmlfzoi:08618] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f48d789eb2c]
[pkrvmbietmlfzoi:08618] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f48d784527e]
[pkrvmbietmlfzoi:08618] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f48d78288ff]
[pkrvmbietmlfzoi:08618] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f48d7ca5ff5]
[pkrvmbietmlfzoi:08618] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f48d7cbb0da]
[pkrvmbietmlfzoi:08618] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f48d7ca5a55]
[pkrvmbietmlfzoi:08618] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f48d7ca5a6f]
[pkrvmbietmlfzoi:08618] [ 8] plumed_master(+0x146dd)[0x55f8848e56dd]
[pkrvmbietmlfzoi:08618] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f48d782a1ca]
[pkrvmbietmlfzoi:08618] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f48d782a28b]
[pkrvmbietmlfzoi:08618] [11] plumed_master(+0x15365)[0x55f8848e6365]
[pkrvmbietmlfzoi:08618] *** End of error message ***
</pre>
{% endraw %}
