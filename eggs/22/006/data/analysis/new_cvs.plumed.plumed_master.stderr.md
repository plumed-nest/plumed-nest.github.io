**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @89 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:63461] *** Process received signal ***
[pkrvmbietmlfzoi:63461] Signal: Aborted (6)
[pkrvmbietmlfzoi:63461] Signal code:  (-6)
[pkrvmbietmlfzoi:63461] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa9ab645330]
[pkrvmbietmlfzoi:63461] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa9ab69eb2c]
[pkrvmbietmlfzoi:63461] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa9ab64527e]
[pkrvmbietmlfzoi:63461] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa9ab6288ff]
[pkrvmbietmlfzoi:63461] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa9abaa5ff5]
[pkrvmbietmlfzoi:63461] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa9ababb0da]
[pkrvmbietmlfzoi:63461] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa9abaa5a55]
[pkrvmbietmlfzoi:63461] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa9abaa5a6f]
[pkrvmbietmlfzoi:63461] [ 8] plumed_master(+0x146dd)[0x562fad2176dd]
[pkrvmbietmlfzoi:63461] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa9ab62a1ca]
[pkrvmbietmlfzoi:63461] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa9ab62a28b]
[pkrvmbietmlfzoi:63461] [11] plumed_master(+0x15365)[0x562fad218365]
[pkrvmbietmlfzoi:63461] *** End of error message ***
</pre>
{% endraw %}
