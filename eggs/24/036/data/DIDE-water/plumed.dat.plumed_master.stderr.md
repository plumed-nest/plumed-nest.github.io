**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az1693-854:05562] *** Process received signal ***
[fv-az1693-854:05562] Signal: Aborted (6)
[fv-az1693-854:05562] Signal code:  (-6)
[fv-az1693-854:05562] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1102645330]
[fv-az1693-854:05562] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f110269eb2c]
[fv-az1693-854:05562] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f110264527e]
[fv-az1693-854:05562] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f11026288ff]
[fv-az1693-854:05562] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1102aa5ff5]
[fv-az1693-854:05562] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1102abb0da]
[fv-az1693-854:05562] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1102aa5a55]
[fv-az1693-854:05562] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1102aa5a6f]
[fv-az1693-854:05562] [ 8] plumed_master(+0x146dd)[0x563f24b8a6dd]
[fv-az1693-854:05562] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f110262a1ca]
[fv-az1693-854:05562] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f110262a28b]
[fv-az1693-854:05562] [11] plumed_master(+0x15365)[0x563f24b8b365]
[fv-az1693-854:05562] *** End of error message ***
</pre>
{% endraw %}
