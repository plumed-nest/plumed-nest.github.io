**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmbietmlfzoi:63504] *** Process received signal ***
[pkrvmbietmlfzoi:63504] Signal: Aborted (6)
[pkrvmbietmlfzoi:63504] Signal code:  (-6)
[pkrvmbietmlfzoi:63504] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcd0a045330]
[pkrvmbietmlfzoi:63504] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcd0a09eb2c]
[pkrvmbietmlfzoi:63504] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcd0a04527e]
[pkrvmbietmlfzoi:63504] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcd0a0288ff]
[pkrvmbietmlfzoi:63504] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcd0a4a5ff5]
[pkrvmbietmlfzoi:63504] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcd0a4bb0da]
[pkrvmbietmlfzoi:63504] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcd0a4a5a55]
[pkrvmbietmlfzoi:63504] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcd0a4a5a6f]
[pkrvmbietmlfzoi:63504] [ 8] plumed(+0x146dd)[0x557ecce826dd]
[pkrvmbietmlfzoi:63504] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcd0a02a1ca]
[pkrvmbietmlfzoi:63504] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcd0a02a28b]
[pkrvmbietmlfzoi:63504] [11] plumed(+0x15365)[0x557ecce83365]
[pkrvmbietmlfzoi:63504] *** End of error message ***
</pre>
{% endraw %}
