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
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @40 : keyword ARG is compulsory for this action
[fv-az1277-646:69234] *** Process received signal ***
[fv-az1277-646:69234] Signal: Aborted (6)
[fv-az1277-646:69234] Signal code:  (-6)
[fv-az1277-646:69234] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5e4e445330]
[fv-az1277-646:69234] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5e4e49eb2c]
[fv-az1277-646:69234] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5e4e44527e]
[fv-az1277-646:69234] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5e4e4288ff]
[fv-az1277-646:69234] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5e4e8a5ff5]
[fv-az1277-646:69234] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5e4e8bb0da]
[fv-az1277-646:69234] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5e4e8a5a55]
[fv-az1277-646:69234] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5e4e8a5a6f]
[fv-az1277-646:69234] [ 8] plumed_master(+0x146dd)[0x55d433a0f6dd]
[fv-az1277-646:69234] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5e4e42a1ca]
[fv-az1277-646:69234] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5e4e42a28b]
[fv-az1277-646:69234] [11] plumed_master(+0x15365)[0x55d433a10365]
[fv-az1277-646:69234] *** End of error message ***
</pre>
{% endraw %}
