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
[fv-az790-36:69142] *** Process received signal ***
[fv-az790-36:69142] Signal: Aborted (6)
[fv-az790-36:69142] Signal code:  (-6)
[fv-az790-36:69142] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f21e8a45330]
[fv-az790-36:69142] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f21e8a9eb2c]
[fv-az790-36:69142] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f21e8a4527e]
[fv-az790-36:69142] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f21e8a288ff]
[fv-az790-36:69142] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f21e8ea5ff5]
[fv-az790-36:69142] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f21e8ebb0da]
[fv-az790-36:69142] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f21e8ea5a55]
[fv-az790-36:69142] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f21e8ea5a6f]
[fv-az790-36:69142] [ 8] plumed_master(+0x146dd)[0x5650c155c6dd]
[fv-az790-36:69142] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f21e8a2a1ca]
[fv-az790-36:69142] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f21e8a2a28b]
[fv-az790-36:69142] [11] plumed_master(+0x15365)[0x5650c155d365]
[fv-az790-36:69142] *** End of error message ***
</pre>
{% endraw %}
