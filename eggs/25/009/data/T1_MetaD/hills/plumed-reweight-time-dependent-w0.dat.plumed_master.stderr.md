**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w0.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w0.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w0.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[fv-az1680-626:05408] *** Process received signal ***
[fv-az1680-626:05408] Signal: Aborted (6)
[fv-az1680-626:05408] Signal code:  (-6)
[fv-az1680-626:05408] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0739e45330]
[fv-az1680-626:05408] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0739e9eb2c]
[fv-az1680-626:05408] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0739e4527e]
[fv-az1680-626:05408] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0739e288ff]
[fv-az1680-626:05408] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f073a2a5ff5]
[fv-az1680-626:05408] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f073a2bb0da]
[fv-az1680-626:05408] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f073a2a5a55]
[fv-az1680-626:05408] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f073a2a5a6f]
[fv-az1680-626:05408] [ 8] plumed_master(+0x146dd)[0x55e063fff6dd]
[fv-az1680-626:05408] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0739e2a1ca]
[fv-az1680-626:05408] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0739e2a28b]
[fv-az1680-626:05408] [11] plumed_master(+0x15365)[0x55e064000365]
[fv-az1680-626:05408] *** End of error message ***
</pre>
{% endraw %}
