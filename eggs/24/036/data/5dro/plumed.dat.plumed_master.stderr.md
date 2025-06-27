**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  5dro/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @30 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:62475] *** Process received signal ***
[pkrvmbietmlfzoi:62475] Signal: Aborted (6)
[pkrvmbietmlfzoi:62475] Signal code:  (-6)
[pkrvmbietmlfzoi:62475] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b39245330]
[pkrvmbietmlfzoi:62475] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b3929eb2c]
[pkrvmbietmlfzoi:62475] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b3924527e]
[pkrvmbietmlfzoi:62475] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b392288ff]
[pkrvmbietmlfzoi:62475] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b396a5ff5]
[pkrvmbietmlfzoi:62475] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b396bb0da]
[pkrvmbietmlfzoi:62475] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b396a5a55]
[pkrvmbietmlfzoi:62475] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b396a5a6f]
[pkrvmbietmlfzoi:62475] [ 8] plumed_master(+0x146dd)[0x558a39efc6dd]
[pkrvmbietmlfzoi:62475] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b3922a1ca]
[pkrvmbietmlfzoi:62475] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b3922a28b]
[pkrvmbietmlfzoi:62475] [11] plumed_master(+0x15365)[0x558a39efd365]
[pkrvmbietmlfzoi:62475] *** End of error message ***
</pre>
{% endraw %}
