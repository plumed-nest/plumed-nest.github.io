**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @39 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:13647] *** Process received signal ***
[pkrvmbietmlfzoi:13647] Signal: Aborted (6)
[pkrvmbietmlfzoi:13647] Signal code:  (-6)
[pkrvmbietmlfzoi:13647] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5667845330]
[pkrvmbietmlfzoi:13647] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f566789eb2c]
[pkrvmbietmlfzoi:13647] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f566784527e]
[pkrvmbietmlfzoi:13647] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f56678288ff]
[pkrvmbietmlfzoi:13647] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5667ca5ff5]
[pkrvmbietmlfzoi:13647] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5667cbb0da]
[pkrvmbietmlfzoi:13647] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5667ca5a55]
[pkrvmbietmlfzoi:13647] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5667ca5a6f]
[pkrvmbietmlfzoi:13647] [ 8] plumed_master(+0x146dd)[0x5579c77c36dd]
[pkrvmbietmlfzoi:13647] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f566782a1ca]
[pkrvmbietmlfzoi:13647] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f566782a28b]
[pkrvmbietmlfzoi:13647] [11] plumed_master(+0x15365)[0x5579c77c4365]
[pkrvmbietmlfzoi:13647] *** End of error message ***
</pre>
{% endraw %}
