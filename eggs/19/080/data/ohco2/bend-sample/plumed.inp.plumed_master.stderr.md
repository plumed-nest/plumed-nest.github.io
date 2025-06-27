**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:66761] *** Process received signal ***
[pkrvmbietmlfzoi:66761] Signal: Aborted (6)
[pkrvmbietmlfzoi:66761] Signal code:  (-6)
[pkrvmbietmlfzoi:66761] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5954645330]
[pkrvmbietmlfzoi:66761] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f595469eb2c]
[pkrvmbietmlfzoi:66761] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f595464527e]
[pkrvmbietmlfzoi:66761] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f59546288ff]
[pkrvmbietmlfzoi:66761] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5954aa5ff5]
[pkrvmbietmlfzoi:66761] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5954abb0da]
[pkrvmbietmlfzoi:66761] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5954aa5a55]
[pkrvmbietmlfzoi:66761] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5954aa5a6f]
[pkrvmbietmlfzoi:66761] [ 8] plumed_master(+0x146dd)[0x560df769c6dd]
[pkrvmbietmlfzoi:66761] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f595462a1ca]
[pkrvmbietmlfzoi:66761] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f595462a28b]
[pkrvmbietmlfzoi:66761] [11] plumed_master(+0x15365)[0x560df769d365]
[pkrvmbietmlfzoi:66761] *** End of error message ***
</pre>
{% endraw %}
