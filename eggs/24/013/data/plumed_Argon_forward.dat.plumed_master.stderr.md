**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmbietmlfzoi:62261] *** Process received signal ***
[pkrvmbietmlfzoi:62261] Signal: Aborted (6)
[pkrvmbietmlfzoi:62261] Signal code:  (-6)
[pkrvmbietmlfzoi:62261] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe374e45330]
[pkrvmbietmlfzoi:62261] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe374e9eb2c]
[pkrvmbietmlfzoi:62261] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe374e4527e]
[pkrvmbietmlfzoi:62261] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe374e288ff]
[pkrvmbietmlfzoi:62261] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe3752a5ff5]
[pkrvmbietmlfzoi:62261] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe3752bb0da]
[pkrvmbietmlfzoi:62261] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe3752a5a55]
[pkrvmbietmlfzoi:62261] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe3752a5a6f]
[pkrvmbietmlfzoi:62261] [ 8] plumed_master(+0x146dd)[0x556c4a7796dd]
[pkrvmbietmlfzoi:62261] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe374e2a1ca]
[pkrvmbietmlfzoi:62261] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe374e2a28b]
[pkrvmbietmlfzoi:62261] [11] plumed_master(+0x15365)[0x556c4a77a365]
[pkrvmbietmlfzoi:62261] *** End of error message ***
</pre>
{% endraw %}
