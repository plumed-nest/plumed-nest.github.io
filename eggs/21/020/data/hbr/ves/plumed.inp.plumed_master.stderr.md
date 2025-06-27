**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/ves/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @51 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:66010] *** Process received signal ***
[pkrvmbietmlfzoi:66010] Signal: Aborted (6)
[pkrvmbietmlfzoi:66010] Signal code:  (-6)
[pkrvmbietmlfzoi:66010] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b02845330]
[pkrvmbietmlfzoi:66010] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b0289eb2c]
[pkrvmbietmlfzoi:66010] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b0284527e]
[pkrvmbietmlfzoi:66010] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b028288ff]
[pkrvmbietmlfzoi:66010] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b02ca5ff5]
[pkrvmbietmlfzoi:66010] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b02cbb0da]
[pkrvmbietmlfzoi:66010] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b02ca5a55]
[pkrvmbietmlfzoi:66010] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b02ca5a6f]
[pkrvmbietmlfzoi:66010] [ 8] plumed_master(+0x146dd)[0x55ed819056dd]
[pkrvmbietmlfzoi:66010] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b0282a1ca]
[pkrvmbietmlfzoi:66010] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b0282a28b]
[pkrvmbietmlfzoi:66010] [11] plumed_master(+0x15365)[0x55ed81906365]
[pkrvmbietmlfzoi:66010] *** End of error message ***
</pre>
{% endraw %}
