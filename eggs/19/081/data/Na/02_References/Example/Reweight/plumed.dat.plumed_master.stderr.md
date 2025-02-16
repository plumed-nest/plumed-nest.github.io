**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[fv-az1112-175:69163] *** Process received signal ***
[fv-az1112-175:69163] Signal: Aborted (6)
[fv-az1112-175:69163] Signal code:  (-6)
[fv-az1112-175:69163] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdfc7c45330]
[fv-az1112-175:69163] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdfc7c9eb2c]
[fv-az1112-175:69163] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdfc7c4527e]
[fv-az1112-175:69163] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdfc7c288ff]
[fv-az1112-175:69163] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdfc80a5ff5]
[fv-az1112-175:69163] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdfc80bb0da]
[fv-az1112-175:69163] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdfc80a5a55]
[fv-az1112-175:69163] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdfc80a5a6f]
[fv-az1112-175:69163] [ 8] plumed_master(+0x146dd)[0x564763bd46dd]
[fv-az1112-175:69163] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdfc7c2a1ca]
[fv-az1112-175:69163] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdfc7c2a28b]
[fv-az1112-175:69163] [11] plumed_master(+0x15365)[0x564763bd5365]
[fv-az1112-175:69163] *** End of error message ***
</pre>
{% endraw %}
