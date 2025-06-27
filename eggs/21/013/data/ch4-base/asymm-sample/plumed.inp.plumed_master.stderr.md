**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @42 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:66361] *** Process received signal ***
[pkrvmbietmlfzoi:66361] Signal: Aborted (6)
[pkrvmbietmlfzoi:66361] Signal code:  (-6)
[pkrvmbietmlfzoi:66361] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe922a45330]
[pkrvmbietmlfzoi:66361] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe922a9eb2c]
[pkrvmbietmlfzoi:66361] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe922a4527e]
[pkrvmbietmlfzoi:66361] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe922a288ff]
[pkrvmbietmlfzoi:66361] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe922ea5ff5]
[pkrvmbietmlfzoi:66361] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe922ebb0da]
[pkrvmbietmlfzoi:66361] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe922ea5a55]
[pkrvmbietmlfzoi:66361] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe922ea5a6f]
[pkrvmbietmlfzoi:66361] [ 8] plumed_master(+0x146dd)[0x55bc606416dd]
[pkrvmbietmlfzoi:66361] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe922a2a1ca]
[pkrvmbietmlfzoi:66361] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe922a2a28b]
[pkrvmbietmlfzoi:66361] [11] plumed_master(+0x15365)[0x55bc60642365]
[pkrvmbietmlfzoi:66361] *** End of error message ***
</pre>
{% endraw %}
