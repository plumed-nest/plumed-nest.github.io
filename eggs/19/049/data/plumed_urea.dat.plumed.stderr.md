**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[pkrvmbietmlfzoi:10295] *** Process received signal ***
[pkrvmbietmlfzoi:10295] Signal: Aborted (6)
[pkrvmbietmlfzoi:10295] Signal code:  (-6)
[pkrvmbietmlfzoi:10295] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1006645330]
[pkrvmbietmlfzoi:10295] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f100669eb2c]
[pkrvmbietmlfzoi:10295] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f100664527e]
[pkrvmbietmlfzoi:10295] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10066288ff]
[pkrvmbietmlfzoi:10295] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1006aa5ff5]
[pkrvmbietmlfzoi:10295] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1006abb0da]
[pkrvmbietmlfzoi:10295] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1006aa5a55]
[pkrvmbietmlfzoi:10295] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1006aa5a6f]
[pkrvmbietmlfzoi:10295] [ 8] plumed(+0x146dd)[0x55cb901476dd]
[pkrvmbietmlfzoi:10295] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f100662a1ca]
[pkrvmbietmlfzoi:10295] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f100662a28b]
[pkrvmbietmlfzoi:10295] [11] plumed(+0x15365)[0x55cb90148365]
[pkrvmbietmlfzoi:10295] *** End of error message ***
</pre>
{% endraw %}
