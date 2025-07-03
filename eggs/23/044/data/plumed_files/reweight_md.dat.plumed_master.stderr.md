**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @31 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:07935] *** Process received signal ***
[pkrvmbietmlfzoi:07935] Signal: Aborted (6)
[pkrvmbietmlfzoi:07935] Signal code:  (-6)
[pkrvmbietmlfzoi:07935] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec10045330]
[pkrvmbietmlfzoi:07935] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec1009eb2c]
[pkrvmbietmlfzoi:07935] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec1004527e]
[pkrvmbietmlfzoi:07935] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec100288ff]
[pkrvmbietmlfzoi:07935] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec104a5ff5]
[pkrvmbietmlfzoi:07935] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec104bb0da]
[pkrvmbietmlfzoi:07935] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec104a5a55]
[pkrvmbietmlfzoi:07935] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec104a5a6f]
[pkrvmbietmlfzoi:07935] [ 8] plumed_master(+0x146dd)[0x55848aed66dd]
[pkrvmbietmlfzoi:07935] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec1002a1ca]
[pkrvmbietmlfzoi:07935] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec1002a28b]
[pkrvmbietmlfzoi:07935] [11] plumed_master(+0x15365)[0x55848aed7365]
[pkrvmbietmlfzoi:07935] *** End of error message ***
</pre>
{% endraw %}
