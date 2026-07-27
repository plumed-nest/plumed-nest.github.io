**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmvrwv9:04918] *** Process received signal ***
[runnervmvrwv9:04918] Signal: Aborted (6)
[runnervmvrwv9:04918] Signal code:  (-6)
[runnervmvrwv9:04918] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f36d9e45330]
[runnervmvrwv9:04918] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f36d9e9eb2c]
[runnervmvrwv9:04918] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f36d9e4527e]
[runnervmvrwv9:04918] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36d9e288ff]
[runnervmvrwv9:04918] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f36da2a5ff5]
[runnervmvrwv9:04918] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f36da2bb0da]
[runnervmvrwv9:04918] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f36da2a5a55]
[runnervmvrwv9:04918] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f36da2a5a6f]
[runnervmvrwv9:04918] [ 8] plumed_master(+0x146dd)[0x55d8126a16dd]
[runnervmvrwv9:04918] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f36d9e2a1ca]
[runnervmvrwv9:04918] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f36d9e2a28b]
[runnervmvrwv9:04918] [11] plumed_master(+0x15365)[0x55d8126a2365]
[runnervmvrwv9:04918] *** End of error message ***
</pre>
{% endraw %}
