**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmbietmlfzoi:62210] *** Process received signal ***
[pkrvmbietmlfzoi:62210] Signal: Aborted (6)
[pkrvmbietmlfzoi:62210] Signal code:  (-6)
[pkrvmbietmlfzoi:62210] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1516045330]
[pkrvmbietmlfzoi:62210] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f151609eb2c]
[pkrvmbietmlfzoi:62210] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f151604527e]
[pkrvmbietmlfzoi:62210] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f15160288ff]
[pkrvmbietmlfzoi:62210] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f15164a5ff5]
[pkrvmbietmlfzoi:62210] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f15164bb0da]
[pkrvmbietmlfzoi:62210] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f15164a5a55]
[pkrvmbietmlfzoi:62210] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f15164a5a6f]
[pkrvmbietmlfzoi:62210] [ 8] plumed_master(+0x146dd)[0x562cf42cd6dd]
[pkrvmbietmlfzoi:62210] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f151602a1ca]
[pkrvmbietmlfzoi:62210] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f151602a28b]
[pkrvmbietmlfzoi:62210] [11] plumed_master(+0x15365)[0x562cf42ce365]
[pkrvmbietmlfzoi:62210] *** End of error message ***
</pre>
{% endraw %}
