**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervmvrwv9:04880] *** Process received signal ***
[runnervmvrwv9:04880] Signal: Aborted (6)
[runnervmvrwv9:04880] Signal code:  (-6)
[runnervmvrwv9:04880] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7a9fe45330]
[runnervmvrwv9:04880] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7a9fe9eb2c]
[runnervmvrwv9:04880] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7a9fe4527e]
[runnervmvrwv9:04880] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7a9fe288ff]
[runnervmvrwv9:04880] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7aa02a5ff5]
[runnervmvrwv9:04880] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7aa02bb0da]
[runnervmvrwv9:04880] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7aa02a5a55]
[runnervmvrwv9:04880] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7aa02a5a6f]
[runnervmvrwv9:04880] [ 8] plumed_master(+0x146dd)[0x55a02e48a6dd]
[runnervmvrwv9:04880] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7a9fe2a1ca]
[runnervmvrwv9:04880] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7a9fe2a28b]
[runnervmvrwv9:04880] [11] plumed_master(+0x15365)[0x55a02e48b365]
[runnervmvrwv9:04880] *** End of error message ***
</pre>
{% endraw %}
