**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @51 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:65972] *** Process received signal ***
[pkrvmbietmlfzoi:65972] Signal: Aborted (6)
[pkrvmbietmlfzoi:65972] Signal code:  (-6)
[pkrvmbietmlfzoi:65972] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f726de45330]
[pkrvmbietmlfzoi:65972] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f726de9eb2c]
[pkrvmbietmlfzoi:65972] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f726de4527e]
[pkrvmbietmlfzoi:65972] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f726de288ff]
[pkrvmbietmlfzoi:65972] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f726e2a5ff5]
[pkrvmbietmlfzoi:65972] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f726e2bb0da]
[pkrvmbietmlfzoi:65972] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f726e2a5a55]
[pkrvmbietmlfzoi:65972] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f726e2a5a6f]
[pkrvmbietmlfzoi:65972] [ 8] plumed_master(+0x146dd)[0x55d64fd766dd]
[pkrvmbietmlfzoi:65972] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f726de2a1ca]
[pkrvmbietmlfzoi:65972] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f726de2a28b]
[pkrvmbietmlfzoi:65972] [11] plumed_master(+0x15365)[0x55d64fd77365]
[pkrvmbietmlfzoi:65972] *** End of error message ***
</pre>
{% endraw %}
