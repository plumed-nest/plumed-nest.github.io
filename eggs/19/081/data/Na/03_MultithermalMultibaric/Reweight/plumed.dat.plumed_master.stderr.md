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
[fv-az1344-582:67548] *** Process received signal ***
[fv-az1344-582:67548] Signal: Aborted (6)
[fv-az1344-582:67548] Signal code:  (-6)
[fv-az1344-582:67548] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fde59445330]
[fv-az1344-582:67548] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fde5949eb2c]
[fv-az1344-582:67548] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fde5944527e]
[fv-az1344-582:67548] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fde594288ff]
[fv-az1344-582:67548] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fde598a5ff5]
[fv-az1344-582:67548] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fde598bb0da]
[fv-az1344-582:67548] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fde598a5a55]
[fv-az1344-582:67548] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fde598a5a6f]
[fv-az1344-582:67548] [ 8] plumed_master(+0x146dd)[0x564def07f6dd]
[fv-az1344-582:67548] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fde5942a1ca]
[fv-az1344-582:67548] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fde5942a28b]
[fv-az1344-582:67548] [11] plumed_master(+0x15365)[0x564def080365]
[fv-az1344-582:67548] *** End of error message ***
</pre>
{% endraw %}
