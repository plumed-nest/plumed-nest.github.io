**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az1947-163:60884] *** Process received signal ***
[fv-az1947-163:60884] Signal: Aborted (6)
[fv-az1947-163:60884] Signal code:  (-6)
[fv-az1947-163:60884] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3585e45330]
[fv-az1947-163:60884] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3585e9eb2c]
[fv-az1947-163:60884] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3585e4527e]
[fv-az1947-163:60884] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3585e288ff]
[fv-az1947-163:60884] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f35862a5ff5]
[fv-az1947-163:60884] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f35862bb0da]
[fv-az1947-163:60884] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f35862a5a55]
[fv-az1947-163:60884] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f35862a5a6f]
[fv-az1947-163:60884] [ 8] plumed_master(+0x146dd)[0x55c5128db6dd]
[fv-az1947-163:60884] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3585e2a1ca]
[fv-az1947-163:60884] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3585e2a28b]
[fv-az1947-163:60884] [11] plumed_master(+0x15365)[0x55c5128dc365]
[fv-az1947-163:60884] *** End of error message ***
</pre>
{% endraw %}
