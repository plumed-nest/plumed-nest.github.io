**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @39 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:65757] *** Process received signal ***
[pkrvmbietmlfzoi:65757] Signal: Aborted (6)
[pkrvmbietmlfzoi:65757] Signal code:  (-6)
[pkrvmbietmlfzoi:65757] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f64d4245330]
[pkrvmbietmlfzoi:65757] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f64d429eb2c]
[pkrvmbietmlfzoi:65757] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f64d424527e]
[pkrvmbietmlfzoi:65757] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f64d42288ff]
[pkrvmbietmlfzoi:65757] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64d46a5ff5]
[pkrvmbietmlfzoi:65757] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64d46bb0da]
[pkrvmbietmlfzoi:65757] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64d46a5a55]
[pkrvmbietmlfzoi:65757] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64d46a5a6f]
[pkrvmbietmlfzoi:65757] [ 8] plumed_master(+0x146dd)[0x55fd81db36dd]
[pkrvmbietmlfzoi:65757] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f64d422a1ca]
[pkrvmbietmlfzoi:65757] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f64d422a28b]
[pkrvmbietmlfzoi:65757] [11] plumed_master(+0x15365)[0x55fd81db4365]
[pkrvmbietmlfzoi:65757] *** End of error message ***
</pre>
{% endraw %}
