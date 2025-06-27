**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:67274] *** Process received signal ***
[pkrvmbietmlfzoi:67274] Signal: Aborted (6)
[pkrvmbietmlfzoi:67274] Signal code:  (-6)
[pkrvmbietmlfzoi:67274] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb1c4045330]
[pkrvmbietmlfzoi:67274] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb1c409eb2c]
[pkrvmbietmlfzoi:67274] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb1c404527e]
[pkrvmbietmlfzoi:67274] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb1c40288ff]
[pkrvmbietmlfzoi:67274] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb1c44a5ff5]
[pkrvmbietmlfzoi:67274] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb1c44bb0da]
[pkrvmbietmlfzoi:67274] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb1c44a5a55]
[pkrvmbietmlfzoi:67274] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb1c44a5a6f]
[pkrvmbietmlfzoi:67274] [ 8] plumed_master(+0x146dd)[0x55cc82bbc6dd]
[pkrvmbietmlfzoi:67274] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb1c402a1ca]
[pkrvmbietmlfzoi:67274] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb1c402a28b]
[pkrvmbietmlfzoi:67274] [11] plumed_master(+0x15365)[0x55cc82bbd365]
[pkrvmbietmlfzoi:67274] *** End of error message ***
</pre>
{% endraw %}
