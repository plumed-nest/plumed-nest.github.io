**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmbietmlfzoi:08758] *** Process received signal ***
[pkrvmbietmlfzoi:08758] Signal: Aborted (6)
[pkrvmbietmlfzoi:08758] Signal code:  (-6)
[pkrvmbietmlfzoi:08758] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efebe045330]
[pkrvmbietmlfzoi:08758] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efebe09eb2c]
[pkrvmbietmlfzoi:08758] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efebe04527e]
[pkrvmbietmlfzoi:08758] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efebe0288ff]
[pkrvmbietmlfzoi:08758] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efebe4a5ff5]
[pkrvmbietmlfzoi:08758] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efebe4bb0da]
[pkrvmbietmlfzoi:08758] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efebe4a5a55]
[pkrvmbietmlfzoi:08758] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efebe4a5a6f]
[pkrvmbietmlfzoi:08758] [ 8] plumed(+0x146dd)[0x557cac4bb6dd]
[pkrvmbietmlfzoi:08758] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efebe02a1ca]
[pkrvmbietmlfzoi:08758] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efebe02a28b]
[pkrvmbietmlfzoi:08758] [11] plumed(+0x15365)[0x557cac4bc365]
[pkrvmbietmlfzoi:08758] *** End of error message ***
</pre>
{% endraw %}
